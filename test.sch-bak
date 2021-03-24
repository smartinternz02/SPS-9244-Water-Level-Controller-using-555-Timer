EESchema Schematic File Version 4
EELAYER 30 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 1 1
Title "LM555 TIMER"
Date "2021-03-22"
Rev "1.0"
Comp ""
Comment1 ""
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L power:GNDREF #PWR01
U 1 1 605872A1
P 3300 3300
F 0 "#PWR01" H 3300 3050 50  0001 C CNN
F 1 "GNDREF" H 3305 3127 50  0000 C CNN
F 2 "" H 3300 3300 50  0001 C CNN
F 3 "" H 3300 3300 50  0001 C CNN
	1    3300 3300
	1    0    0    -1  
$EndComp
Wire Wire Line
	3300 3300 3100 2600
$Comp
L Device:CP C1
U 1 1 60588B82
P 6350 3200
F 0 "C1" H 6468 3246 50  0000 L CNN
F 1 "10ufd/16V" H 6468 3155 50  0000 L CNN
F 2 "Capacitor_SMD:CP_Elec_6.3x5.2" H 6388 3050 50  0001 C CNN
F 3 "~" H 6350 3200 50  0001 C CNN
	1    6350 3200
	1    0    0    -1  
$EndComp
Wire Wire Line
	6350 3050 6350 3000
Wire Wire Line
	6350 3350 6350 3500
Wire Wire Line
	6350 2900 5850 2900
Wire Wire Line
	6350 3500 4150 3500
Wire Wire Line
	4000 3500 4000 2600
Wire Wire Line
	3100 2600 3400 2600
Connection ~ 4000 2600
Wire Wire Line
	4000 2600 5050 2600
$Comp
L Device:R_Small R4
U 1 1 60589FCF
P 6450 2800
F 0 "R4" H 6509 2846 50  0000 L CNN
F 1 "150K 1206" H 6509 2755 50  0000 L CNN
F 2 "Resistor_SMD:R_1206_3216Metric" H 6450 2800 50  0001 C CNN
F 3 "~" H 6450 2800 50  0001 C CNN
	1    6450 2800
	1    0    0    -1  
$EndComp
Wire Wire Line
	6500 2900 6500 3000
Wire Wire Line
	6500 3000 6350 3000
Connection ~ 6350 3000
Wire Wire Line
	6350 3000 6350 2900
$Comp
L Device:R_Small R3
U 1 1 6058E45D
P 6450 2600
F 0 "R3" H 6509 2646 50  0000 L CNN
F 1 "150K 1206" H 6509 2555 50  0000 L CNN
F 2 "Resistor_SMD:R_1206_3216Metric" H 6450 2600 50  0001 C CNN
F 3 "~" H 6450 2600 50  0001 C CNN
	1    6450 2600
	1    0    0    -1  
$EndComp
Wire Wire Line
	6500 2900 6450 2900
Connection ~ 6450 2700
Wire Wire Line
	5850 2500 5850 2600
Wire Wire Line
	5850 2700 6450 2700
Connection ~ 5850 2700
Wire Wire Line
	5800 2700 5850 2700
$Comp
L ABT~lib:LM555 U1
U 1 1 60586CB9
P 5450 2800
F 0 "U1" H 5450 3265 50  0000 C CNN
F 1 "LM555" H 5450 3174 50  0000 C CNN
F 2 "Package_SO:SOIC-8_3.9x4.9mm_P1.27mm" H 5450 3150 50  0001 C CNN
F 3 "" H 5450 3150 50  0001 C CNN
	1    5450 2800
	1    0    0    -1  
$EndComp
Text Label 5950 2900 0    50   ~ 0
THRTRG
Text Label 5050 2700 0    50   ~ 0
THRTRG
Wire Wire Line
	4650 3000 5050 3000
Text Label 4800 3000 0    50   ~ 0
vcc
Text Label 6050 2500 0    50   ~ 0
vcc
$Comp
L Device:LED D2
U 1 1 605AEAB3
P 4700 3300
F 0 "D2" V 4647 3380 50  0000 L CNN
F 1 "LED" V 4738 3380 50  0000 L CNN
F 2 "LED_SMD:LED_1206_3216Metric" H 4700 3300 50  0001 C CNN
F 3 "~" H 4700 3300 50  0001 C CNN
	1    4700 3300
	0    1    1    0   
$EndComp
$Comp
L Device:LED D1
U 1 1 605B21C5
P 4400 2950
F 0 "D1" V 4393 3167 50  0000 C CNN
F 1 "LED" H 4393 3076 50  0000 C CNN
F 2 "LED_SMD:LED_1206_3216Metric" H 4400 2950 50  0001 C CNN
F 3 "~" H 4400 2950 50  0001 C CNN
	1    4400 2950
	-1   0    0    1   
$EndComp
$Comp
L Device:R_Small R1
U 1 1 605B259A
P 4150 3300
F 0 "R1" H 4209 3346 50  0000 L CNN
F 1 "470E 1206" H 4209 3255 50  0000 L CNN
F 2 "Resistor_SMD:R_1206_3216Metric" H 4150 3300 50  0001 C CNN
F 3 "~" H 4150 3300 50  0001 C CNN
	1    4150 3300
	1    0    0    -1  
$EndComp
Wire Wire Line
	5050 2900 4600 2900
Wire Wire Line
	4550 2900 4550 2950
$Comp
L Device:R_Small R2
U 1 1 605B2E79
P 4200 2750
F 0 "R2" H 4259 2796 50  0000 L CNN
F 1 "470E 1206" H 4259 2705 50  0000 L CNN
F 2 "Resistor_SMD:R_1206_3216Metric" H 4200 2750 50  0001 C CNN
F 3 "~" H 4200 2750 50  0001 C CNN
	1    4200 2750
	1    0    0    -1  
$EndComp
Wire Wire Line
	4250 2950 4150 2950
Wire Wire Line
	4150 2950 4150 2850
Wire Wire Line
	4150 2850 4200 2850
Wire Wire Line
	4200 2650 4400 2650
Text Label 4350 2650 0    50   ~ 0
vcc
Wire Wire Line
	4700 3150 4150 3150
Wire Wire Line
	4150 3150 4150 3200
Wire Wire Line
	4700 3450 5000 3450
Wire Wire Line
	5000 3450 5000 3050
Wire Wire Line
	5000 3050 4600 3050
Wire Wire Line
	4600 3050 4600 2900
Connection ~ 4600 2900
Wire Wire Line
	4600 2900 4550 2900
Wire Wire Line
	4150 3400 4150 3500
Connection ~ 4150 3500
Wire Wire Line
	4150 3500 4000 3500
$Comp
L Connector:TestPoint vcc1
U 1 1 605B993F
P 6450 2100
F 0 "vcc1" H 6508 2218 50  0000 L CNN
F 1 "+9v vcc" H 6508 2127 50  0000 L CNN
F 2 "TestPoint:TestPoint_Pad_D4.0mm" H 6650 2100 50  0001 C CNN
F 3 "~" H 6650 2100 50  0001 C CNN
	1    6450 2100
	1    0    0    -1  
$EndComp
Wire Wire Line
	6450 2100 6450 2500
Connection ~ 6450 2500
Wire Wire Line
	5850 2500 6450 2500
$Comp
L Connector:TestPoint GND1
U 1 1 605BC557
P 3400 2600
F 0 "GND1" H 3458 2718 50  0000 L CNN
F 1 "GND" H 3458 2627 50  0000 L CNN
F 2 "TestPoint:TestPoint_Pad_D4.0mm" H 3600 2600 50  0001 C CNN
F 3 "~" H 3600 2600 50  0001 C CNN
	1    3400 2600
	1    0    0    -1  
$EndComp
Connection ~ 3400 2600
Wire Wire Line
	3400 2600 4000 2600
$EndSCHEMATC
