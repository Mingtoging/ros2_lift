# ros2_lift
○ 지게차 로봇 팀 : 조민석, 이주현

# 개발환경
○ Ubuntu20.04, ROS2 foxy, Turtlebot3 

# 배경
○ 무인지게차는 자동화를 통해 물류순환속도를 높이고, 재고공간을 효율적으로 활용하게 해 생산성을 높일 수 있는 것이 가장 큰 특징이다.

○ 한 계획된 경로로 작업을 수행하기에 작업장에서의 사고 위험 역시 크게 줄일 수 있다. 이 때문에 반복작업이 빈번하게 이뤄지는 물류창고나 24시간 무인가동이 필요한 사업장, 좁은 공간의 작업장 등에서 활용되어 작업 효율을 높일 수 있다.

○ 특히 모든 설비와 장치가 무선통신으로 연결되는 스마트공장을 구축한 제조업체들의 수요에도 부합될 것으로 기대된다.

# 주요기능
OpenCV 기반의 aruco marker를 사용하여 마커의 2D Pose 정보를 읽어와 터틀봇을 마커의 중앙으로 위치 시키고 Arduino Serial을 사용하여 서보 모터를 컨트롤하여 미션을 수행합니다.

구동 영상보기 https://www.youtube.com/watch?v=5JBPTG4YDPo&t=8s
![image](https://user-images.githubusercontent.com/89680719/146515818-d87258c4-cea8-46c8-ab39-bff358ac642f.png)


목표에 도착한 로봇이 marker를 찾기위하여 회전을 합니다.
marker를 찾은 로봇을 마커의 중앙으로 위치하기 위한 이동을 실시 합니다.
marker 앞에서 미션을 수행한 로봇은 종료지점으로 복귀합니다.
연구기록 YouTube -- > https://www.youtube.com/channel/UCLSgng38L1zVYUgOHEe1yOg

![image](https://user-images.githubusercontent.com/89680719/146515902-8afc8c6a-5f18-4c3f-bd30-b771bd7a5f21.png)
