---
layout: post
title:  Logistics behind writing my data science posts
---
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> ruby.
{% endhighlight %}

{% highlight python %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> python.
{% endhighlight %}

{% highlight rusthon %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> rusthon.
{% endhighlight %}

{% highlight pycon %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> pycon.
{% endhighlight %}

Now a different notation:

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> ruby.
```

```python
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> python.
```

```rusthon
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> rusthon
```

```pycon
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=>pycon
```

```Shell
$ jupyter nbconvert --to html --template basic notebook.ipynb
```

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
