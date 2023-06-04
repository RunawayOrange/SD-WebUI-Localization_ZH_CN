# stable-diffusion-webui-localization-zh_CN
Simplified Chinese translation extension , Used for [AUTOMATIC1111's stable diffusion webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui)

## 简体中文(Simplified Chinese)
简体中文翻译扩展，适用于 [Stable Diffusion Webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui)

***推荐与 [Bilingual Localization](https://github.com/journey-ad/sd-webui-bilingual-localization) 共同使用***


## 如何安装webUI简体中文语言包

<details>
  <summary>新版本 webui 安装方法【点击展开】</summary>

  ### 1. 通过官方扩展列表安装
  此扩展可以在 **Extension** 选项卡里面通过加载官方插件列表直接安装
  - 点击 `Extension` 选项卡，点击 `Avaliable` 子选项卡
  - **取消勾选** `localization`，再把其他勾上，然后点击 **橙色按钮**，如下图
  ![image](https://user-images.githubusercontent.com/21131439/220507253-65b91219-05ac-4932-a129-0fcd1e55ffaa.png)

  - 在 `zh_CN Localization` 这一项的右边点击 `install`
  ![image](https://user-images.githubusercontent.com/21131439/220507520-77eab48a-272b-4a06-a38a-ca721181092f.png)
  - 安装完成，跳转到 [如何使用](#如何使用)

  ### 2. 或者，通过网址安装
  - 点击 `Extension` 选项卡，点击 `Install from URL` 子选项卡
  - 复制本 git 仓库网址：
  ```
  [https://github.com/StormyOrange/SD-WebUI-Localization_ZH_CN]
  ```
  - 粘贴进 URL 栏，点击 `Install`，如图
  ![image](https://user-images.githubusercontent.com/60730393/202898107-e207d645-e446-456c-8a5b-6dd400eba480.png)  
  - 安装完成，跳转到 [如何使用](#如何使用)

  ### 3. 又或者，直接下载然后放在对应路径
  - [下载本 git 仓库](https://codeload.github.com/dtlnor/stable-diffusion-webui-localization-zh_CN/zip/refs/heads/main)为 zip 档案
  ![image](https://user-images.githubusercontent.com/60730393/202898203-8f4265ff-efc1-4cb4-887a-86af291c000e.png)  

  - 解压，并把文件夹放置在 webui 根目录下的 `extensions` 文件夹中，放好之后应该会如下图
  ![image](https://user-images.githubusercontent.com/60730393/202898631-e4f6b3e2-b1d2-4258-b003-3142597fff3b.png)  
  - 安装完成，跳转到 [如何使用](#如何使用)

</details>

<details>
  <summary>2022年旧版本 webui 安装方法【点击展开】</summary>

  ### 1. 通过官方扩展列表安装【旧版】
  此扩展可以在 **extension** 选项卡里面通过加载官方插件列表直接安装
  - 点击 `extension` 选项卡，点击 `Avaliable` 子选项卡
  - **取消勾选** `localization`，然后点击 **橙色按钮**，如下图
  ![image](https://user-images.githubusercontent.com/60730393/202897956-484e2aaa-89db-4612-8e69-8d76458e23d0.png)  

  - 在 `zh_CN Localization` 这一项的右边点击 `install`
  ![image](https://user-images.githubusercontent.com/60730393/202897890-cd502e8d-dee0-48f8-835a-c3446cfb526c.png)
  - 安装完成，跳转到 [如何使用](#如何使用)

  ### 2. 或者，通过网址安装【旧版】
  - 点击 `extension` 选项卡，点击 `Install from URL` 子选项卡
  - 复制本 git 仓库网址：
  ```
  https://github.com/StormyOrange/SD-WebUI-Localization_ZH_CN
  ```
  - 粘贴进 URL 栏，点击 `Install`，如图
  ![image](https://user-images.githubusercontent.com/60730393/202898107-e207d645-e446-456c-8a5b-6dd400eba480.png)  
  - 安装完成，跳转到 [如何使用](#如何使用)

  ### 3. 又或者，直接下载然后放在对应路径【旧版】
  - [下载本 git 仓库](https://github.com/StormyOrange/SD-WebUI-Localization_ZH_CN/zip/refs/heads/main)为 zip 档案
  ![image](https://user-images.githubusercontent.com/60730393/202898203-8f4265ff-efc1-4cb4-887a-86af291c000e.png)  

  - 解压，并把文件夹放置在 webui 根目录下的 `extensions` 文件夹中，放好之后应该会如下图
  ![image](https://user-images.githubusercontent.com/60730393/202898631-e4f6b3e2-b1d2-4258-b003-3142597fff3b.png)  
  - 安装完成，跳转到 [如何使用](#如何使用)

</details>

## 如何使用

  > 2022 旧版 webui [点这里](#如何使用旧版)
  
  **确保扩展已经正确加载**  
  
  - 重启webUI以确保扩展已经加载了  
  
  - 在 `Settings` 选项卡，点击 **页面右上角**的 **橙色 `Reload UI` 按钮** 刷新扩展列表  
    ![image](https://user-images.githubusercontent.com/21131439/220509147-89b29802-2f9f-4db2-a21d-2dc99afa2d96.png)  

  - 在 `Extensions` 选项卡，确定已勾选本扩展☑️；如未勾选，勾选后点击**橙色按钮**启用本扩展。  
    ![image](https://user-images.githubusercontent.com/21131439/220509469-5c2af595-aece-4405-88f4-eb0638f8f22a.png)  

  **选择简体中文语言包（简体中文语言包_StormyOrange）**  
  
  - 在 `Settings` 选项卡中，找到 `User interface` 子选项  
    ![image](https://user-images.githubusercontent.com/21131439/220509760-b8680fcd-9673-47e3-ba47-2ae0baf41d51.png)  
  
  - 然后去页面最底部，找到 `Localization (requires restart)` 小项，找到在下拉选单中选中 `zh_CN` （如果没有就按一下🔄按钮），如图  
  ![image](https://user-images.githubusercontent.com/21131439/220510690-4445c0bc-b70b-4943-b69c-270faa7cffc1.png)  

  - 然后按一下 页面顶部左边的 **橙色 `Apply settings` 按钮** 保存设置，再按 右边的 **橙色 `Reload UI` 按钮** 重启webUI  
  ![image](https://user-images.githubusercontent.com/21131439/220510486-90a1cf87-345b-48a7-8286-26dc02c0634e.png)  

</details>

## 如何使用【旧版】

<details>
  <summary> 2022年旧版本 webui【点击展开】</summary>


  **重启webUI以启用扩展**
  - 在 `Settings` 选项卡，点击 **页面底部**的 **橙色按钮** 刷新扩展列表
  - 在 `Extensions` 选项卡，确定已勾选本扩展☑️；如未勾选，勾选后点击**橙色按钮**启用本扩展。  

  **选择简体中文语言包（简体中文语言包_StormyOrange）**  
  - 在 `Settings` 选项卡中，找到 `Localization (requires restart)` 小项，然后在下拉选单中选中 `简体中文语言包_StormyOrange` （如果没有就按一下🔄按钮），如图  
  ![image](https://user-images.githubusercontent.com/60730393/202900620-263cbdd3-0559-4b08-acd6-29570add8a3f.png)  

  - 然后按一下 页面顶部的  **橙色按钮** 保存设置，再按 页面底部的 **橙色按钮** 重启webUI  
  ![image](https://user-images.githubusercontent.com/60730393/202901412-26765c04-e69c-4beb-a56b-9e310ed273ca.png)  
  ![image](https://user-images.githubusercontent.com/60730393/202901401-de7d34e9-67c6-4f39-8f5f-b0c0c7a58b54.png)
