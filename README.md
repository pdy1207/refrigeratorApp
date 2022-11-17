<p align="center">
  <img src="https://user-images.githubusercontent.com/110442250/202329222-5ac59d3c-0391-4b28-a5f8-a101a96b049d.png" height="350">
  <h2 align="center">냉장고 앱</h2>
  <p align="center">정리가 안되어있던 나의 냉장고 앱으로 정리하자!<p>


  </p>
</p>

### 냉장고 앱?
  
      <냉장고를 부탁해 앱 >은 자취생,주부님들의 목적으로 만들게 되었으므로, 
      마트에서 장을 볼때 “그게 있었던가? 그냥 사자” 라는 과소비를 할때가 많습니다. 
      식재료를 저장함으로서 그러한 과소비를 해결하고 언제 어디서든 냉장고 식재료를 조회하고 관리할 수 있게 만든 앱입니다. 
      장을 보려고 했던것을 리스트에 담아 시세를 알 수 있으며, 
      일정 체크를 하면서 스케줄 조정 또한 가능합니다. 귀여운 일러스트와 모션(Lottie)을 적용하였습니다.
  
### 📱 프로젝트 기능
 
  - 문의 사항 기능
  - 광고 기능
  - 근처 마트 정보 기능
  - 식재료 관리 품명, 유통기한, D-day, 메모 기능
  - 일정 체크 기능
  - 리스트 항목 클릭 시 사이트로 이동
  - 차트기능
  - 사진 촬영 및 사진 저장 기능
  - QR기능
  
### 🛠️ 사용 기술 및 라이브러리

  - Android Studio
  - Carmera
  - lottie
  - viewpager2
  - calender
  - RoomDB
  - gps
  - cardview
  - MPAndroidChart(차트 기능)
  - 가속도계 센서(쉐이크기능) + zxing(QR코드)


### 💡 깨달은 점

- **RoomDB**
    - 이 전에 SQLite를 사용하였는데, 그러한 기능들을 완벽히 활용하면서 오류가 발생하기 <br>
      쉬운 코드를 최소화 하는 것과 간소화된 데이터베이스 경로가 가능하다.
- **쉐이크 (QR코드 기능 구현)**
    - 안드로이드에는 여러가지 센서가 내정 되어있다는 점이 있다.
    - 진동, 운동가속을 감지하는 기능을 통하여 물체가 받는 힘, 너무 짧을때는 무시 등으로 계산을하여, <br>
    컴퓨터가 만든 흑백 격자무늬 패턴 코드 즉 QR코드를 띄울 수 있게 되었다.
- **MPAndroidChart**
    - MPAndroidChart라는 차트기능을 제공하는 라이브러리가 있다.
    - 차트기능은 되게 여러가지이므로 다양한 곳에 응용해 볼 수 있다.
