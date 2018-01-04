## 环境准备
通过抓包软件，抓包拿到微信的sesseion_id

将sesseion_id写入改分脚本，提交改分请求

##  具体的步骤：
```bash
$ npm init --y
$ npm install crypto-js request-promise

然后用文本编辑器打开hack.js，修改里面的score（分数）和session_id变量的值即可。

命令行运行node hack.js，出现2018! Happy new year! 就代表成功了。

```
