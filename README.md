# Traffic-Light-Simulation


## Purpose
A traffic light simulation in [Digital](https://github.com/hneemann/digital). It contains two lights, one for a Main Street and one for a Side Street. It uses 7474D Flip Flops ICs, Counter ICs, and Seven Segment Displays at a clock signal of 1 Hz.

The main street has a green light for a minimum of 8 seconds (Tl) so long as there are no vehicles on the side street sensor or a train is present. 
The side street has a green light for a maximum of 7 seconds (Ts).
Yellow lights have a duration of 2 seconds.
While the train sensor is active, the side street will not have a green light and emergency vehicles can wirelessly activate a sensor to turn both lights Red. 

### The State Diagram:
<img width="1111" height="798" alt="image" src="https://github.com/user-attachments/assets/7c534cae-2a1f-470d-99ba-cb20c152fcec" />

### State Table:
<img width="1529" height="501" alt="image" src="https://github.com/user-attachments/assets/d72c0907-25a4-40b3-83fd-b4bcaeb1fe60" />

