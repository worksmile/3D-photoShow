# 3D-photoShow
#### 通过鼠标从图片的不同角度进入。图片进行不同方向的翻转
#### 1.涉及到数学角度弧度计算
![Alt text](https://raw.githubusercontent.com/worksmile/3D-photoShow/master/Screenshots/1.png)
(Math.round((Math.atan2(y,x)*(180/Math.PI)+180)/90)+3)%4;   
1=====top   
2=====right   
3=====bottom    
0=====left    
##### 2.涉及到css3的一些新属性
transform，animation，@keyframes关键帧，rotate3d 3D旋转​


