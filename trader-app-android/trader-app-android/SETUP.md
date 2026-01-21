# 快速上传到 GitHub 并自动生成 APK

## 步骤 1：创建 GitHub 仓库
1. 访问 https://github.com/new
2. 仓库名称：`trader-viz-app`
3. 选择 **Public**
4. 不勾选 "Initialize this repository"
5. 点击 **Create repository**

## 步骤 2：上传项目（在命令行执行）
```
cd trader-app-android
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/w59733/trader-viz-app.git
git push -u origin main
```

## 步骤 3：等待自动构建
1. 访问 https://github.com/w59733/trader-viz-app
2. 点击 **Actions** 标签页
3. 等待构建完成（15-20分钟）

## 步骤 4：下载 APK
1. 点击最新构建任务
2. 找 **Artifacts** 中的 **app-release**
3. 点击下载 APK 文件

## 步骤 5：安装到手机
1. 将 APK 发送到手机
2. 打开文件管理器，点击 APK
3. 点击安装
