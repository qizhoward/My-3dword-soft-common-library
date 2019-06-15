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




我这种的新的计算方法及定位方法：                                        </br>
双重压缩,高效利用缓存                                                 </br>

![image](https://github.com/qizhoward/myself-3dword-soft-common-library/blob/master/Image/2.PNG)      
![image](https://github.com/qizhoward/myself-3dword-soft-common-library/blob/master/Image/3.PNG)      
![image](https://github.com/qizhoward/myself-3dword-soft-common-library/blob/master/Image/4.PNG)      

反人类图:                                                                       </br>

![image](https://github.com/qizhoward/myself-3dword-soft-common-library/blob/master/Image/透明2.png)
![image](https://github.com/qizhoward/myself-3dword-soft-common-library/blob/master/Image/透明3.png)
![image](https://github.com/qizhoward/myself-3dword-soft-common-library/blob/master/Image/透明4.png)

    用1个三阶魔方棋盘叠加法构建图形:
    计算显示最大值与二次显示值,实现快速地理呈现,快速图形的构建
        
        19*19 = 361       19^3=6859
        20*20 = 400       20^3=8000
        22*22 = 484       22^3=10648
        
                          16^3=4096
        １个三阶魔方,计算立方体,体积                  
        10648-4096-2=6550
        6859-6550=309 误
        则实际22^3-16^3-19^3-2
        
        在以前,此方法不适用于提高精准度,
        
        如果多个魔方累加,
        如果多个多级魔方叠加,
        
          
                        
                                                                                  
