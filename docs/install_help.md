# 一、无法双击打开APPX

## 使用 应用安装程序 安装

确定系统已经安装了《应用安装程序》
![2021-01-10_5ffb1e6065690.png](https://vip1.loli.io/2022/03/15/KHv1ZUWF47A6Xzt.png)

如果没有安装，到这里安装：

https://www.microsoft.com/zh-cn/p/%e5%ba%94%e7%94%a8%e5%ae%89%e8%a3%85%e7%a8%8b%e5%ba%8f/9nblggh4nns1

安装完成后，右键APPX文件-打开方式，选择 应用安装程序 打开 即可

![2021-01-10_5ffb1f38cc24d.png](https://vip2.loli.io/2022/03/15/1xg7cJU8avlMq6n.png)

## 使用PowerShell安装
以管理员身份运行PowerShell

![2021-01-10_5ffb21c936d10.png](https://vip2.loli.io/2022/03/15/EWsYhcS3IJBMzwZ.png)

输入

`Add-AppxPackage -Path `

将APPX文件拖入到PowerShell窗口

![2021-01-10_5ffb2222252d4.png](https://vip2.loli.io/2022/03/15/SvepZjrchg5kwUW.png)

回车运行
