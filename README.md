# blockmesh_boot
blockmesh_boot
使用教程
脚本是用python语言写的，使用这个脚本你起码要有会运行python的基础

脚本不开源，请勿尝试破解。如有害怕数据被盗，请不要使用！

key申请地址：https://lumao.us.kg/blockmesh/index.php

blockmesh注册：https://app.blockmesh.xyz/register?invite_code=472117a5-b80c-4597-a373-703b7df83589

视频教程
youtube地址：https://youtu.be/kRtGGPUn5Ic

===教程开始===
## 1、安装virtualenv，virtualenv 是一个用于创建隔离 Python 环境的工具，它的主要作用是让你在项目中使用独立的 Python 依赖，而不会影响到系统或其他项目。具体来说，virtualenv 有以下几个重要作用：隔离项目依赖，保护全局环境，方便迁移和部署，多版本 Python 管理
```bash
pip install virtualenv

mkdir myenv

virtualenv myenv
```
linux/mac激活
```bash
source myenv/bin/activate
```
windows激活
```bash
myenv\Scripts\activate
```
## 2、安装脚本需要用到组件
```
pip install aiohttp json5 requests -i https://pypi.tuna.tsinghua.edu.cn/simple/
```
## 3、修改accounts.json的数据
详细看视频操作，懒得打字了！

## 4、运行脚本
pyhon 你的脚本名称

## 5、查看运行日志
出现下面的文字，说明你运行成功了：
```log
你的IP: 1.1.1.1，所在国家: China，所在地区: Shanghai 所在国家: China，Shanghai，1111@gmail.com的blockmesh的总积分: 12398.0
```
