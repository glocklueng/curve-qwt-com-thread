# curve-qwt-com-thread

/**
*********************************************************************************************************
*
*	@ProjectName : curve-qwt-com-thread
*	@Description : 
*	@Version     : V1.0
*	@Description : 
*
*	....................Update....................
*	@Version  @Date      @Design   @Description
*    V1.0    2016.11.23  Aslm       demo
*
* @ME:sillyman2008@outlook.com
*********************************************************************************************************/

**********************************
1、实时解析串口数据并绘制相关曲线 
2、串口以及数据处理单独一个进程（不影响GUI刷新) 
3、曲线、串口参数可配置、可保存 
4、log记录
5、release版本已经发布

**********************************
1、曲线配置 颜色、名称 等参数时要先点击 set按钮，然后再点击 reset按钮 开启重新绘制
2、参数保存请按 cfgSave按钮
3、串口数据格式请参考 <下位机发送格式Demo.c>
4、如果使用单片机与软件通讯，请选用较好的 串口转usb设备 ，如 CP21X ；
   不然会因为速率不够而导致数据解析会经常报错

**********************************
1、../cfg 文件夹 为配置文件
2、../log 文件夹 记录log

**********************************
1、曲线绘制基于 qwt控件
2、串口控制基于 qextserial类

**********************************
感谢 Qt开源社区 www.qter.org
本程序 串口部分 参考了社区的 qcom 1.1