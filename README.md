# sm_week07
스마트모바일프로그램설계 7주차

6주차 팀 프로젝트 활동 : https://github.com/Kim-KyungJin/sm_week06

### 팀 구성   
스마트정보통신공학과 201621216 이준석   
스마트정보통신공학과 201921036 김경진   
스마트정보통신공학과 201921054 박유리   
스마트정보통신공학과 201921083 이혜정   
스마트정보통신공학과 201921104 홍수빈    
스마트정보통신공학과 201990009 미르자크메더브 사르더르    

   ***   
### 모든 항목은 변경되거나 삭제될 여지가 있습니다   
   ***   
   
### 6주차 보완 (김경진, 홍수빈)   
>진행과정   
>>1. 테마를 통일하는 부분에서 네비게이션 기능이 작동하지 않고 튕기는 현상이 발생해서   
>>네비게이션 기능을 잠시 빼두고 다른 액티비티를 통합하였습니다.   

>>2. 리뷰, 찜 목록 등 스크롤이 길어질 수 있는 액티비티에 스크롤뷰를 추가하였습니다.   
>>스크롤뷰를 넣으면 튕기는 현상이 발생해서 오류를 고치고 있습니다.   

>>3. 데이터베이스에 저장된 데이터를 불러온 후 UI에 맞추어 띄우는 작업을 하고 있습니다.   
>>>데이터베이스 문법에 익숙하지 않아서 데이터가 제대로 로딩되지 않는 등의 오류가 있어서 수정하고 있습니다.   
>>>![image](https://user-images.githubusercontent.com/57963888/115232334-8d4d2c00-a151-11eb-8e8d-228e3ba19d0e.png)   
>>>완성하게 되면 이런 식으로 데이터베이스에 저장된 데이터를 하나씩 불러올 수 있습니다.   

>>4. 예산을 입력하는 화면에서 사용자가 어떤 활동을 위주로 돈을 사용할 지 선택하는 기능을 넣었습니다.   
>>
>>![Screenshot_20210419-040034__](https://user-images.githubusercontent.com/57963888/115230133-e4053680-a14e-11eb-97a0-951b71bac580.jpg)   

>>5. 상단바에 마이페이지로 이동할 수 있는 아이콘을 추가하여 클릭하면 마이페이지로 이동할 수 있는 기능을 넣었습니다.   
>>
>>[마이페이지 아이콘 추가](https://user-images.githubusercontent.com/57963888/115233615-17e25b00-a153-11eb-9253-e99cd8cf17a5.mp4)   

>>6. 메인화면에서 액션 바에 프래그먼트를 추가하여 각 화면별로 기능을 다르게 넣어주는 작업을 하고 있습니다.   
>>7. 뒤로가기 버튼을 누르면 이전 화면으로 돌아가는 기능을 추가하였습니다.   
>>
>>위의 기능을 정리하여 영상으로 찍었습니다.   
>>[7주차 영상](https://user-images.githubusercontent.com/57963888/115237617-b83a7e80-a157-11eb-9e09-5515e5d29ff8.mp4)   


   ***   
   
### 로그인, 회원가입 (박유리, 이혜정)   
>저번주차에 mysql을 사용하여 구현하였던 회원가입과 로그인 기능을 파이어베이스로 변경, 구현하였습니다.   
>>[회원가입 데이터베이스 연동](https://user-images.githubusercontent.com/57963888/115234841-73f9af00-a154-11eb-8733-1dbd3f46d6b2.mp4)    
>1.이메일을 이용하여 로그인과 회원가입을 할 수 있게 했으며 이때 이메일 중복을 확인하기 위해서 해당 메일에 인증링크가 가게 했습니다. 인증되지 않은 메일일 시 로그인이 되지 않습니다.   

>2. 이메일 중복 확인, 비밀번호와 이메일 정규식 확인, 비밀번호 2차 확인 등 회원가입할 때 사용자 정보의 유효성을 확인하게 했습니다.   

***   
   
### 구글 지도 띄우기, 장소 검색하기 (이준석, 미르자크메더브 사르더르)   
>진행과정   
>>추천 가게로 가는 상세 지도를 띄우기 위해 구글 지도로 검색할 수 있는 기능을 넣었습니다.     
>>새로운 액티비티를 만들어 지도만 띄우려고 시도했지만, 지도가 띄워지지 않는 오류가 있었습니다.   
>아직 지도가 띄워지지 않는 오류를 고치지 못해서 다음 주차에서 오류를 고치는 작업을 할 예정입니다.  
>
 ![캡처](https://user-images.githubusercontent.com/79889548/115240109-6515fb00-a15a-11eb-820d-e682270e7469.PNG)
 
코드에선 오류가 안뜨는데 앱을 실행하면 버튼만 눌리고 주소 입력이 안됩니다. 
