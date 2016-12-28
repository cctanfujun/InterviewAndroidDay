# InterviewAndroidDay

总结一些面试问题，一些知识点。参考网上一些别人整理的资料，对于我认为没有回答好或者回答详细的问题进行补充，或者开文章分析。参考项目见底部。

## Java部分


## Android相关

1. Bitmap 的四种属性，与每种属性队形的大小？  
在 Android 中图片有四种属性，分别是：  
ALPHA_8：每个像素占用1byte内存  
ARGB_4444：每个像素占用2byte内存  
ARGB_8888：每个像素占用4byte内存 （默认）  
RGB_565：每个像素占用2byte内存(没有alpha属性)  
对于一张图片，假设其尺寸为2592x1936 pixels,默认情况下加载进来，Android系统需要为其分配2592_1936_4 bytes的空间，也就要19M。

2. View 树的绘制
 


### 参考项目

https://github.com/GeniusVJR/LearningNotes  
https://github.com/JackyAndroid/AndroidInterview-Q-A  

