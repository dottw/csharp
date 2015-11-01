#取得程式執行的當前路徑#

##Console Application##
```CSharp
string path = System.AppDomain.CurrentDomain.BaseDirectory;
```
##WPF##
```CSharp
string path = System.AppDomain.CurrentDomain.BaseDirectory;
```

##Windows Form##
```CSharp
string path = System.Windows.Forms.Application.StartupPath;
//or
string path = System.AppDomain.CurrentDomain.BaseDirectory;
```


除此之外, C# 還有提供許多方法可以取得執行程式路徑


##References##
+ [MSDN - Application.StartupPath 屬性 ](https://msdn.microsoft.com/zh-tw/library/system.windows.forms.application.startuppath%28v=vs.110%29.aspx)
+ [MSDN - AppDomain.BaseDirectory 屬性](https://msdn.microsoft.com/zh-tw/library/system.appdomain.basedirectory%28v=vs.110%29.aspx)
+ [stack overflow - Best way to get application folder path](http://stackoverflow.com/questions/6041332/best-way-to-get-application-folder-path)
