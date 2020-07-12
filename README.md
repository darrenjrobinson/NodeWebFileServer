# Node Web Local File Server
Small NodeJS Web File Server

## Requirements
Requires NodeJS

[Associated Blogpost](https://github.com/darrenjrobinson/UniversalDashboard.UDFinancialChart/tree/master/UniversalDashboard.UDFinancialChart)

## Syntax
node server.js <path_to_basefolder_to_share> port

Example 1
```
node server.js 'C:\SharedFiles' 10010 
```

Example 2 - Start-NodeWebFS.ps1 (Start Script)
```
# Start NodeJS Web File Server
clear
$port = 10010
$path = "$($env:USERPROFILE)"
cd $path
write-output "Starting NodeJS Web Server"
write-output "	File Server Path: $($path)"
write-output "	File Server Port: $($port)" 

& node server.js "$($env:USERPROFILE)\data" $port
```

## Links
![](https://wpcom.files.wordpress.com/2017/11/cropped-wordpress.png?w=16) [Blog](https://blog.darrenjrobinson.com)

![](http://twitter.com/favicon.ico) [Twitter](https://twitter.com/darrenjrobinson)
