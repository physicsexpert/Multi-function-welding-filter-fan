# 多功能焊接过滤风扇
# 项目简介：

<img src=picture/zhengti.png width=90% />

## 项目链接
### B站视频链接：https://www.bilibili.com/video/BV1T142187PJ/?spm_id_from=333.999.0.0
### 立创开源平台链接：https://oshwhub.com/expert/zi-zhi-han-jie-feng-shan

## 需要准备的材料

- 焊接风扇调速PCB板（在hardware文件夹中）和3D打印件（在model文件夹中）

<img src=picture/1.jpg width=90% />

- M3×45mm螺丝4颗、M3×10mm螺丝4颗、M3×6mm螺丝8颗

<img src=picture/luosi.png width=50% />

- M3螺母4颗

<img src=picture/luomu.png width=50% />

- M3×5mm×4.2mm热熔螺母12颗

<img src=picture/rerongluomu.png width=50% />

- 台达6038风扇1个
  
<img src=picture/fenshan.png width=50% />

- 过滤棉1块
<img src=picture/guolv.png width=50% />

- 自锁按键开关1个

<img src=picture/kaiguan.png width=50% />

- XH2.54连接线1条

<img src=picture/xh2.54.png width=50% />

- 防滑脚贴一块

<img src=picture/dianzi.png width=50% />

- 电烙铁支架1个（我这里用的是正点原子的迷你电烙铁支架）

<img src=picture/dianlaotie.png width=50% />



## 组装方法
1. 打印所有3D打印件，并在12个开孔处使用电烙铁压入热熔螺母
<img src=picture/2.png width=50% />
<img src=picture/3.png width=50% />


2. 将自锁开关对应的四个引脚焊接导线，注意指示灯正极和开关一侧接同一根导线，指示灯负极接一根线，开关另一侧接一根线
<img src=picture/4.png width=50% />


3. 将开关的穿过底座圆形开孔并锁紧固定螺母
<img src=picture/6.png width=50% />

   
4. 将开关上的导线焊接到控制板上，指示灯正极接+12V，指示灯负极接GND,开关另一侧导线接VBUS，焊接完成后将控制板放入底座内
  <img src=picture/7.png width=50% />
  <img src=picture/8.png width=50% />


5. 将风扇的四根导线穿过上盖的小开孔，与XH2.54排线连接，注意连接线序（红色电源，黑色接地，蓝色接pwm信号，黄色可不接），连接后将XH2.54排线插上控制板
  <img src=picture/9.png width=50% />
  <img src=picture/10.png width=50% />
  <img src=picture/11.png width=50% />


6. 拧上上盖上的八颗螺丝
<img src=picture/12.png width=50% />
<img src=picture/13.png width=50% />

  
7. 拧上风扇的四颗螺丝和螺母
<img src=picture/14.png width=50% />
<img src=picture/15.png width=50% />
<img src=picture/16.png width=50% />


8. 将电烙铁支架固定在顶盖上（使用双面胶或者胶水）
<img src=picture/17.png width=50% />


9. 拧上顶盖上的四个螺丝
<img src=picture/18.png width=50% />


10. 将过滤海绵放进过滤插销，并插入机器内
 <img src=picture/19.png width=50% />
 <img src=picture/20.png width=50% />


 
11. 插入焊锡丝收纳器
<img src=picture/21.png width=50% />


12. 安装电位器旋钮和脚贴
<img src=picture/22.png width=50% />
<img src=picture/23.png width=50% />




13. 安装完成
<img src=picture/24.png width=50% />


## 注意事项
- 请务必按照说明给出的组装顺序进行组装，否则可能出现无法安装的情况
- 请配合支持PD/QC快充协议的充电器使用，否则可能出现无法诱骗出高电压的情况
- 风扇转速很快，使用时请注意安全，不要用手触摸扇叶
- 请使用密度较高的滤网，保证焊锡烟雾过滤效果
- 请使用FDM打印机打印，这样可以便于热熔螺母安装
- 焊接时注意开关引脚的接线和pcb板焊点的对应关系

