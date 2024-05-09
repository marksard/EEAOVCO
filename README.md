# EEAOVCO
Eurorack 8HP Single VCO using 3340 IC.

## Specification

### Power

|Use Voltage|Current consumption|
|:--|:--|
|+12V|19mA|
|-12V|19mA|

### Input

|Name|Description|
|:--|:--|
|V/OCT||
|FM||
|PWM||
|H.SYNC|NEG/POSI/BOTH are switched by jumpers on the back|
|S.SYNC||


### Output

|Name|Description|
|:--|:--|
|PULSE|Bipoler8Vpp|
|RAMP|Bipoler8Vpp|
|TRIANGLE|Bipoler8Vpp|
|SINE|Bipoler8Vpp|
|RAMPH|Bipoler8Vpp, Morphing between from RAMP+SINE to RAMP+PULSE|


### Controller

|Name|Description|
|:--|:--|
|COARSE|About 0.6Hz～2.8khz|
|FINE|About ~8 semitone|
|PW|Pulse Width|
|PWM|PWM Depth|
|FM|FM Depth|
|RAMPH|Morphing between from RAMP+SINE to RAMP+PULSE|

## Image
![img]()

## Schematic

![img](_data/eeao_vco_rev1.0.0.png)

## Waveform

Pulse(50%)  
![img](_data/eeaovco_pulse_1.png)  

Pulse(0%)  
![img](_data/eeaovco_pulse_2.png)  

Pulse(100%)  
![img](_data/eeaovco_pulse_3.png)  

Ramp  
![img](_data/eeaovco_upramp.png)  

Triangle  
![img](_data/eeaovco_triangle.png)  

Sine(25%)  
![img](_data/eeaovco_sine.png)  

Ramph(0%)  
![img](_data/eeaovco_ramph_1.png)  

Ramph(25%)  
![img](_data/eeaovco_ramph_2.png)  

Ramph(50%)  
![img](_data/eeaovco_ramph_3.png)  

Ramph(100%)  
![img](_data/eeaovco_ramph_4.png)  

Triangle with FM  
![img](_data/eeaovco_triangle_fm.png)  

Triangle with H.Sync(NEG)  
![img](_data/eeaovco_triangle_hsync.png)  

Triangle with S.Sync  
![img](_data/eeaovco_triangle_ssync.png)  
