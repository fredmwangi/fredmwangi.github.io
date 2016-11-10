---
layout: post
title: Setup and Use Plugins in Vim on macOS
date: 2016-11-05
comments: true
tags: [Vim, macOS, command-line, plugins, OSX]
---
Install [Brew](http://brew.sh) if you do not have it.
{% highlight bash %}
usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
{% endhighlight %}

Install [Vim](http://www.vim.org) with Brew
{% highlight bash %}
brew install vim
{% endhighlight %}

Create the plugin directory under ~/.vim/
{% highlight bash %}
mkdir ~/.vim/plugin
{% endhighlight %}

Copy plugin file into that folder
{% highlight bash %}
cp location/of/plugin/foobar.vim ~/.vim/plugin/foobar.vim
{% endhighlight %}

Now you can use the plugin in Vim.
