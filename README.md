# hublix_backend

随意影视后端

## 部署流程

1. 安装mariadb10.3版本
2. 导入[sql文件](https://github.com/typenoob/hublix_backend/blob/master/dump-hublix-202206142121.sql)
3. 更改[数据库url](https://github.com/typenoob/hublix_backend/blob/master/config/config.default.js#L40-L52)
4. 在[邮件服务配置](https://github.com/typenoob/hublix_backend/blob/master/app/controller/email.js#L11-L22)中填入相关信息
5. 执行命令`npm install`
6. 执行命令`npm start`

## 推荐方案

- heroku容器+JawsDB Maria免费部署。 