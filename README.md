# SolutionMiningMachine

由于最近普遍出现了MAC电脑被ssl.plist或者ssl3.plist绑架当作矿机挖门罗币的情况，每天都会有人加我让我帮忙远程解决下。所以，我研究了下，写了两个进程，只需要按我的步骤操作，你的电脑就会恢复如初。

1.重启电脑，在重启的过程中按住comond+R，进入安全模式，并在安全模式下打开终端。
![我是图片](https://wx1.sinaimg.cn/mw1024/006pTt9Mly1g6f6u545hkj31400u0wgv.jpg)

2.在终端下输入，csrutil disable，解除保护。如果不解除保护的话，会造成某些文件无法访问，导致矿机程序无法彻底删除。
![我是图片](https://wx1.sinaimg.cn/mw1024/006pTt9Mly1g6f6u545hkj31400u0wgv.jpg)

3.重启电脑，什么也不按，进入界面。并且运行git上下载的test3和test4。一个一个的运行，运行完成以后，重启即可恢复。

4.如需恢复文件保护的话，重启电脑，在重启的过程中按住comond+R，进入安全模式，并在安全模式下打开终端。

5.在终端下输入，csrutil enable，恢复保护。然后重启电脑即可。
