# 命令行版本注入工具使用方法
1. 终端进入本文件夹
2. 执行 sudo ruby main.rb 启动注入程序。

# App兼容性
### 支持以下App的M系和Intel版本：
1. iShot 2.3.4
2. Infuse Pro 通杀
3. Parallels Desktop 18.3.1
4. Surge Pro 5.1.1 2264
5. CleanMyMac X 4.13.4 
6. MWEB Pro 通杀
7. App Cleaner & Uninstaller 8.2 已支持macOS 14
8. 解优2 1.6.1 通杀
9. Adobe PhotoShop 24.5 
10. Adobe Acrobat 23.003.20201

### 仅支持Intel版本: 因为官方没有做M系处理器适配
1. Navicat Premium 应用商店版通杀
2. Office Word/PowerPoint/Excel 16.73 应用商店365订阅版
3. Adobe Illustrator 27.5.0
4. Adobe PhotoShop Beta 24.7 支持创意填充 需要随便登录个账户

### 提示：
1. 会自动扫描本地安装的App，你只需要在想注入的App后面输入y即可。
2. Adobe App如果不想让官方ACC乱拉屎，可以用这个仓库下载v6版本的离线安装包: https://github.com/Drovosek01/adobe-packager, 然后配合AntiCC之类的组件运行Adobe产品。

### 警告
一定要关闭SIP，因为我使用的注入方式依赖于关闭SIP。
