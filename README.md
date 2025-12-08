# Smart Mobility 2025--AMR1 Modules

This repository contains the codes implementen on the microcontrolers use in the AMR1 plataform

# AMR1 Module Description Summary

| Module | Description | Subscribes | Publishes |
|------|-------------|------------|-----------|
| **amr_imu_encoder** | Odometry estimation from IMU + Encoder | Gets data via Pyserial from ESP32 |`/amr/odom`|
| **pose_ekf_amr** | Pose estimation from IMU + Encoder \[x, y, θ\] | `/amr/odom`| `/amr/pose` |
| **amr_pure_pursuit** | Pure Pursuit controller for autonomous driving | `/amr/pose`| None |
| **trayectoria_grabar_csv_node** | Node to record waypoints and plot desired trajectory | `/amr/pose` | None |


## Authors

Abraham Moro-Hernandez
Tecnologico de Monterrey – Campus Puebla
--Smart Mobility Concentration-- 
LinkedIn www.linkedin.com/in/abraham-moro-hernandez-amh19

Mariana Manjarrez Lima
Tecnologico de Monterrey – Campus Puebla
--Smart Mobility Concentration-- 
E-mail: marianamanjarrezlima@gmail.com

Iván Valdéz del Toro
Tecnologico de Monterrey – Campus Puebla
--Smart Mobility Concentration-- 
LinkedIn https://www.linkedin.com/in/ivan-valdez-069730365?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app

Franco Abraham Díez
Tecnologico de Monterrey – Campus Puebla
--Smart Mobility Concentration-- 
LinkedIn www.linkedin.com/in/franco-abraham-diez

Yonathan Romero Amador
Tecnologico de Monterrey – Campus Puebla
--Smart Mobility Concentration-- 
E-mail: romeroamadoryonathan@gmail.com

Pedro García Millán
Tecnologico de Monterrey – Campus Puebla
--Smart Mobility Concentration-- 
LinkedIn www.linkedin.com/in/pedro-garcia-millan





## License

Distributed under the Apache 2.0 License, fully compatible with the ROS 2 ecosystem.

This project is based on the Quanser QCar1 and AMR1 ROS 2 environment and the pal.products.qcar libraries.
Developed as part of the Smart Mobility course (MR3004C) at Tecnológico de Monterrey.

