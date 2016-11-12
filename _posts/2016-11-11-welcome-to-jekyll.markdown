---
layout: post
title:  "Welcome to Jekyll!"
date:   2016-11-11 22:21:43 -0500
categories: jekyll update
---
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

In a Terminal tab, start a local server with: 
{% highlight bash %}
bundle exec jekyll serve
{% endhighlight %}

The default behaviour is to watch for changes: We do not need the following.
When you save a file, the site gets generated automatically.  Not you still have to refresh the browser.


Not sure why you have have the seperate watch now.
Start a new terminal tab and run the command, this will auto generate whne you change your site
{% highlight bash %}
jekyll build --watch
{% endhighlight %}


Do not follow instructions in the Genfile to use github_pages.
The site works without the changes.  I had issues when trying to following the recommendations in teh Gemfile.
{% highlight ruby %}
# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins
{% endhighlight %}


[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
