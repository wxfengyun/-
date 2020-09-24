# 日常编程记录 Today I Learned
> 我每天学了点啥 Today I Learned
随手记录每天学习的点滴编程技术，备查使用，也希望能给需要的人带来帮助。
文章都是一些碎片化的记录，不是完整的博客。  

A collection of concise write-ups on small things I learn day to day across a
variety of languages and technologies. These are things that don't really
warrant a full blog post.

当前一共<font color=red>12</font>条记录 持续更新中...

---
### 目录 Categories
* [Apache](#apache)
* [Css](#css)
* [Javascript](#javascript)
* [Mysql](#mysql)
* [Python](#python)
* [Shell](#shell)
* [Tcpdump](#tcpdump)

---
### Apache

- [apache日志记录POST的详细数据](apache/apache日志记录POST的详细数据.md)
- [apache默认日志加入耗时统计](apache/apache默认日志格式加入耗时统计.md)

### Css

- [创建一个带输入框的下拉列表控件](css/创建一个带输入框的下拉列表控件.md)

### Javascript

- [使用jQuery向服务器post表单数据](javascript/使用jQuery向服务器post表单数据.md)

### Mysql

- [mysql查看最大连接数的配置](mysql/mysql查看最大连接数的配置.md)

### Python

- [python时间日期的转化和加减计算](python/python时间日期的转化和加减计算.md)
- [python解析xml文件](python/python解析xml文件.md)
- [将python源代码编译成elf文件](python/将python源代码编译成elf文件.md)

### Shell

- [grep搜索多层目录下指定后缀的文件内容](shell/grep搜索多层目录下指定后缀的文件内容.md)
- [python解析xml文件](shell/ls按文件大小或者时间排序.md)
- [查询磁盘类型和inode使用量](shell/查询磁盘类型和inode使用量.md)

### Tcpdump

- [使用tcpdump生成post上传文件pcap包](tcpdump/使用tcpdump生成post上传文件pcap包.md)

## 自动生成README的方法 Usage
在根目录下执行 `python createReadme.py` 可以自动根据目录结构生成README.md  

After creating a new entry, run `./createReadme.py > README.md` to regenerate
the readme with the new data.
If you are using git, you can install this script as a pre-commit git hook so
that it is autogenerated on each commit.  Use the following command:
    cd .git/hooks/ && ln -s ../../createReadme.py pre-commit && cd -
## 关于 About
此想法的最初来源[jbranchaud/til](https://github.com/jbranchaud/til)  

I shamelessly stole this idea from
[jbranchaud/til](https://github.com/jbranchaud/til) who claims to have stolen
it from others.
## 其他每日记录 Other TIL Collections
* [jbranchaud/til](https://github.com/jbranchaud/til) who claims to have stolen
* [Today I Learned by Hashrocket](https://til.hashrocket.com)
* [jwworth/til](https://github.com/jwworth/til)
* [thoughtbot/til](https://github.com/thoughtbot/til)
* [jima80525/til](https://github.com/jima80525/til)
## 版权信息 License
&copy; 2017-2020 Jim Anderson & 小黄鸡
This repository is licensed under the MIT license. See `LICENSE` for
details.