# -luffy-life
***
# 程序入口文件
/atm-mall/main.py
# 目录结构介绍
* conf
> 包含conf.py文件
> 新建用户的默认余额
> 新建用户的锁定状态 1为锁定 0为正常
> 未找到管理员配置文件时，设定一个默认的管理员账号
> 登录时允许错误次数
> 默认提现手续费新建用户的默认余额
* data
> 包含了存放数据的文件
> 用户数据
> 管理员数据
> 商品数据
* log
> 存放日志文件
> 也包含交易流水文件
* mods
> 内置了核心模块
> atm_mall    ATM + 购物车
> admin_page  管理员模块
> pwd_md5     对密码进行加密
