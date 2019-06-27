---
layout: post
title:  "Learning Jekyll"
date:   2019-06-27 02:09:26 -0500
categories: jekyll update
---
Learning more about jekyll. I have to say, it's prtty darn sweet...

This is [the post](http://jmcglone.com/guides/github-pages/) that got me started.

Shout out to Stephanie Hicks for [this post.](http://www.stephaniehicks.com/githubPages_tutorial/pages/githubpages-jekyll.html)

Jekyll also offers powerful support for code snippets:

{% highlight powershell %}
</p>
<div class="code">
# Create a new object
$Result = New-Object -TypeName PSObject
Add-Member -InputObject $Result -MemberType NoteProperty -Name Parameter1 -Value Result1
Add-Member -InputObject $Result -MemberType NoteProperty -Name Parameter2 -Value Result2
return $Result

###################################################################################################

# Create a new object
$Results = @()

foreach($Line in $Lines)
{
    $Result = New-Object -TypeName PSObject
    Add-Member -InputObject $Result -MemberType NoteProperty -Name Parameter1 -Value $Line.Result1
    Add-Member -InputObject $Result -MemberType NoteProperty -Name Parameter2 -Value $Line.Result2
    $Results += $Result
}

return $Results
{% endhighlight %}
</div> <!-- end code div -->
<p>

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
