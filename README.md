# Pneumatic-bench-control-by-PLC
## _ladder programming for pneumatic stem sequence_

objetivo: programar un secuencia de control para la salida y entrada de tres vastagos neumatico, por medio de lenguaje en escalera CoDeSys y FST

## Materials
- PLC
- 1 Modulo 8 relevadores 5V a 1A
- 3 Micro switchs con pulsador
- 1 Tarjeta de comunicación max232
- 1 Cable USB serial
- Fuente simetrica variable

## Ladder programming in CoDeSys
![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/f4c48ef6-201a-484c-a408-6b1575976376)
![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/435f2ccc-58f9-4f7e-93d6-c31183ffa70a)
![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/49f21fd8-abc9-4ba4-9752-eb2c63c07029)
![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/cc3cc5e8-4909-4c7e-b8f9-b4f252fc9034)
![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/e8b3c1ee-f733-4789-9e51-b226fe841a07)

## Simulation visualization
![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/97d660c4-795b-4cea-bcd8-f5d0f139635d)
![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/488a0cdb-a89c-4408-86e5-4c0a5d6cc66b)
![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/376f2d60-5a68-43d1-a7a6-ce39b5f96cbf)
![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/1f80a133-2e3d-4e7f-b2ad-577e4485aaa3)

## Structured programming for the animation of the offspring
_Codigo de vastago 1_
```python
IF VALVULA1 = TRUE THEN
	IF X1 = 100 THEN
		X1:= 100;
	ELSE 
		X1:= X1 + 1;
	END_IF
END_IF

IF VALVULA2 = TRUE THEN
	IF X1 = 0 THEN
		X1:=0;
	ELSE
		X1:= X1-1;
	END_IF
END_IF
```

_Codigo de vastago 2_
```python
IF VALVULA3 = TRUE THEN
	IF X2 = 100 THEN
		X2:= 100;
	ELSE 
		X2:= X2 + 1;
	END_IF
END_IF

IF VALVULA4 = TRUE THEN
	IF X2 = 0 THEN
		X2:=0;
	ELSE
		X2:= X2-1;
	END_IF
END_IF
```

_Codigo de vastago 3_
```python
IF VALVULA5 = TRUE THEN
	IF X3 = 100 THEN
		X3:= 100;
	ELSE 
		X3:= X3 + 1;
	END_IF
END_IF

IF VALVULA5 = FALSE THEN
	IF X3 = 0 THEN
		X3:=0;
	ELSE
		X3:= X3-1;
	END_IF
END_IF
```


## Programming conversion in CoDeSys to FST
![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/086428ec-7f1a-4aae-acb6-657cc4876992)
![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/d212e06e-0546-4720-9d43-6b1d62dd11a3)
![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/302fefcd-f122-4738-8632-d425c05de920)
![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/68f5f14a-0581-478f-a101-af7085c87fbb)
![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/33ced741-38e0-4051-9bac-4e17110064df)
![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/53e68d03-243f-4c62-827e-df9e28d1d7a0)
![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/56a721f2-eab0-4308-9225-1c222924dd9d)
![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/10c106ea-0261-49f5-96c7-7f39c9fc3abf)


## video of the practice carried out physically
_video final de la practica en fisico con apoyo del banco neumatico_

video...





