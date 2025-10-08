# 运行方法
## 本地运行
```shell
pip install -r requirements.txt
python xiaomi.py
```
## 在线执行
> 该项目已经配置了GitHub Action只需要fork仓库，然后在仓库中创建GitHub SecretGitHub Secret即可6
## 创建GitHub Secret
1. 进入你的GitHub仓库
2. 点击仓库顶部的"Settings"（设置）选项卡
3. 在左侧菜单中找到并点击"Secrets and variables" > "Actions"
4. 点击"New repository secret"按钮
5. 在"Name"字段中输入XIAOMI_ACCOUNTS
6. 在"Value"字段中输入JSON格式的账号信息：
   ```json
   [
    {
        "passToken": "xxxx",
        "userId": "xxxx"
    }
   ]
   ``` 
