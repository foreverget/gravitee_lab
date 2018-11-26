# 开发环境搭建

## 一、安装golang

### 安装

Golang语言安装包下载1[国内](https://www.golangtc.com/download) 下载2[官方国外](https://golang.org/dl/)，本地安装

### 校验和环境设置

```
go version
go env
```
确保**GOROOT**(go语言安装目录)和**GOPATH**(go语言工作区)设置正确，建议Windows环境变量设置中定制自己的**GOPATH**。

## 二、安装vscode

### 安装

下载[Visual Studio Code](https://code.visualstudio.com/)，本地安装

### 安装go语言扩展

打开vscode，选中扩展(ESTENSIONS)面板，搜索Go语言扩展(Microsoft)，根据提示安装即可。

**注意**，Go语言扩展完整安装需要拉取一些go语言扩展工具，请尽量保证网络畅通，这些工具如果安装不成功，不会影响go语言代码的浏览和编辑，但是会影响一些高级功能，比如代码导航，自动导入和调试等。如果因网络问题无法正常拉取go语言扩展工具，请参考[附录]或自行百度一下。

## 三、Hello World!

在%GPATH%\src`中编写你的Hello World!程序hello.go

```go
package main

import "fmt"

func main() {

  fmt.println("Hello World!")

}
```

当前目录，打开命令窗口，输入`go run hello.go`，输出：

```
Hello World!
```

尝试在vscode中打断点进行调试，验证vscode和golang扩展安装正确。

## 附录

[VSCode安装go语言开发环境，go插件问题解决](https://blog.csdn.net/Yo_oYgo/article/details/79065966)












