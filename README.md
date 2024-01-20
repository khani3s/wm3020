# wm3020

## Processor

STM32F103C8T Clone

![image](https://github.com/khani3s/wm3020/assets/152649/27739b58-d6c9-4072-a71d-d5e014601675)

Pin	|	Description																														
-----	|	-----																														
1	|	VCC																														
2	|	GND																														
3	|	GND																														
4	|	spindle_enable																														
5	|	osc_in																														
6	|	osc_out																														
7	|	e-stop																														
8	|	GND																														
9	|	VCC																														
10	|	step_X																														
11	|	step_Y																														
12	|	step_Z																														
13	|																															
14	|	dir X (-X=3.3v)																														
15	|	dir Y (-Y=3.3v)																														
16	|	dir Z (-Z=3.3v)																														
17	|																															
18	|	spindle_direction (M4)																														
19	|																															
20	|																															
21	|																															
22	|																															
23	|	GND																														
24	|	VCC																														
25	|	x limit - PORT1(1)																														
26	|	y limit - PORT1(2)																														
27	|	z limit - PORT1(3)																														
28	|																															
29	|	spindle_pwm																														
30	|																															
31	|																															
32	|																															
33	|																															
34	|	ST-LINK (4) SWDIO																														
35	|	GND																														
36	|	VCC																														
37	|	SWCLK - ST-LINK (2) / HOME																														
38	|	step_enable																														
39	|																															
40	|	coolant (M8)																														
41	|	pause - hold/door																														
42	|	resume - start																														
43	|	reset - rst																														
44	|																															
45	|	BOOT 0 - ST-link (1) GND																														
46	|	probe - PORT1(7)																														
47	|	GND																														
48	|	VCC																														

## Board

Driver Chip: [TB67S109AFTG](https://br.mouser.com/datasheet/2/408/TB67S109AFTG_datasheet_en_20190228-1272643.pdf)

## CAD Model

## PSU

Model: CNC-600D24+48ADJ
Output 1: +24V 8A
Output 2: +48V (Adjustable) 7A
