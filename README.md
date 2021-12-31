# Water Tank Automation v2.0
It is afternoon, so I'm going to take a bath and suddenly water supply goes stop. Ooh annoying the water tank is empty. This is always happening to me. Then I have to manually switch on the water pump. There is no water level indication. How we know the tank is full? Hmm, we wait until it is overflowing. This is the time to do something cool. So I came up with an idea. A project based on esp32 to make our home water tank filling process automation.

the system should do 3 main things
1. turn on the water pump when water level is low
2. turn off the water pump when water level is high
3. show the water level

To do these main 3 things I need **2 float switches** and an **ultrasonic sensor**

functions of these devices
- float switch: detect higher and lower water level
- ultrasonic sensor: detect the exact water level by distance (so I can put that data into a display)

![tank sketch](/images/water_tank.jpg)
