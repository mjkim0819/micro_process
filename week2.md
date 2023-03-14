# 라즈베리파이 세팅

## 라즈베리파이 OS Imager 다운로드
![image](https://user-images.githubusercontent.com/108729047/224986897-7fa931a7-c046-4d68-98f5-33a298ea670b.png)  
  
[라즈베리파이](https://www.raspberrypi.com/software/)  
![image](https://user-images.githubusercontent.com/108729047/224990961-b9aa2e73-e9df-4614-8489-f9e4f8a21200.png)  
해당 사이트에 들어가면 라즈베리파이를 사용하기 위해 필요한 os(운영체제)를 다운받을 수 있다.  
  
![image](https://user-images.githubusercontent.com/108729047/224989801-e45da656-1c07-4fb8-b5ef-e04fae1ed366.png)  
자신의 컴퓨터 운영체제에 맞게 Window / MAC / Ubuntu 를 선택하여 imager를 다운받는다.  

## 라즈베리파이 OS Imager 실행
우선 Imager를 실행하기 전 별도의 USIM 카드와 카드 리더기를 준비한다.  
- 사진 
Imgaer를 다운받으면 해당 화면이 실핻된다.  
![image](https://user-images.githubusercontent.com/108729047/224991506-a2363ca1-ebf9-4b26-ad60-c01783156c11.png)
운영체제를 클릭하여 가장 첫번째 Raspberry Pi OS (32-bit)를 선택한다.  
![image](https://user-images.githubusercontent.com/108729047/224991828-6fa06162-23dc-448d-88d0-a9976bd9fee3.png)   
미리 준비했던 USIM 카드를 노트북에 연결하고
- 사진
저장소에 USIM 카드를 선택한다.  
![image](https://user-images.githubusercontent.com/108729047/224992461-d7d00376-737f-44ff-82d1-f5fc89463a18.png)  
저장소를 선택하면 오른쪽 하단에 톱니바퀴가 생기며, 세부설정을 할 수 있다.
![image](https://user-images.githubusercontent.com/108729047/224993646-be23010d-be6d-4fdd-9efc-800d39aba34c.png)  

세부 설정을 하는 이유는 노트북에 와이파이로 연결하여 모니터와 키보드를 따로 설치하지 않고 사용하기 위해서이다.  
호스트이름은 min-raspi4로 설정하였다.  
![image](https://user-images.githubusercontent.com/108729047/224994115-19d0e17b-12e4-4c20-ac1c-664b1ba138bd.png)  
사용자 이름은 호스트이름과 동일하게 해두면 사용하기 편하다.  
사용자 이름을 설정하지 않으면 자동으로 ID : pi, PW : raspberrypi로 설정된다.  
![image](https://user-images.githubusercontent.com/108729047/224995075-50be4e75-1af9-4915-83da-8497419ba67e.png)  
무선 LAN은 자주 사용하는 와이파이 환경으로 설정하면 좋지만, 환경이 자주 바뀌는 경우 휴대폰 셀룰러로 해두면 좋다.  
![image](https://user-images.githubusercontent.com/108729047/224995241-61d51865-bbf0-4aa4-866b-3b01143680eb.png)  
사용 국가가 한국이기 때문에
![image](https://user-images.githubusercontent.com/108729047/224995991-2e4c1654-d799-430c-9d21-23270c4e3618.png)  
해당 사진처럼 설정하면 시간대나 키보드가 편하게 세팅된다.  

이후 쓰기 버튼을 누르면 모든 데이터가 사라진다는 문구가 뜨므로, 필요한 데이터가 있는 USIM카드는 사용하면 안된다.  
![image](https://user-images.githubusercontent.com/108729047/224992562-545d7c6b-1345-45f3-b28e-603068f6cdf2.png)  

주의사항을 읽고 확인하면 사진처럼 USIM카드에 라즈베리 OS가 설치된다.  
![image](https://user-images.githubusercontent.com/108729047/224992803-78f353c8-3113-42bc-a1dd-f6139f4a5d9c.png)  

