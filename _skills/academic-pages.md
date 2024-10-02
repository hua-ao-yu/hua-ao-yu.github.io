---
title: "个人学术网站制作教程"
collection: skills
type: "skills"
permalink: /skills/academic-pages
date: 2024-10-01
location: "China"
---

======

# 1、修改academicpages
**1.1、各文件夹说明**：
<img src='/images/blogs/skills/academicpages/各文件夹说明1.png' width="500"> <br>
<img src='/images/blogs/skills/academicpages/各文件夹说明2.png' width="500"> <br>
**1.2、简介设置**：
<br> &emsp; （1）点击文件夹_pages中的about.md <br>
<img src='/images/blogs/skills/academicpages/设置about.md.png' width="500"> <br>
<br> &emsp; （2）填写个人简介 <br>
<img src='/images/blogs/skills/academicpages/个人简介.png' width="500"> <br>



<br> &emsp; 数据集被称为**线性可分**，如果**可以用一个线性决策边界将不同类别的数据完全分开**。这种边界可以是二维空间中的直线、三维空间中的平面，或更高维空间中的超平面。
<br>
**线性不可分**：
<br> &emsp; 数据集被称为**线性不可分**，如果**无法用单一的线性决策边界将不同类别的数据完全分开**。在这种情况下，不同类别的数据点交织在一起，无法用一条直线、平面或超平面分隔开，需要使用非线性模型或通过特征变换将数据映射到更高维空间。 <br>
线性可分例子：<br>
<img src='/images/blogs/knowledges/线性可分/线性可分.png' width="500"> <br>
线性不可分例子：
<br> &emsp; aVEP四分类数据，四种颜色代表四个类别，使用t-SNE可视化。
<img src='/images/blogs/knowledges/线性可分/线性不可分.png' width="500">

# 2、线性不可分数据的解决办法

**1、非线性模型** <br> 
&emsp; 决策树：通过树结构将数据分割成不同的类别。 <br>
&emsp; 随机森林：结合多棵树进行分类，提升性能。 <br>
&emsp; K-临近算法（KNN）：通过邻域中的样本进行分类。 <br>
**2、特征变换** <br> 
&emsp; 多项式特征：将原始特征扩展为多项式特征，增加特征维度，从而可能使数据在扩展后的特征空间中线性可分。 <br>
&emsp; 核方法：使用核函数（如径向基核RBF核、多项式核）将数据映射到更高维空间，使其在高维空间中线性可分。如核支持向量机。 <br>
**3、深度学习** <br> 
&emsp; 神经网络：使用多层感知机（MLP）或卷积神经网络（CNN）等深度学习模式来处理复杂的非线性数据。深度网络能够通过多个层次的非线性变换学习复杂的数据模式。