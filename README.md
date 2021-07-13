# Windows-Display-Optimization_Chinese-font-modification

Macty配置文件
[General]
Name=ADaQianZiBi
HintingMode=1
AntiAliasMode=2
NormalWeight=16
BoldWeight=2
ItalicSlant=0
EnableKerning=0
GammaMode=0
LcdFilter=2
BolderMode=0
TextTuning=0
TextTuningR=0
TextTuningG=0
TextTuningB=0
GammaValue=1.4
Contrast=1.0
RenderWeight=1.0
Fontlink=2
HookChildProcesses=1
FontLoader=0
FontSubstitutes=1
Shadow=0,0,60,0x0,30,0x0
MaxBitmap=0
CacheMaxFaces=256
CacheMaxSizes=12554432
CacheMaxBytes=12108864
[Preview]
Font=ADaQianZiBi
Color=$3300CC
Text=ADaQianZiBi by：632079    推荐Chrome使用
Size=10
Align=Left

[ExcludeModule]
;【不渲染的程序，但仍会加载DLL】




[UnloadDll]
[exclude]
[FontSubstitutes]
Fixedsys=ADaQianZiBi
SimSun=ADaQianZiBi
@SimSun=@ADaQianZiBi
NSimSun=ADaQianZiBi
@NSimSun=@ADaQianZiBi
新宋体=ADaQianZiBi
@新宋体=@ADaQianZiBi
SimHei=ADaQianZiBi
@SimHei=@ADaQianZiBi
黑体=ADaQianZiBi
@黑体=@ADaQianZiBi
Segoe UI=ADaQianZiBi
Tahoma=ADaQianZiBi
Microsoft YaHei=ADaQianZiBi
@Microsoft YaHei=@ADaQianZiBi
微软雅黑=ADaQianZiBi
@微软雅黑=@ADaQianZiBi
Microsoft YaHei UI=ADaQianZiBi
@Microsoft YaHei UI=ADaQianZiBi
微软雅黑 UI=ADaQianZiBi
@微软雅黑 UI=@ADaQianZiBi
MS Shell Dlg=ADaQianZiBi
MS Shell Dlg 2=ADaQianZiBi
Microsoft Sans Serif=ADaQianZiBi
仿宋=ADaQianZiBi
@仿宋=ADaQianZiBi
宋体=ADaQianZiBi
@宋体=@ADaQianZiBi
@SimSun-ExtB=@ADaQianZiBi
SimSun-ExtB=ADaQianZiBi
@黑体-简=@ADaQianZiBi
黑体-简=ADaQianZiBi
Segoe UI=ADaQianZiBi
Segoe UI Light=ADaQianZiBi
Segoe UI Semibold=ADaQianZiBi
Segoe UI Symbol=ADaQianZiBi
Segoe Print=ADaQianZiBi
Segoe Script=ADaQianZiBi
黑体=ADaQianZiBi
隶书=ADaQianZiBi
华文宋体=ADaQianZiBi
华文仿宋=ADaQianZiBi
华文中宋=ADaQianZiBi
仿宋=ADaQianZiBi
幼圆=ADaQianZiBi
@幼圆=ADaQianZiBi
@仿宋=ADaQianZiBi
@华文中宋=ADaQianZiBi
@华文仿宋=ADaQianZiBi
@华文宋体=ADaQianZiBi
@黑体=ADaQianZiBi
@隶书=ADaQianZiBi



[Individual]
[excludeSub]
;【不渲染的程序，同时完全不加载DLL】
ChatHall.exe
CorelDRW.exe
et.exe
EXCEL.EXE
Fetion.exe
fontview.exe
guagua.exe
kugoo.exe
POWERPNT.EXE
WINWORD.EXE
wpp.exe
wps.exe
XLDoctorUI.exe
e.exe
Photoshop.exe
i4Tools.exe
notepad++.exe



---------------------
 
 


使用Macytpe警告：我自己使用的是注册表加载，你们可以自己选择。如果使用注册表加载，请让自己电脑有PE系统或者自己有U盘PE系统，否则万一发生无法开机情况，没法救！安全模式都进不去！


软件下载走一波：
我自己使用的字体是： 筑紫A丸コ&#12441;シック By 宁静之雨     
配置跟修改好的字体下载：链接: https://pan.baidu.com/s/1nf1HbX7inGlkbP9yXsUWvg 密码: fnj9
Mactype软件下载： 官网：http://www.mactype.net/  网盘：链接: https://pan.baidu.com/s/1MzgVbf6mM7dm2WQ8pZGJUQ 密码: 1wy8
noMeiryoUI232下载：链接: https://pan.baidu.com/s/18z0hbRerKYRgujElae-leQ 密码: mx4v
这个软件修改桌面上的字体啥的可以！win10推荐！
FontCreator软件下载：链接: https://pan.baidu.com/s/1OWt7ggdKvVSoLsFk8c11eQ 密码: fscq


二：使用FontCreator修改字体系统识别为中文简体
当你下载一个TTF字体时候，如果电脑识别是这样的，   ，使用Mactype渲染就会有些问题。现在让大家自己修改字体增加简体中文支持！

1.使用FontCreator打开你需要修改的字体。
 
2.点击FontCreator菜单栏上的  “格式”→“设置”→范围，点击“代码页字符范围” 下面的编辑。勾选 “中文：简体-中国 与 新加坡（936）”
 
 
3.一直确认，为了防止文件损坏，建议另存为。修改完成后如下。
 

至此修改字体成功。安装后将配置文件复制一份，然后将配置文件中的 字体文件名替换成你自己修改好的字体文件名，再去Mactype中启用即可！

三。浏览器使用插件强制渲染
渲染效果图如下：
   

实现方法如下：我这里用的360极速浏览器
选项，高级设置中 选择字体为你们自己想使用的字体，实验室中关闭 “开启DirectWrite高清字体渲染支持”，如下图
   
这里已经实习一半了，但是还是有些网页么有显示你自己喜欢的字体，这里就要用到“雅酷字体修正 1.0”这个浏览器扩展插件了。
360急速浏览器中扩展中心中搜索即可下载。如下图
 
安装完成后，进入扩展修改字体为你想要的字体名即可。如图
 
我这是修改好了的，你们点击会显示字体列表的.
OK，就这样了~


