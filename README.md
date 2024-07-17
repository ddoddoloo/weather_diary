# weather Diary project
Description : 날시 데이터 저장 및 일기 쓰기 백엔드 구현

1. 최종 구현 API 리스트
✅ POST / create / diary
- date parameter 로 받아주세요. (date 형식 : yyyy-MM-dd)
- text parameter 로 일기 글을 받아주세요.
- 외부 API 에서 받아온 날씨 데이터와 함께 DB에 저장해주세요.

✅ GET / read / diary
- date parameter 로 조회할 날짜를 받아주세요.
- 해당 날짜의 일기를 List 형태로 반환해주세요.

✅ GET / read / diaries
- startDate, endDate parameter 로 조회할 날짜 기간의 시작일/종료일을 받아주세요.
- 해당 기간의 일기를 List 형태로 반환해주세요.

✅ PUT / update / diary
- date parameter 로 수정할 날짜를 받아주세요.
- text parameter 로 수정할 새 일기 글을 받아주세요.
- 해당 날짜의 첫번째 일기 글을 새로 받아온 일기글로 수정해주세요.

✅ DELETE / delete / diary
- date parameter 로 삭제할 날짜를 받아주세요.
- 해당 날짜의 모든 일기를 지워주세요.


2. 프로젝트 완성도 높이기
✅ DB와 관련된 함수들을 트랜잭션 처리 해주세요.

✅ 매일 새벽 1시에 날씨 데이터를 외부 API 에서 받아다 DB에 저장해두는 로직을 구현해주세요.

✅ logback 을 이용하여 프로젝트에 로그를 남겨주세요.

✅ ExceptionHandler 을 이용한 예외처리를 해주세요.

✅ swagger 을 이용하여 API documentation 을 해주세요.



## 사용 api
https://openweathermap.org/current

## 사용 스택
![image](https://user-images.githubusercontent.com/102509636/226165362-07b171bd-4e44-4b65-9554-1cbc3270ce8a.png)

![image](https://user-images.githubusercontent.com/102509636/226165387-2fd26621-72da-4134-a20a-ffa6c1c02707.png)
![image](https://user-images.githubusercontent.com/102509636/226165394-0e264281-df54-4fda-8b5d-389768375595.png)
![image](https://user-images.githubusercontent.com/102509636/226165399-15591971-ec97-47a6-b545-5ea3902f2a3c.png)
![image](https://user-images.githubusercontent.com/102509636/226165411-84d91823-d7a9-477d-b76f-5f367b743ce9.png)
![image](https://user-images.githubusercontent.com/102509636/226165425-4602e344-14c4-424e-9515-56f76ded026b.png)
![image](https://user-images.githubusercontent.com/102509636/226165429-ac869758-34b7-4581-8780-d0a257715308.png)


## 기능
![image](https://user-images.githubusercontent.com/102509636/226165578-6b2293c2-d6f4-4eb5-b3e7-332709526f02.png)
