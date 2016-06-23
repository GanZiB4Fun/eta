# eta
注意事项

1、本包是完整的全新安装包，需要重新安装
2、此包版本为WeiPHP3.0_20160531_2005版
3、由于微场景文件包太大，且原始代码由热心开发者提供，版权不明，因此WeiPHP3.0不会在安装包里提供，需要的用户可以在我们的社区论坛里下载


本次更新日志：

一、功能增加部分
1、核心扩展库增加QQ表情支持
2、修改ThinkPHP核心Redis缓存文件，增加授权功能，以支持阿里云等云平台的Redis数据库
3、系统模型功能增加动态多选菜单功能，即多选里的选项可以系统自己动态从数据库里获取，不需要人工提交配置
4、系统模型功能增加素材选择器功能，在插件开发过程如果需要选择素材，不再需要再自己开发选择的功能
5、系统模型功能增加奖品选择器功能，在插件开发过程如果需要选择奖品库里的奖品，不再需要再自己开发选择的功能
6、系统增加缩略图截图功能
7、系统上传图片功能，百度编辑器上传图片功能增加常用图标功能，极大方便了用户的运营工作，同时很方便地支持用户自己上传更多的图标，以适应各行各业的需求
8、自定义页面增加多商品滑动，多图滑动功能
9、级联菜单插件增加“请选择”选项，解决默认值不正确的问题
10、用户分组增加直接从分组查看用户的功能
11、解决用户组同步到微信异常的问题

二、问题修改部分：
1、微信支付去掉中间的重复提示页面，减少支付流程，直接进入支付
2、修改ThinkPHP核心的数据库驱动文件，规避了用户用in条件时如果数据为空时系统直接报SQL严重错误的问题
3、修复在未选择公众号时系统显示的标题不正常的问题
4、修复用户分享带有openid的H5页面给别人时别人获取openid异常的问题
5、由于微信授权域名不支持泛域名，因此全部去掉weiphp3.0beta版块里的泛域名功能
6、解决在公众号配置页面无法退出的问题
7、解决上传文件时配置参数丢失的问题
8、更新核心T函数在二级目录情况下插件模板里的include标签异常的问题
9、解决通用的导出模型数据的问题

更多更新日志请查看这里：

http://bbs.weiphp.cn/thread-4043-1-1.html
