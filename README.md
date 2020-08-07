# Simulaciones-SMF
Asignación 1 ( Simulación de robot en mesa)
Código rapid
MODULE Module1
	CONST robtarget Home:=[[640.301700826,0,289.419411487],[0.069756473,0,0.99756405,0],[0,0,0,0],[9E+09,9E+09,9E+09,9E+09,9E+09,9E+09]];
	CONST robtarget Target_10:=[[-0.234052335,-41.066234567,115.384419999],[0.176275184,-0.339666997,0.820028671,0.42556594],[0,0,0,0],[9E+09,9E+09,9E+09,9E+09,9E+09,9E+09]];
	CONST robtarget Target_20:=[[141.187303884,-122.474219299,-0.256143936],[0.176275184,-0.339666997,0.820028671,0.42556594],[0,0,0,0],[9E+09,9E+09,9E+09,9E+09,9E+09,9E+09]];
	CONST robtarget Target_30:=[[282.608660139,-41.066234588,115.384419969],[0.176275184,-0.339666997,0.820028671,0.42556594],[0,0,0,0],[9E+09,9E+09,9E+09,9E+09,9E+09,9E+09]];
	CONST robtarget Target_40:=[[141.18730392,40.341750143,231.024983903],[0.176275184,-0.339666997,0.820028671,0.42556594],[0,0,0,0],[9E+09,9E+09,9E+09,9E+09,9E+09,9E+09]];
	PROC Path_10()
	    MoveJ Home,v300,fine,tWeldGun\WObj:=wobj0;
	    MoveL Target_10,v300,fine,tWeldGun\WObj:=Workobject_1;
	    MoveL Target_20,v300,fine,tWeldGun\WObj:=Workobject_1;
	    MoveL Target_30,v300,fine,tWeldGun\WObj:=Workobject_1;
	    MoveL Target_40,v300,fine,tWeldGun\WObj:=Workobject_1;
	    MoveJ Home,v300,fine,tWeldGun\WObj:=wobj0;
	ENDPROC
ENDMODULE
