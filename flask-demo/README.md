# flask简单的服务示例

## 运行环境
软件：python3、pip3
主要模块：flask、flask-restful、flask_script

## 启动方式
linux环境下：
进入flask-demo文件夹下（如：`cd flask-demo`）
设置环境变量：`export FASK_APP=app.py`
运行软件：`python3 -m flask run`

## 测试方式
*换一个终端测试，启动程序的终端保持不动。*
- 测试1：`curl http://localhost:5000/`(响应：Hello World!)
- 测试2：`curl http://localhost:5000/users`(响应：{"code":0,"data":"data","msg":"查询成功"})
- 测试3：`curl http://localhost:5000/users/a`(响应：{"code":0,"data":"data","msg":"成功查询到用户(a)的信息"})

*如果运行不了demo，可以先阅读[flask快速入门](https://flask.net.cn/quickstart.html#id2)*
