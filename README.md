### 对Labelme标注工具生成的xml文件进行解析
功能：根据xml中标注的行人坐标信息将行人目标从图片上截取下来并保存成一幅图片到指定路径下。



`./image/`:存放原始帧图片，命名格式为：`frame_XXXXXX.jpg`

`./xml/`:存放含有标注信息的xml文件，命名格式为：`frame_XXXXXX.xml`

`./output/`:处理后的图片存放路径，处理后的图片命名格式为：`ID编号_摄像头编号_frame_图片帧名.jpg`