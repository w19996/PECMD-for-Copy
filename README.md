# PECMD-for-Copy
根据文件列表提取文件

```
Windows\System32\drivers\fbwf.sys
Windows\System32\drivers\wimfsf.sys
Windows\System32\zh-CN\winpeshl.exe.mui
Windows\System32\zh-CN\drvload.exe.mui
Windows\System32\zh-CN\wpeutil.dll.mui
Windows\System32\drvload.exe
Windows\System32\schema.dat
\Windows\System32\winpeshl.exe
\Windows\System32\wpeinit.exe
\Windows\System32\wpeutil.dll
\Windows\System32\wpeutil.exe
\Windows\System32\abcd.*.*.exe
 ```
 文件列表中文件名称支持通配符，路径不支持通配符
 相对路径同级目录是指源文件中Windows的同级目录，例如Windows的绝对路径为D:\1\Windows，那么就选择D:\1\
运行本软件时需将软件放到目标目录，即如果你想把Windows\System32\wpeutil.dll复制到D:\2那么就把软件放到D:\2目录
