# Zeal-docset-CN
Zeal和Velocity中文docset文档导入工具.A tool that could import docsets file to Zeal and Velocity(Just like Dash for windows).

项目说明
===
Dash离线文档docsets文件整理,来源于weixiang的[Dash-dcsets-CN](https://github.com/weixiang/Dash-dcsets-CN).

由于Windows下常用的可使用Dash文档的软件Zeal和Velocity都无法兼容和直接离线导入同步,所以干脆在这里整理了一份.

最新更新
===
+ 将Zip文件使用tar cfz重新打包为.docset.tgz , 同时兼容 Velocity for windows和Zeal for windows(Zeal只能导入*.tgz ; Velocity只能导入*.docset.tgz且必须是tar的压缩包);

+ 对没有图标的包,添加了高清图标;

+ 添加xml文件,作为Zeal在线导入的Feed;

+ 修改info.plist清单中的名称(CN),修正Linux包中清单的格式错误导致的导入失败问题;

Feed订阅列表
===

+ [Git中文文档](https://github.com/quericy/Zeal-docset-CN/raw/master/Git-CN.xml)

+ [Laravel5中文文档](https://github.com/quericy/Zeal-docset-CN/raw/master/Laravel5-CN.xml)

+ [Linux中文文档](https://github.com/quericy/Zeal-docset-CN/raw/master/Linux-CN.xml)

+ [PHP中文文档](https://github.com/quericy/Zeal-docset-CN/raw/master/PHP-CN.xml)

+ [ThinkJS中文文档](https://github.com/quericy/Zeal-docset-CN/raw/master/ThinkJS-CN.xml)

+ [jQuery1.10.3中文文档](https://github.com/quericy/Zeal-docset-CN/raw/master/jQuery1.10.3-CN.xml)


导入方式
===

- Zeal(在线导入Feed,无需下载):
    + 打开Zeal,Tool->Docsets,点击Add feed
    
    + 复制上节[Feed订阅列表](#Feed订阅列表)里需要导入的链接
    
    + 等待导入完成(可能需要扶墙,Zeal选项中可设置代理)
    
    + Zeal无导入进度显示,部分较大的docsets,下载完成后可能会导入比较久,需要等待Installed列表中出现为止.(可观察磁盘读写使用率来判断是不是还在导入)

- Velocity(需要下载):
    +  Clone项目或将docsets文件夹中的压缩包下载到本地;
    
    + 打开Velocity,左上角菜单->Add/Download->XCode->Import;
    
    + 导入下载的.docset.tgz文件即可;

鸣谢
===
原项目地址:[https://github.com/weixiang/Dash-dcsets-CN](https://github.com/weixiang/Dash-dcsets-CN)


