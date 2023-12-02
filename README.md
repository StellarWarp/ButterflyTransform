# Butterfly Transform

Unity ECS Demo of Orbit Mechanics

![image](https://github.com/StellarWarp/OrbitSandBox/assets/49562703/9d7c49d0-94fc-4b76-9442-547b59d638d6)

![image](https://github.com/StellarWarp/OrbitSandBox/assets/49562703/023d67bd-584a-49fb-a7d9-8be537d321fb)


## Unit Design

- Currently Implementation 3 types of block
  - Structural
  - Main Thruster(for orbit maneuver)
  - Side Thruster(for rotation adjestment)
 
- Move hard-coded block to data base
- Emission texture supported
- Multiple material supported
- Dynamic material supported

![image](https://github.com/StellarWarp/OrbitSandBox/assets/49562703/4ffd5f58-d7fd-453f-8160-6a76b7d43a5f)



## Orbit Mechanics

### Stateful Physics Model

- prediection shift fixed
- implement object watch mechanism ：unwatch object is excluded by orbit prediction

![image](https://github.com/StellarWarp/ButterflyTransform/assets/49562703/f3f3ba2e-da1c-45e5-b1b9-d47d035509a9)


### Orbit Prediction

- General orbit section predication supported
- Distinct section color
- Planet-Hit prediction termination
- View Scaled orbit opacity
- Optimized by using Hermite Interpolation
- Orbit maneuver supported

![image](https://github.com/StellarWarp/OrbitSandBox/assets/49562703/3e68554d-e915-4791-8b9d-c76998ecacfa)

![image](https://github.com/StellarWarp/OrbitSandBox/assets/49562703/829d22aa-8bc1-4302-bf50-42bfc96130f4)


### Orbit Maneuver

- Physics-based Orientation Control
- Dynamic maneuver and animated maneuver system
- Orbit state system rewrited

### Orbit Maneuver Algorithm

- Lambert solver implemented 









## Unit Control

- Input System Rewrited
- Test Spawn Impeachmented


## Destruction


Demo Download see https://github.com/StellarWarp/OrbitSnadBox/releases

Operation guide:
- Right click and drag to move the camera
- Hold/release space to quickly toggle placement/selection mode
- In the selection mode, left-click to frame the object, and a circle will appear after the frame selection, which can be dragged to move the object
- Left click to place objects in placement mode



