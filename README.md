# Saliency_based_image_segmentation
Saliency_based_image_segmentation
总体思路参考：https://www.jianshu.com/p/b33e2dd32bf8   
step1 使用opencv读入图片:   
使用matplotlib用于显示，发现出现问题，由于opencv读入图片默认为bgr，而matplotlib默认为rbg，故先转换，感谢：https://blog.csdn.net/dss875914213/article/details/84974472      
step2 使用FT算法提取出图像的显著性特征       
step3 使用SLIC(simple linear iterative clustering)算法，将图片分割成许多小部分，参考：https://blog.csdn.net/CWBARSA/article/details/89603913  
step4 输入到gradcut算法中，扣出图像，参考：https://blog.csdn.net/qq_40755643/article/details/84844125



