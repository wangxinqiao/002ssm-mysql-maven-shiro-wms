# 002ssm+mysql+maven+shiro进销存系统wms
002ssm+mysql+maven+shiro进销存系统wms


## 功能介绍

系统操作权限管理。系统提供基本的登入登出功能，同时系统包含两个角色：系统超级管理员和普通管理员，超级管理员具有最高的操作权限，而普通管理员仅具有最基本的操作权限，而且仅能操作自己被指派的仓库。
请求URL鉴权。对于系统使用者登陆后进行操作发送请求的URL，后台会根据当前用户的角色判断是否拥有请求该URL的权限。
基础数据信息管理。对包括：货物信息、供应商信息、客户信息、仓库信息在内的基础数据信息进行管理，提供的操作有：添加、删除、修改、条件查询、导出为Excel和到从Excel导入。
仓库管理员管理。对仓库管理员信息CRUD操作，或者为指定的仓库管理员指派所管理的仓库。上述中的仓库管理员可以以普通管理员身份登陆到系统。
库存信息管理。对库存信息的CRUD操作，导入导出操作，同时查询的时候可以根据仓库以及商品ID等信息进行多条件查询。
基本仓库事务操作。执行货物的入库与出库操作。
系统登陆日志查询。超级管理员可以查询某一用户在特定时间段内的系统登陆日志。
系统操作日志查询。超级管理员可以查询某一用户在特定时间段内对系统进行操作的操作记录

源码获取： [**点此获取** ](http://www.shuyue.fun/index.php?type=productinfo&id=94)

## 运行截图

![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/161534_2e37fbd1_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/161545_9b4b2737_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/161555_8794741b_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/161604_10621ca4_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/161612_a5c1398b_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/161620_4abdde64_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/161628_b4f95876_863230.png "屏幕截图.png")

