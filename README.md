# GitHubWidgets
GitHub html widget, include User Widget and Repo Widget.

![repo](https://github.com/smuyyh/GitHubWidgets/blob/master/screenshot/github_user_1.png?raw=true)
![repo](https://github.com/smuyyh/GitHubWidgets/blob/master/screenshot/github_repo_1.png?raw=true)

## How to use
- User Widget

Copy and paste this code in your HTML body, replacing “data-username” with your GitHub username
```xml
<div class="github-widget" data-username="smuyyh"></div>
<script src="../js/github_user_widget_en.js"></script>
```
- Repo Widget

Copy and paste this code in your HTML body, replacing “data-repo” with your GitHub username/reponame
```xml
<script type="text/javascript" src="../js/jquery-1.7.1.min.js"></script>
<script type="text/javascript" src="../js/github_repo_widget_en.js"></script>
<div class="github-widget-repo" data-repo="smuyyh/SprintNBA" style="width:500px"></div>
```

## 为博客添加GitHub挂件（以CSDN博客为例）
管理博客 -> 博客栏目 -> 添加栏目
```xml
<div class="github-widget" data-username="smuyyh"></div>
<script type="text/javascript" src="https://rawgit.com/smuyyh/GitHubWidgets/master/js/github_user_widget_en.js"></script>

<!--js文件真实地址是以raw.githubusercontent.com开头，raw.githubusercontent.com在Response中设置了X-Content-Type-Options:nosniff ，浏览器强制检查资源的MIME。解决方法就是将js链接中的raw.githubusercontent.com换成rawgit.com。  -->
```
![csdn](https://github.com/smuyyh/GitHubWidgets/blob/master/screenshot/csdn_widget.png?raw=true)
