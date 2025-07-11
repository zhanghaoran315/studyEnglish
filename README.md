善始者实繁，克终者盖寡



LTE_SendAtCmd("AT+CIPSTART=\"TCP\",\"mac.alex.xin\",36666\r\r");	
// alex本地服务器（基本也不会用）
LTE_SendAtCmd("AT+CIPSTART=\"TCP\",\"hz.alex.xin\",36666\r\r");	  
// 浩然的本地测试服务器（开发调试用）
LTE_SendAtCmd("AT+CIPSTART=\"TCP\",\"47.96.81.114\",36666\r\r");	
// 吞天蛙线上服务器（发出去的所有设备连这个）
LTE_SendAtCmd("AT+CIPSTART=\"TCP\",\"47.114.169.91\",36666\r\r");	
// 外包的服务器（后面几乎不会用了）

                


