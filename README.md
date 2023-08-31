# smart_spraying_sytem
A system that automatically dispenses liquid detergent to the lavatory incase the ph of ammonia is higher than normal.

## COMPONENTS
 - Ammonium sensor
 - Relay
 - esp32 micro-controller
 - lm117t  3.3V voltage regulator
 
 

### SPECIFICATIONS
##### Ammonium sensor MQ-135
 - Target gas is ammonia, sulfide, benzene series steam.
 - Detection range is 10 ~ 1000ppm
 - Loop voltage < 24V Dc
 - Hetaer voltage  5.0V +/- 0.1V AC or DC
 - Load resistance is adjustable depending on the gas being measured.
 - Sensitivity  RS(in air) / Rs ( in 400ppm H2)>5
 - Output voltage 2V ~ 4V
 
##### Relay
- Breakdown voltage 300V 
- Carry current 1.0A
- Switch speed 1ms
- Maximum switch voltage 70VDC
- Maximum power 20W


## COCLUSION
 The system was able to dispense liquid detergent when the ammonia level rose above the set value of ammonium ppm.

