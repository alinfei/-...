相关资源

开发群：QQ（452137839）

开发工具 v0.7

百度: https://pan.baidu.com/s/1pLTKIqJ （密码: iswg）
360: https://yunpan.cn/ckvTYFHWzYYFV （提取码：e09b）
开发工具 v0.9

百度: https://pan.baidu.com/s/1pLTKIqJ （密码: iswg）
360: https://yunpan.cn/ckvXjEbnFYMSC （提取码：f9ca）
Demo源代码

百度: https://pan.baidu.com/s/1o8hJFuU （密码: bsky）
360: https://yunpan.cn/ckvXAacJjvsgR （提取码：3327）
破解步骤

Mac测试可用，Windows测试可用

下载开发工具，并安装（注意：一定要安装0.9版本）
打开『微信Web开发者工具』的程序目录
Windows：使用资源管理器查看
Mac：右键点击图标，选择『显示包内容』
进入程序目录后，替换以下文件（只需要替换0.9版本里的，0.7版本用来登陆）：

Windows：
\package.nw\app\dist\components\create\createstep.js
\package.nw\app\dist\stroes\projectStores.js
Mac：
/Resources/app.nw/app/dist/components/create/createstep.js
/Resources/app.nw/app/dist/stroes/projectStores.js
注意，这里微信工程师拼写错了，是stroes没错！！！

替换的文件点击这里下载

Good luck

扫码无法登录问题 please bind your wechat account to the appid first

先使用0.7版本[Windows|Mac]的进行扫码登陆
登陆成功后，再用0.9版本打开就直接进入了
使用教程

运行『微信Web开发者工具』
通过微信扫描二维码
创建项目
AppID：随便填
项目名称：随便填
本地开发目录：选择一个目录
点击「添加项目」
此时如果出错，先退出再重进
此时，能够看到项目列表了
打开项目
开始开发
Good luck
常见问题

找不到所要替换的文件
问题原因：开发工具版本不正确，老版本不支持
解决方案：确保下载的程序版本在0.9.092100以上
Failed to load resource: net::ERR_NAME_NOT_RESOLVED http://1709827360.appservice.open.weixin.qq.com/appservice
问题原因：通常是由于系统设置了代理如Shadowsocks等。
解决方案：关闭代理，或者依次点击工具栏“动作”-"设置"，选择“不使用任何代理，勾选后直连网络”。
修复asdebug.js报错
问题原因：TypeError: Cannot read property 'MaxRequestConcurrent' of undefined
解决方案：替换 /Resources/app.nw/app/dist/weapp/appservice/asdebug.js
扫码登录失败
问题原因：please bind your wechat account to the appid first
解决方案：先使用0.7版本的进行扫码登陆，登陆成功后，再用0.9的版本打开就直接进入了。
0.7版本地址：http://dldir1.qq.com/WechatWebDev/release/0.7.0/wechat_web_devtools_0.7.0.dmg
工具截图


相关链接
