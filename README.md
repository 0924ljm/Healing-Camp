<h1>Healing Camp - 팀 프로젝트</h1>
<br>

![healingcamp1](https://github.com/0924ljm/Healing-Camp/assets/97243334/6ebe667d-25b6-47e7-890e-4f4e4eb08202)




<br>
<br>

## 프로젝트 목적
<br>

- 하나의 사이트에서 캠핑장 예약과 캠핑용품 구매가 모두 가능한 사이트 제작
  ![img](https://github.com/0924ljm/Healing-Camp/assets/97243334/6a7672a1-f3c6-49fe-8118-e24a4ba212c3)

---

## 프로젝트 인원
<br>

- 프론트 0명, 백엔드 5명

<br>

---

## 프로젝트 기간
<br>

- 2023-11-20 ~ 2023-11-29

![img_2](https://github.com/0924ljm/Healing-Camp/assets/97243334/3d8b76f6-12d1-4712-ac41-f8b80d0ed05e)

<br>

---

## 팀 개발 환경
<br>

- 운영체제 : Windows
- 개발도구 : Visual Studio Code, Intellij
- DB : Mysql
- Server : Apache Tomcat 9.0.82
- Language: HTML5, CSS3, JavaScript, JQuery, AJax, Java, Jstl, JSP
- FrameWork: Spring, MyBatis

<br>

---


## ER-다이어그램
<br>

![img_3](https://github.com/0924ljm/Healing-Camp/assets/97243334/6671067c-87a6-458a-b5af-3e37ffa9f1c5)


<br>

---

## 맡은 파트
<br>

- <h3>캠핑장 디테일 페이지 (백엔드)</h3>
- <h3>상점 디테일 페이지 (프론트,백엔드)</h3>
- <h3>상점 장바구니 페이지 (프론트, 백엔드)</h3>
- <h3>상점 결제 페이지 (프론트)</h3>
- <h3>마이페이지 - 캠핑장, 아이템 찜 목록 (백엔드)</h3>
- <h3>마이페이지 - 리뷰작성, 수정, 삭제 (백엔드)</h3>


<br>

---


## **캠핑장 디테일 페이지**
<br>

![img_6](https://github.com/0924ljm/Healing-Camp/assets/97243334/de3121d0-d7ca-4abc-a0b7-9da2e593655d)
#### 1.캠핑장 정보 표시 (사진, 이름, 주소, 전화번호, 평점, 예약가능 자리 등)
#### 2.캠핑장 지도 api
#### 3.현재 로그인한 유저의 찜상태 표시, 클릭시 찜목록에 추가/제거
- ####   비로그인시 "로그인이 필요합니다." 메세지 띄워주기
#### 4.캠핑장 예약 페이지로 이동
#### 5.해당 캠핑장 리뷰 리스트 보여줌

<br>

---

## **상점 디테일 페이지**
<br>

![img_8](https://github.com/0924ljm/Healing-Camp/assets/97243334/9730d267-1093-4c94-af18-446f67c0c4f7)
#### 1.상품 정보 표시 (이미지, 브랜드, 제품명, 가격 ,배송비 등)
#### 2.상품 수량 조절
#### 3.유저의 찜상태 표시, 클릭시 찜목록에 추가/제거
#### 4.클릭시 채크된 수량만큼 장바구니에 추가 or "이미 추가된 상품입니다." 메세지 띄워주기 
- #### 비로그인시 "로그인이 필요합니다." 메세지 띄워주기
#### 5.결제 페이지로 이동

<br>

---

## **상점 장바구니 페이지**
<br>

![img_9](https://github.com/0924ljm/Healing-Camp/assets/97243334/64a9db4b-efa4-4fb1-abdf-10778f6b01fd)
#### 1.유저의 장바구니 목록 보여주기
#### 2.전체선택, 개별선택
#### 3.선택한 상품 장바구니에서 삭제
#### 4.장바구니 비우기
#### 5.상품 수량 조절 (바로바로 장바구니 DB 수량 업데이트)
#### 6.해당상품만 주문하기
#### 7.해당상품 장바구니에서 삭제
#### 8.선택된 상품 전체 가격정보 표시
#### 9.선택된 상품들 모두 결제하기 페이지로 이동

<br>

---

## **상점 결제 페이지**
<br>

![img_10](https://github.com/0924ljm/Healing-Camp/assets/97243334/f10bf55b-37dd-4c42-a98d-337fec7e7ec0)
#### 1.배송지 입력
#### 2.주문상품 목록
#### 3.유저의 보유 포인트 보여주기 (사용할 포인트 입력시 입력값 만큼 빠짐)
#### 4.보유 포인트 내에서 사용할 포인트 입력, 최대사용 버튼 클릭시 모두 사용
#### 5.결제하기 (주문목록 상품들 장바구니에서 제거, 포인트 업데이트)

<br>

---



## **마이페이지**
<br>

![img_13](https://github.com/0924ljm/Healing-Camp/assets/97243334/7965416f-2dc7-4e10-a1b8-90525f61519c)
![img_14](https://github.com/0924ljm/Healing-Camp/assets/97243334/b78f1662-e737-4732-8b07-5637bb0d00d5)
![img_15](https://github.com/0924ljm/Healing-Camp/assets/97243334/d8f47081-ce7a-4eb3-9bd4-2b615e67bec1)
![img_16](https://github.com/0924ljm/Healing-Camp/assets/97243334/ce855434-f42d-4490-9ac9-d08637475820)
#### 1.캠핑장 예약 내역 확인, 해당 캠핑장 리뷰작성 
#### 2.캠핑장 찜 목록 확인, 해당 캠핑장 찜 목록에서 삭제
#### 3.상품 찜 목록 확인, 해당 상품 찜 목록에서 삭제
#### 4.내가 작성한 리뷰 확인, 해당 리뷰 수정/삭제

<br>

---

