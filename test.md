方法：盲水印
首先下载盲水印的工具blind-watermark，然后准备原始图片ori.png和含有姓名学号的图片name.png，放到工具的目录下
隐藏：python3 encode.py --image ori.png --watermark name.png --result test.png
提取：python3 decode.py --image test.png --orig ori.png --result watermark.png
