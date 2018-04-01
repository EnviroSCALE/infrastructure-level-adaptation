# infrastructure-level-adaptation

simulator.zip is a java simulator that simulates the multi sensor iot platform.

Simulation scenario:

D = data volume at expense -> varied for various results
M = operation time = 500 seconds
T = upload interval = 50 seconds

Sensor specs:

Sensor Name			Trace File					Type				Desired Freq		Size of readings
-----------------------------------------------------------------------------------------------------------
CO2: 				  1.txt						Physical			    5 Hz				    16
methane: 			2.txt						Physical			    5 Hz				    16
dust:				  3.txt						Physical			    5 Hz				    16
humidity:			4.txt						Virtual				    1 Hz				    16
lpg:				  5.txt						Virtual				    1 Hz				    16
event-        random
triggerred:	  values          Aperiodic ET      ----				    2048
              generated		

Rate of the poisson process in aperiodic event triggerred: 1 every 200 seconds
