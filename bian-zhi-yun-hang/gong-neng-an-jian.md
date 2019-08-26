# 功能按键

![](../.gitbook/assets/gong-neng-an-jian.png)

### F1 复位（编织准备）

图标显示墨绿渐变色状态：编织准备，归零复位  
图标显示老黄渐变色状态：编织确定，进入编织（复位操作完成后转换）

拉杆启动或手移机头返回至左限点处进入原点复位，流程如下：

1. 选针器刀头复位（机头不在左、右限位时）
2. 电磁铁复位（换梭电磁铁、三角控制电磁铁）
3. 选针器刀头再次复位（机头到达左限位时）
4. 度目马达及生克电机原点复位
5. 摇床伺服电机原点复位（前摇床示例）  （1）针床左移，离开零位探头（探头指示灯灭）  （2）针床右移至零位探头停止（探头指示灯亮），完成复位
6. 生克电机至工作参数中前后沉降片复位设定值（无生克步进控制或在系统参数设置页将生克有效关闭则略去此步）
7. 归零复位完成后，图标显示状态2，进入编织运行

**警告**：

按手动原点键前，请检查针床摇床位置。如果摇床侧针板不在原点位置，同时前后针床上均有织 物，则要脱掉织物的一面，之后才可按手动原点键。 手动原点键的作用是将度目和摇床位置回复到原始位置（零点），以及复位机头上的三角、换梭芯子等。

### F2 行锁定

图标显示上锁状态：重复编织，执行第1行第2行循环编织  
图标显示开锁状态：无锁定，按编织行顺序执行

**警告**：

在编织中使用卷布罗拉（主罗拉或副罗拉）后方可使用该键。编织过程中按重复键无效，将弹出报警提示，即原点复位完成后，须先按下此键再启动操作拉杆时有效，也可以在首行机头右行至中途拉杆停车（准备预选行），再按下此键，然后启动拉杆。

### F3 机头速度（兔子、乌龟图标）

图标显示乌龟状态：慢速编织（拉杆慢动）  
****图标显示兔子状态：快速编织（拉杆快动）

无需停车即可切换编织速度。

乌龟状态：当前状态为慢速编织，切换快速编织将在下一行执行  
兔子状态：当前状态为快速编织，切换慢速编织在当前行立刻执行

### F4 单片停车

一片编织（单片）、循环编织切换

图标显示墨绿渐变色状态：循环编织  
图标显示老黄渐变色状态：单片编织，完成一片编织后，机头停止在左侧花版起针点外，蜂鸣器发出断续报警提示音

### F5 报警关闭

默认：开启

图标显示老黄渐变色状态：报警关闭   
图标显示墨绿渐变色状态：报警有效（遇报警时发出断续蜂鸣提示）

**说明**：

报警关闭时只对断纱，大纱结，边纱报警暂时取消，其余报警仍生效

### F6 纱嘴提起

默认：提起 

图标显示墨绿渐变色状态：纱嘴使能   
图标显示老黄渐变色状态：纱嘴休止

**说明**：

当机头运行在编织区内时，由于突然断纱等原因（机器停于衣片之间），因带纱嘴的电 磁铁处于工作位置，如需快速移出纱嘴，按下此键使纱嘴处于休止位置。 纱嘴休止时，启动操作拉杆运行将不执行，需再按此键使纱嘴使能后方可重新进入编织运行。




