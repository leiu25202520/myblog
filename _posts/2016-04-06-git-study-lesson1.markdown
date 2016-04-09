---
layout: post
title:  "git 基本配置和使用!"
date:   2016-04-06 07:43:07 +0800
---
＃git命令
git remote add origin https://xxx.github.com/xxx

git add .

git commit -m 'first commit'

git branch gh-pages

git checkout gh-pages

git push origin gh-pages



//git 基本使用
  sudo apt-get install git
  git init
  ls -a
  git status
  git add README
  git commit -m "1st"
  git config --global user.name "Peter Wang"
  git config --global user.email "happypeter1983@gmail.com"
  git log
  git log -p
  sudo apt-get install tig
  git commit -a
  git diff
  git config --global core.editor vim
  git commit -a -v
  git config --global alias.ci "commit -a -v"

{% highlight ruby %}
git init
ls -a
git status
{% endhighlight %}

{% highlight ruby %}
git add README
git commit -m "1st"
git config --global user.name "Peter Wang"
git config --global user.email "happypeter1983@gmail.com"
git log
git log -p
{% endhighlight %}

{% highlight ruby %}
git commit -a
git diff
git config --global core.editor vim
git commit -a -v
git config --global alias.ci "commit -a -v"
{% endhighlight %}

Check out the [git 基本配置][git basic]

[git basic]: http://haoduoshipin.com/v/4
