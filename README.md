# MIN_USB_TO_TTL
说明：超小USB TO TTL串口工具，超便携，同时带有过压保护功能。

			文件目录说明
	1.Gerber
		内含Gerber文件(Gerber_PCB_USB-TO_TTL.zip)压缩包，可以直接在嘉立创打板，毕竟有5元打板的羊毛薅
		立创下单地址：https://www.jlc.com
	
	2.PCB工程
		内含AD(Altium Designer)、立创EDA，两种软件打开的PCB文件
		文件(PCB_USB-TO_TTL_EDAProject.json)使用立创EDA软件导入即可查看PCB
		文件(PCB_USB-TO_TTL_PCB_ADProject.pcbdoc)使用AD(Altium Designer)软件导入即可查看PCB
		
	3.原理图
		内含原理图文件、PCB顶层丝印图、PCB底层丝印图、BOM表
	
	4.数据手册
		内含CP2102芯片数据手册
		
		
			PCB焊接注意
	1.在PCB底层丝印标注的5V和3.3V的0殴电阻是用来选择排针VCC输出的电压，
	  只需要焊接其中一个即可，需要VCC输出5V焊接5V的0欧电阻，需要3.3V焊接3.3V的。
	
	
