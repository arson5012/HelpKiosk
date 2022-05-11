# :bus: 버스 예매 키오스크

군산대학교 It정보제어공학과 캡스톤 디자인  

---

</br>
  

* #### :family: 팀원
  * 정휘성, 김주하, 김예진, 이소현
   
* #### 💻 Kiosk
  * Language & Environment: Python, Java
  * 
  * 
  * 
* #### :file_folder: Server
  * AWS EC2: 웹 서버:  
  * AWS RDS: DB 서버: 
  

  
* #### 💡 구동 환경
  * Raspberry Pi 4(4GB)
  * OS Ver: Stretch 
  * Touch Screen: KLEINZ KP1401FTM 14Inch Portable Display or 한성컴퓨터 TFX133T
  * RC522 NFC Reader
  * IDE: Pycharm, Thonny, Pyqt5 Designer 
  * Git 

<hr/>


<!-------------------------------------------------------------Part 1------------------------------------------------------------------------------------------>
## 1. 개요

 * **목표**
     > 노약자가 쉽게 사용할 수 있음  
     > 청구 운영시간 이후 사용 가능  
     > 청구 직원 유무 상관 없이 사용 가능   
     > 대면을 원하지 않은 사용자 또한 사용 가능   
     > 대기시간 절감 효과  
 
 * **키오스크 메인 화면**
     > 사용자가 정보를 보다 쉽고 간단하게 확인 가능
 1. 메인1 \
    ![사진1]()
 1. 메인2 \
    ![사진2]()
  

 ---

 <!-------------------------------------------------------------Part 2------------------------------------------------------------------------------------------>
 ## 2. 블록도 설명
 <center>
     <img src="Readme_src/블록.png" alt="블록도">
 </center>

 1. 버튼 이벤트
     > 각 버튼 클릭 시 웹서버에 저장된 목적지, 시간, 좌석, 연령대별 가격 출력   

 2. 결제
     >  결제 확인 후 NFC Tag를 이용하여 결제
     >  결제 완료 정보를 DB서버에 저장 및 웹 서버에 반영
     
 3. 웹 서버
     >  목적지, 목적지별 가격 및 시간, 소요시간, 출발날짜, 좌석, 연령대별 가격 저장

 4. DB 서버
     > 미 결제 정보 및 결제 완료 정보 저장

 ---
 <!-------------------------------------------------------------Part 3------------------------------------------------------------------------------------------>
 ## 3. 핵심내용 설명

 NFC Tag   
 AWS EC2  
 AWS ADS  
 
 ---
 
 <!-------------------------------------------------------------Part 4------------------------------------------------------------------------------------------>
 ## 4. 참고문헌

 
