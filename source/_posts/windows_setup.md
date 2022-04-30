---
layout: post
title:  windows下的环境安装
date:   2022-04-29 16:49:08
categories:
  - 系统
---

本文针对个人MAC下的虚拟机win7_64旗舰版

* 运行win7激活工具
* 安装[VIM](https://www.vim.org/download.php#pc)，并配置好;
* 安装mtux，并配置好；
* 安装[git](https://git-scm.com/download/win)/[git GUI](https://tortoisegit.org/download/)及汉化包，并配置好git;
* 为便于`git clone git@github.com:xxx/yyy`时无需密码验证, 进行[github下的ssh](https://www.jianshu.com/p/9317a927e844)配置

# V1
用于STC下的开发工作，建议安装最新v5版本
* 执行MDKxxx.exe安装IDE,缺省安装了ARM;
* 手动安装c51，期间出现的所有提示都选skip;
* 运行注册机
```shell
1. 右键以管理员身份打开IDE的桌面快捷方式;
2. 打开“File”的“License Management”，拷贝其CID编号;
3. 打开注册机keygen，粘贴CID编号;
4. target”选择arm，点击“Generate”，复制结果到“License Management”中，点“Add Lic”，激活ARM
5. 同样操作激活C51.
```

* 安装烧录工具(stc-isp-15xx-v6.86S)

# 附录
* windows下的包管理工具：[scoop](https://sspai.com/post/52496)、[baulk](https://github.com/baulk/baulk)
* everything
* autohotkey
* Total Commander
* sscom支持串口/网口通信，注意串口通信时可选设置RTS/DTR
