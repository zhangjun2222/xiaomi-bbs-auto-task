## 使用  
* 使用的第三方库
```
pip3 install requests_toolbelt
pip3 install requests
```

* 每日任务  
    * 每日五题(10分)和每日打开App(4分)  
    * 将账号密码填入`Daily\data\accounts.json`  
    * 在该项目目录下输入`python3 daily.py`即可运行  
        * 建议设置定时运行  
        * 若出现未收录题目将会随机选择, 并在之后自动收录题目的正确选项  
    * 青龙面板部署:
        * 将以下命令添加至`定时任务`并运行  

        ```
        ql repo https://github.com/azurstar/xiaomi-bbs-auto-task.git Daily/ql_panel
        ```

        * 立即执行一次`main.py`, 然后在`脚本管理`中找到`account.json`输入账密  
        * 在Python3的`依赖管理`中添加`requests_toolbelt`和`requests`  
        * 若账号在非常用设备上登录, 可能会需要验证码, 使用该设备自行前去验证 https://web-alpha.vip.miui.com/page/info/mio/mio/internalTest 

* 登录验证自己想办法, 不写了  
