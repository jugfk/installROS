# 젯슨 나노에 ROS를 설치하고 구동해보기
***
(1) 다운로드 & 설치
```
git clone https://github.com/jetsonworld/git clone https://github.com/jetsonworld/installROS.git.git
cd installROS
./install-ros.sh
(or)
sh install-ros.sh
```
(2) 거북이 시뮬레이터 시작하기
```
roscore
```
이제 roscore는 ROS의 통신이 매인이되는 운영체제가 움직이기 시작합니다.  이 상태에서 조금 시작한 터미널 애플리케이션과는 다른 터미널 응용 프로그램 (윈도우)를 시작합니다.  ROS는 이러한 여러 터미널을 열고 명령을 실행 해 나가는 것이 기본 스타일입니다.  두 번째 터미널을 열어서  rosrun 명령에서 turtlesim 패키지의 turtlesim_node를 시작합니다.

```
rosrun turtlesim turtlesim_node
```
다음 그림과 같이 거북이의 일러스트가 나타나면 성공입니다.
다음은 새로운 터미널을 또 엽니다.
열어서 다음과 같이 실행하면 키보드를 이용해서 거북이를 움직일수 있습니다.
```
rosrun turtlesim turtle_teleop_key
```

![image](https://raw.githubusercontent.com/jetsonworld/installROS/master/ROS_Turtle.jpg)

## 출처
https://github.com/karaage0703/jetson-nano-tools

(Thank you for your precious devotion.)
