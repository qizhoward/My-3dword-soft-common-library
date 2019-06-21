# myself-3dword-software-common-library


sun light ...

>map edit...            </br>
>>XYZ                   </br>
>>XZY                   </br>
>>YXZ                   </br>
>>YZX                   </br>
>>ZXY                   </br>
>>ZYX                   </br>


>
>坐标的计算方法:
>
3维坐标的计算方法有很多,                                             </br>
最常见的:X(0,0)Y(0,0)Z(0,0),即可表示一个三维坐标系,                    </br>

表示点：                                                            </br>

当然还有这种简写的:X(0,0)Y(0,0),                                      </br>
还有这种的:X(0,0,0)Y(0,0,0),Z(0,0,0),                                 </br>
还有变换转换的：                                                      </br>
                                                                    
表示向量的：                                                         </br>
0XY(0,0),                                                           </br>
0XZ(0,0),                                                           </br>

0XY(0,0,0),                                                         </br>
0XZ(0,0,0),                                                         </br>

XYZ                                                                 </br>
0(0,0,0),                                                           </br>
XYZ(0,0,0),                                                         </br>


表示线的：                                                           </br>
XYZ(0,0,0),                                                         </br>

OpenGL投影思想：                                                     </br>
包含三角函数的变换矩阵思想                                             </br>

![image](https://github.com/qizhoward/myself-3dword-soft-common-library/blob/master/投影与矩阵.png)
![image](https://github.com/qizhoward/myself-3dword-soft-common-library/blob/master/投影与矩阵2.png)

OpenGLes应用于移动通讯的图形编程：                                     </br>
WebGL的网页图形编程思想：                                             </br>




         
双重压缩,高效利用缓存                                                 </br>

![image](https://github.com/qizhoward/myself-3dword-soft-common-library/blob/master/Image/2.PNG)      
![image](https://github.com/qizhoward/myself-3dword-soft-common-library/blob/master/Image/3.PNG)      
![image](https://github.com/qizhoward/myself-3dword-soft-common-library/blob/master/Image/4.PNG)      
![image](https://github.com/qizhoward/myself-3dword-soft-common-library/blob/master/Image/5.PNG) 


反人类图:                                                                       </br>

![image](https://github.com/qizhoward/myself-3dword-soft-common-library/blob/master/Image/透明2.png)
![image](https://github.com/qizhoward/myself-3dword-soft-common-library/blob/master/Image/透明3.png)
![image](https://github.com/qizhoward/myself-3dword-soft-common-library/blob/master/Image/透明4.png)
![image](https://github.com/qizhoward/myself-3dword-soft-common-library/blob/master/Image/透明5.png)

    用1个三阶魔方棋盘叠加法构建图形:
    计算显示最大值与二次显示值,实现快速地理呈现,快速图形的构建
      
      
        19*19 = 361       19^3=6859
        20*20 = 400       20^3=8000
        22*22 = 484       22^3=10648
        
                          16^3=4096
        1个三阶魔方,计算立方体,体积                  
        10648-4096-2=6550
        6859-6550=309 误
        则实际22^3-16^3-19^3-2
        
        在以前,此方法不适用于提高精准度,
        
        如果多个魔方累加,
        如果多个多级魔方叠加,
        
        一个围棋棋盘,对角线大概需要6个一阶魔方,
        如果多个一阶魔方累加,速度会受到影响,图形的构建也会受到影响
        
        
        如果中国机器人的速度，解开魔方的速度是6.89秒
        围棋的最高速度要41.34秒,
        
        没有错误的情况下三层124.02秒,构建模型的时候会有误差,这个数值就会不准确
        124.02/60=2.067 两分钟一个3D世界的构建就能完成,
        
        如果算上黑子白子,2.067*2=4.134分钟 
        
        41.34秒*2=82.68‬秒
        82.68‬*3=248.04‬秒
        248.04/6‬0=4.134分钟　四分钟一个3D世界的构建,但是会有错误
        
        3D打印机的速度最快5分钟克隆一个
        361*12=4332个点打印完最快不到5分钟
        
![image](https://github.com/qizhoward/myself-3dword-soft-common-library/blob/master/Image/001.PNG)
![image](https://github.com/qizhoward/myself-3dword-soft-common-library/blob/master/Image/003change.png)
![image](https://github.com/qizhoward/myself-3dword-soft-common-library/blob/master/Image/002change.png)

        －－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－
        
        魔方键盘,俗称导航盒,
        
        一个按钮六种键盘,103*6=618个按钮,正常键盘按钮*魔方6个颜色=618个按钮
       
        如果立体27块,魔方内部27块的内部结构,103*27=2781个按钮,27种,如果魔方面,54个面6个颜色,103*54=5562个按钮,
        
        2781*2=5562个,
        如果在魔方键盘的基础上再加1个切换开关,5562*2最少的基础黑白,11124个按钮,
        如果一个人一个按钮,则最少需要一万人,
        
        －－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－－
        
        如果19*19=361 361个格子*103个按钮=37183个按钮 如果考虑黑白,37183*2=74366个按钮,
        围棋棋盘上每个格子都铺设键盘按钮则最少需要7万个按钮,

