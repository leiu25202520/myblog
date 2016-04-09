＃git命令
git remote add origin https://xxx.github.com/xxx
git add .
git commit -m 'first commit'
git branch gh-pages
git checkout gh-pages
git push origin gh-pages


＃修改目录
修改 _posts/目录内容 头部内容  categories: jekyll test

＃只显示目录，不现实地址
修改 _config.yml
  Build settings
  permalink: pretty

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
