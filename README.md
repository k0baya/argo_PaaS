## 源仓库：[Argo-X-Container-PaaS](https://github.com/fscarmen2/Argo-X-Container-PaaS)
>这里仅保留了源仓库中最简单常用的部分变量方便我个人查阅使用。

## PaaS 平台用到的变量:

* PaaS 平台设置的环境变量
  | 变量名        | 是否必须 | 默认值 | 备注 |
  | ------------ | ------ | ------ | ------ |
  | UUID         | 否 | de04add9-5c68-8bab-950c-08cd5320df18 | 可在线生成 https://www.uuidgenerator.net/ |
  | WEB_USERNAME | 否 | admin  | 网页和 webssh 的用户名 |
  | WEB_PASSWORD | 否 | password | 网页和 webssh 的密码 |
  | PORT         | 否 | 3000 | 在某些平台（如Koyeb）使用时需标注端口（不可更改为3000以外的值） |
  
* 路径（path）
  | 命令 | 说明 |
  | ---- |------ |
  | <URL>/list | 查看节点数据 |
  | <URL>/status | 查看后台进程 |
  | <URL>/listen | 查看后台监听端口 |
  | <URL>/test  | 测试是否为只读系统 |  
