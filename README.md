# AndroidDetector🚀
AndroidDetector是一个在安卓系统上使用的基于yolov5s的目标检测器，它支持摄像头、图片和文件夹输入，并提供了精度和速度测试功能。

## 环境
以下是AndroidDetector开发所需的环境信息：
* Android Studio 4.2.1
* minSdkVersion 28
* targetSdkVersion 29
* Android设备：Snapdragon 778G

## 使用方法

### 摄像头输入
AndroidDetector支持通过摄像头进行目标检测。你可以按照以下步骤进行操作：

1. 在设备上安装并运行AndroidDetector应用。
2. 点击应用界面上的"使用摄像头"按钮。
3. 系统会打开设备的摄像头，并开始实时检测目标。
4. 当检测到目标时，应用会在界面上显示目标的位置和相关信息。

### 图片输入
AndroidDetector还支持通过图片进行目标检测。你可以按照以下步骤进行操作：

1. 在设备上安装并运行AndroidDetector应用。
2. 点击应用界面上的"选择图片"按钮。
3. 选择你想要进行目标检测的图片。
4. 系统会对所选图片进行目标检测，并在界面上显示目标的位置和相关信息。

### 文件夹输入
AndroidDetector还支持通过文件夹进行批量目标检测。你可以按照以下步骤进行操作：

1. 在设备上安装并运行AndroidDetector应用。
2. 点击应用界面上的"选择文件夹"按钮。
3. 选择包含需要进行目标检测的图片的文件夹。
4. 系统会批量对文件夹中的图片进行目标检测，并在界面上显示每张图片中目标的位置和相关信息。
5. 并且会在选择的该文件夹下生成result.json文件以供精度测试使用。

### 精度和速度测试
AndroidDetector提供了精度和速度测试功能，你可以按照以下步骤进行操作：

1. 在设备上安装并运行AndroidDetector应用。
2. 点击应用界面上的"进行测试"按钮。
3. 系统会自动进行速度测试，并在日志信息处显示测试结果。
4. 安装pycocotools，对文件夹输入生成的result.json文件进行精度测试。

## Error & Solution
| Error | Solution |
| ------------- | -------- |
| No variants found for ':app'| 更改tools版本:https://blog.csdn.net/chenhao0568/article/details/117754675 |
| Unsupported Java| 修改JDK版本:https://blog.csdn.net/hehota/article/details/130514341 |
## 界面
![zhujiemian](app/src/main/assets/mian.png)
