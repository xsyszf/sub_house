# sub_house

第一步：
//设置 登录名 登录密码 后端转换
    ADMIN_USERNAME: 'admin',           //面板ID
    ADMIN_PASSWORD: '123456',         //登录密码
    SUB_WORKER_URL: 'https://' , // 后端订阅地址（自建）
    SUBSCRIBER_URL: 'https://'//（优选订阅器，不影响主要功能，只是外链）


第二步：
设置KV 绑定，命名 NODE_STORE 

说明：后端可以转换内部含有订阅链接的集合，所以搭配后端订阅地址使用最佳
工作过程
1、收集每个节点信息和订阅信息
2、可以选择任意节点做组合
3、分享：是获得一个链接，包含所有的节点和订阅地址，可用于常规的订阅转换器
4、通用订阅：解析所有组合节点，包含订阅地址的节点，重新编码，获得最终的 通用订阅地址，可以用于小火煎等软件
