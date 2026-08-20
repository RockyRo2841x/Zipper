# Zipper
Making a line following micromouse
Zipper is a line following bot, instead of making a normal line follower I'm thinking of creating a [Micromouse](https://en.wikipedia.org/wiki/Micromouse) which is basically a competitive level Maze solver, but instead is a line follower.
Sources:
- https://ieeexplore.ieee.org/document/5971240
- https://www.youtube.com/watch?v=UHWE3d_au30
- https://www.youtube.com/watch?v=H78VXuEKuvo

## Components:
- ### Electronic:
	- **Microcontroller**: ESP32
	-  **IR Sensor array**: 8-10 Straight Array
		- Buy Link: https://robu.in/product/1-month-warranty-1288/
	-  **IMU Sensor**: 
		- Buy Link:
		- to Map the Track
	-  **Buck converter**:
	-  **Battery**: Lipo

- ### Mechanical:
	-  **Motors**: 2 x N20 with encoder
		- can change speeds fast due to its gear box(need to look into in more detail)
		- I need the encoder to measure the distances and also to understand where I'm on the map
		- Motor driver: tb612fng
	-  **Wheels**: 
		-  2 x High traction(Silicone/Rubber) 32mm wheels 
			- so that the bot doesn't slip or slid on sharp turns at high speeds
		-  1 x Caster wheel
			- makes the design simpler, now i have no need to design the steering system
	-  **Chassis**: ---

- 