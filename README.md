# AECOBOT_Explanation

**Aecobot**은 일종의 자율주행로봇 플랫폼이다. 본 플랫폼은 로봇티즈사의 Manipulator-H, clearpath의 로봇 이동체 husky UGV, 인텔사의 depth 카메라, 
velodyne사의 VLP-16 및 2개의 CMOS카메라를 모델링하고 Aecobot의 시뮬레이션 환경 및 실제 플랫폼을 구축하였다. 가상 플랫폼과 실제 플랫폼의 인터페이스를 맞춰 가상 환경에서 알고리즘을 테스트하여 실제 환경에 적용하여 테스트 진행하였다. (소스 코드는 대외비로 비공개)

[![Watch the video](https://imgur.com/trReNwp)](https://youtu.be/6dMNyTeqqLY)

## 1. 모델링한 아이템

시뮬레인션에서 모델링한 아이템들은 아래와 같다. 
1. Husky UGV
2. Manipulator-H
3. Real sense depth camera d435
4. CMOS camera
5. Velodyne VLP-16

![H/W picture](https://github.com/YDK18/AECOBOT_Explanation/blob/master/picture/1.png)

## 2. OS
**Ubuntu 16.04 LTS** with **ROS kinetic** installed

## 3. 개별 Application (SLAM/Navigation/Motion_Planning) Test
1. SLAM(Gmapping)


2. Navigation


3. Motion planning
