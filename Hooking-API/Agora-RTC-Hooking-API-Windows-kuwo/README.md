# ARD-Agora-RTC-Hooking-API-Windows

The current demo is mainly written for heroes

With this sample Code you can:

- join/leave channel

- Listen to /play remote audio stream

- switch Native audio capture devices

- switch local audio player devices

- select local different audio player hook

##Running Environment

First of all ,you need to download the Dll of the Hook Module and place the relevant folder on the HookSDK, then download the media sdk ,put the sdk file on the AgoraSDK,and finally define the configuration file AgroaHook.ini

[BaseInfo]

AppId=

AppCertEnable=0

AppCertificateId=

ChannelName=baluoteliz

[AgoraHookInstance]

LoginUid=111


Alsl a conguration file DebugMode.ini. this is related to Hook Infomation positoning ,the default is automatically generated as follows

[DebugMode]

DebugMode=1

SaveDumpPcm=0


HookSDK will produce a log file PlayerHookV6_1.log in the ./AgoraHookLog directory during runtime. the current sdamplecode specifies that mediaSDKLog exists in the ./logger directory

##Development Environment

- visual studio 2013

- Window 7 or Higher

- mediaSDK 2.0.2

- https://pan.baidu.com/s/1BpfbSnuZxC9R2G3DiNW4Vw 下载 .h文件的

- sdks基于2.0.2

- 本地pc上需要安装directX ,vs2013 搭配 directx june.







     


