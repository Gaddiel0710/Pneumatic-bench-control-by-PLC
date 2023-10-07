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

![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/05a7d221-149b-4301-90fa-a93894ecbd18)
![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/63473c87-d1a3-47e6-88b4-446260fa4ff9)
![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/b638485a-c9e9-4e26-a189-165037158298)
![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/4e377c5c-f68d-48e2-8d68-3f629a5d4651)
![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/5bf30155-c739-4cf4-8b0e-d0411d96d8e4)
![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/440803cd-5347-4dff-9bfa-26788480ca2a)
![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/adaf7eda-c19e-48f8-8eb2-ca60bca4b7a4)
![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/6deb4fb4-480d-47a0-afe0-bacf89a5cbdc)
![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/ebd175c4-a8bc-45d8-ac5e-9ad660a11998)
![image](https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/730df96d-d5ab-4b63-a224-fe7b579529a6)


## video of the practice carried out physically
_video final de la practica en fisico con apoyo del banco neumatico_

https://github.com/Gaddiel0710/Pneumatic-bench-control-by-PLC/assets/135661300/74fe795b-e8da-45d7-9302-b9c6fb98819d
