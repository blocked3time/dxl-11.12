# dxl-11.12
dxl 라이브러리를 이용한 로봇 제어 


![image](https://github.com/user-attachments/assets/097f8f29-f02e-4375-bae3-95dcefc34d3c)


make 후 sudo ./dxl 을 실행하면 위 화면과 같이 나온다 왼쪽,오른쪽 속도값(rpm) 을 입력하면 속도에 맞추어 바퀴가 회전하며 제어할 수 있다.

과제 1 : control + c를 입력하는 경우 시그널 인터럽트에 의해 코드가 종료 되지만 while문 안에 속도값을 입력받기 위한 cin에서 코드가 정지함으로 바로 종료되지는 않고 속도값(아무 값이나)을 준 후 종료할 수 있다.

과제 2 : 현재 모터 속도와 입력한 모터 속도의 차이가 큰 경우 모터의 속도가 갑자기 바뀌게 된다면 모터에 급가속이 발생하여 소음과 진동이 발생할 수 있으므로 코드 내에서 천천히 가속 혹은 감속하는 알고리즘이 필요하다.
