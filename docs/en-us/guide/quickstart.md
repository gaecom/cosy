在IntelliJ IDEA中安装阿里云智能编码插件（Alibaba Cloud AI Coding Assistant）后，你可以在本地编辑器内享受代码智能补全、代码示例搜索等功能。

# 准备工作

- 下载并安装JDK1.8或更高版本
- 下载并安装IntelliJ IDEA（2020.1或更高版本）

# 安装插件

当前阿里云智能编码插件已经发布**公测**版本，你可以通过插件市场或离线包完成安装。

<!-- tabs:start -->

#### **插件市场安装（推荐）**

1. 在IntelliJ IDEA顶部菜单栏中选择**IntelliJ IDEA** > **Preferences**。
2. 在**Preferences**对话框的左侧导航栏中单击**Plugins**。
3. 在**Plugins**区域单击**Marketplace**。
4. 在搜索栏中输入 ***Alibaba Cloud AI Coding Assistant*** 或 ***cosy***
5. **Search Results**区域会出现 ***Alibaba Cloud AI Coding Assistant*** ，单击**Install**。
6. 等待下载、安装完成后，单击**Restart IDE**。
![image](../../media/plugin_marketplace.jpg)

#### **离线包安装**

1. 复制链接 http://toolkit.aliyun.com/idea/cosy-intellij-beta-latest.zip 至新窗口页即可下载，或通过[Github Release](https://github.com/alibaba-cloud-toolkit/cosy/releases/)下载。
2. 在IntelliJ IDEA顶部菜单栏中选择**IntelliJ IDEA** > **Preferences**。
3. 在**Preferences**对话框的左侧导航栏中单击**Plugins**。
4. 在**Plugins**区域单击**Settings Icon**，再单击**Install Plugin from Disk...**。
5. 在**Choose Plugin File**对话框中选择步骤1中下载的cosy-intellij-0.9.5-beta.zip，安装完成后，单击**Restart IDE**。
![image](../../media/local_install.png)

<!-- tabs:end -->

## 验证结果

IntelliJ IDEA重启后，右侧边栏有【代码示例搜索】Tab，或者代码编辑过程中出现来自Alibaba Cloud AI Coding Assistant即右侧有"Cosy"标识的的补全项，则说明安装成功。

# 功能体验

## 代码智能补全

[代码智能补全使用帮助](zh-cn/guide/how-to-use-completion.md)

## 代码示例搜索

[代码示例搜索使用帮助](zh-cn/guide/how-to-use-codesearch.md)

# 联系我们

如果在使用阿里云智能编程插件时遇到问题或有任何建议，欢迎在[Issues](https://github.com/alibaba-cloud-toolkit/cosy/issues)中向我们反馈！
