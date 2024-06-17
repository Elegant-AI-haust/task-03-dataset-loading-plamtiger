[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/seRHWk3F)
# Assignment

Task3:数据集的读取与可视化  
一、任务目的：了解图像数据集的存储方式，学会读取数据并对数据进行存储格式的转换，实现数据可视化。

二、主要任务（以coco数据集的标签文件为例）：

1、标签数据读取：读取数据集标签文件“TestData_coco.json”；

2、图像数据下载：根据标签数据中图像链接下载相应图像并以图像ID命名；

3、数据存储格式变换：为幅图像建立一个字典，字典中包含{'image_ids', 'category_ids', 'bboxes', 'segmentations'}等键，每个键构建一个list，存储该幅图像中包含的目标类别、目标框和分割标签信息。  
4、可视化图像ID为1000的图像及标签：显示图像、目标框和分割信息，并在目标框左上角标注类别名称，如图例所示；

![img](https://github.com/AceForest/Assignment/blob/main/Example%20image/segmentation_139.png)

5、抽取部分数据保存成新的json文件：从数据集中挑选出图像ID为‘139’，‘724’，‘785’，‘885’和‘1000’的图像及相应标注框和分割掩码标签，保存成新的标签文件，格式与原文件保持一致。

三、任务要求：
- 语言不限，推荐使用Python语言
- 将代码文件添加到该仓库中，例如solution.py
- 将个人信息：**专业xx班级xx-姓名xxx-学号xxx-联系方式xxxx**(微信号)以注释的形式附在代码开头
```python
// 专业xx班级xx-姓名xxx-学号xxx-联系方式xxx
def example():
    print("example")
    return 
```
