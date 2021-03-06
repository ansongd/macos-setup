# Oh My Zsh安装配置

MacOS已默认安装zsh命令工具，如果想获得更多的命令补全、终端主题方案等，可安装Oh My Zsh得到更强大的终端支持

* ### 打开终端窗口, 粘贴以下脚本

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

* ### 配置Oh My Zsh

终端完成安装后，在没设置主题情况下，终端可能变得更奇异，这时候只需要修改Oh My Zsh的配置文档就能获得更强大的终端样式支持。

#### 编辑配置文档

```
vi ~/.zshrc
```

找到ZSH\_THEME=“”，这里可以设置Oh My Zsh的主题样式，[点此链接](https://github.com/robbyrussell/oh-my-zsh/wiki/External-themes) 可获得更多主题样式支持。

建议把默认配置文件修改成以下两部分

```
ZSH_THEME=“ys“
plugins=(git colored-man colorize github jira vagrant virtualenv pip python brew osx zsh-syntax-highlighting)
```



