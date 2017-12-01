## 准备：
1. 安装virtualenv:
`pip install virtualenv`

2. 创建虚拟环境:
`virtualenv venv`

3. 进入虚拟环境:
`venv\Scripts\activate`

4. 安装依赖的包:
`pip install -r requirements.txt`

## 运行：
1. 初始化数据库：`python app.py db init`

2. 迁移数据库：`python app.py db migrate`

3. 更新数据库：`python app.py db upgrade`

4. 生成管理员用户：`python app.py init`

5. 运行：`python app.py runserver`

## 初始管理员账户：
```
用户名：admin
密码：000000
```

## 浏览

http://127.0.0.1:5000