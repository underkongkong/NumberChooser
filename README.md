# NumberChooser
使用quartus和北邮数电开发板完成的选号机。  

##（一）实现功能：  
基本要求：  
###1、 用SW7作为选号机开关，打开开关SW7后选号机自检：8*8点阵和数码管DISP7~DISP0 全亮 0.5S 熄灭 0.5S 重复三次，进入待机状态；    
###2、 使用按键 BTN7 进入选号状态，按以下顺序进行选号，当前面的号码未选定时，后 面的按键无效。具体要求如下：   
a) 8*8 点阵轮流显示“京”“ 沪”“ 吉”“ 苏”“ 川”五个汉字，每个汉字显示停留 时间 0.5S，按动 BTN6 选中当前显示的汉字，该汉字稳定显示；   
b) 数码管 DISP5 上轮流显示“A”“ C”“ E”“ F”“ H”“ L”六个大写字母，每个字 母显示停留时间 0.4S，按动 BTN5 选中当前显示的字母，该字母稳定显示；   
c) 数码管 DISP4 上轮流显示“0-9”十个数字，每个数字显示停留时间 0.3S，按 动 BTN4 选中当前显示的数字，该数字稳定显示；  
d) 数码管 DISP3 上轮流显示“0-9”十个数字，每个数字显示停留时间 0.2S，按 动 BTN3 选中当前显示的数字，该数字稳定显示；   
e) 数码管 DISP2 上轮流显示“0-9”十个数字，每个数字显示停留时间 0.1S，按 动 BTN2 选中当前显示的数字，该数字稳定显示；   
f) 数码管 DISP1 上轮流显示“0-9”十个数字，每个数字显示停留时间 0.08S，按 动 BTN1 选中当前显示的数字，该数字稳定显示；   
g) 数码管 DISP0 上轮流显示“0-9”十个数字，每个数字显示停留时间 0.05S，按 动 BTN0 选中当前显示的数字，该数字稳定显示；   
###3、 DISP0 内容选定后表示所有内容选择完毕，所有内容整体以 2Hz 闪烁三次以示提醒， 然后稳定显示；  
###4、 使用按键 BTN7 可以重新进入选号状态，再一次进行选号。   
提高要求：   
自检过程、各项内容滚动时、内容选定后进行闪烁提醒时伴有适当的音乐，各个按 键按下时伴有按键音。  
   
##（二）资源利用情况  
资源占用率：44%（563/1270）  
引脚占用率：37%（43/116）  


