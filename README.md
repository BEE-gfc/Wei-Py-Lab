图像批量转换工具
这是一个简单的Python工具，具有图形用户界面，允许您将图像从24位转换为16位格式,并生成包含RGB565格式的转换图像数据的C头文件。
该工具使用Tkinter库用于GUI和PIL（Python Imaging Library）用于图像处理。

要求
Python 3.x
Tkinter
PIL（Python Imaging Library）

用法
运行Python脚本。
输入包含要转换的图像的输入文件夹路径。
点击“...”按钮以选择文件夹。
单击“启动！”按钮开始转换。
转换后的图像将保存在名为“images.h”的文件中，保存在输入文件夹中。

功能
检查支持的图像文件格式（.jpg，.jpeg，.png，.bmp，.ico）。暂时先定义这么多，其余格式还不一定支持
将图像转换为16位格式，并生成包含RGB565格式的转换图像数据的C头文件。

版本说明
0.2.0-beta版本更新了GUI的布局,在这个版本之前暂时不加入更多功能,以转换图片为主

0.3.0版本重新设计了GUI的布局，使其更加美观,新增了逐帧提取GIF的功能,优化了一些可能存在的问题,并将名字改为“IP_L" 全名"Integrated Processing Laboratory"

作者
Wei-RC

注意
最新版提取GIF功能无法提取为jpg格式,这个转换按钮暂时就当个装饰品用吧

免责声明：
本工具按原样提供，不附带任何保证。自行承担风险使用。
本工具仅提供解析图片数据并将其转换为数组形式保存