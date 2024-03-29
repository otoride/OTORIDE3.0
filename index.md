오토라이드 3.0 관리자 매뉴얼

# 시스템관리자

## 고객사관리 
### 신규 고객사를 등록하는 방법
>고객사관리 > 신규등록 

- 기본정보를 입력합니다.
	- 아래의 정보는 필수 입력값입니다. 
		* 고객사명
		* 주소

| 필드 | 설명  |
|--|--|
|OTORIDE ID  | 임의의 값을 입력하여 사용합니다. 오토라이드가 고객사를 식별하기 위한 고유값입니다.  |
| OTOPLUG CLIENT ID | 사전에 발급받은 값을 입력합니다. 오토플러그에서 고객사를 식별하기 위한 고유값입니다.  |
|OTOPLUG SECURITY CODE  | 사전에 발급받은 값을 입력합니다.  |
| PG사 | GMO를 선택합니다. |
|  PG 계정 |발급받은 값을 입력합니다.   |
| PG 인증키 | 발급받은 값을 입력합니다.  |
| 구글지도키 | 유효한 구글지도키를 입력합니다. |
| 서비스메뉴 | CS(카셰어링)를 선택합니다. (관제서비스(FMS),카셰어링서비스(CS), 영상관제서비스(DVR)) |
|메뉴구성  |  메뉴관리에서 사전에 구성한 메뉴 중 한가지를 선택합니다. |



- 계약 정보를 입력합니다. 
	- 신규로 등록하는 고객사의 비즈니스 타입을 선택합니다. 
	- Vehicle Type : 차량의 타입을 선택합니다.
	- Device Type : 디바이스 타입을 선택합니다.
	- 사용 ACC : 추가적으로 사용하는 악세사리를 선택합니다. 
	- 예약단위: 차량단위로 운영하는 고객사인지, 클래스단위로 운영하는 고객사인지 선택합니다. 

- 고객담당자 정보를 입력합니다. 

- 마스터ID 생성 
	- 등록하는 고객사의 슈퍼 관리자(마스터)의 ID를 등록합니다. 마스터ID는 중복되어선 안됩니다. 


## 메뉴관리

### 신규 메뉴셋을 등록하는 방법
> 메뉴관리 > ‘메뉴등록 ' 

 - 시스템 코드를 택일합니다. 
	 - CS : 카셰어링
	 - FMS : 차량관제
	 - DVR : 영상관제 
 - 카셰어링 새로운 메뉴셋을 구성하기 위해선 CS를 선택합니다. 
 - 기본적으로 모든 메뉴가 제공되는 형태로 표시됩니다. 
 - 사용/사용안함을 선택하여 고객사에게 선별적으로 메뉴를 제공할 수 있습니다. 

 
## DEVICE관리

### 신규 디바이스를 등록하는 방법
> DEVICE 관리 > ‘신규등록'

고객사가 차량을 등록하기 위해선 시스템관리자가 사전에 디바이스를 등록해줘야 합니다. 

 - 제원정보를 입력합니다.  
	 - 사용/비사용 : ‘사용’을 선택합니다. 추후에 디바이스를 사용하지 않는 경우엔 비사용으로 바꿀수있습니다. 
	 - 고객사 : 디바이스를 등록하려는 고객사를 입력합니다.  
	 - 주행거리 방식 : 단말이 차량으로부터 주행거리를 가져올 수 있는 경우에는 Device를 선택합니다. 가져오지 못하는 경우에는 GPS를 선택합니다.  
	 - 차대번호 : 차대번호를 입력합니다.
	 - Terminal ID: 차량의 단말이 통신하기 위한 고유 코드로서 사전에 발급받은 값을 입력합니다. 
	 - Fuel Type: 연료타입을 선택합니다. 연료타입은 공통코드에서 관리할 수 있습니다.  
	 - 초기주행거리 : 주행거리방식을 GPS를 선택한 경우 초기주행거리 값을 입력해줍니다. Device를 선택한 경우에는 입력하지 않아도 됩니다.

 
- Device 정보를 입력합니다. 
	- Device 기종 : CS를 선택합니다.
	- 그 외의 정보는 필수입력이 아니며, 관리차원에서 입력하여 활용하시기 바랍니다. 

- 디바이스가 성공적으로 등록된 경우에는 고객사의 차량관리 페이지에 리스트업 됩니다.

## 공통코드 관리 
### 공통코드를 추가하는 방법 

오토라이드 시스템 내에서 유동적으로 값을 추가하거나 수정/삭제 할 수 있도록 코드형태로 관리되는 데이터가 있습니다.

*면허종류/
FAQ 종류/
DEVICE 종류 /
악세사리 /
PC사 /
연료타입/
변속기/
차량상태/
메뉴 프리셋/
1:1문의 상태/
계약 종류/
메뉴구성/
국가 종류*	

그 외의 코드를 추가적으로 등록하여 활용할 수 있습니다. 

## 랜드마크관리
### 랜드마크를 추가하는 방법
- 시스템관리자가 랜드마크를 등록하여 고객사의 지점과 맵핑할 수 있습니다.
- 랜드마크관리 > 신규등록을 클릭합니다. 
- 랜드마크명을 입력합니다. 
- 입력한 랜드마크에 맵핑하고자 하는 지점을 선택할 수 있습니다. 


## 공휴일관리 
### 공휴일을 추가하는 방법
- 구글캘린더에서 공휴일 정보 가져오기 
- 좌측 아래에 ‘ 캘린더 불러오기’를 클릭합니다. 
- 기본적으로 구글캘린더로부터 일본의 기본 공휴일 정보를 가져올 수 있습니다. 
- 수정한 공휴일 정보는 고객사 운영관리자의 페이지에 즉시 반영됩니다. 
- ‘삭제’를 클릭하여 특정 공휴일을 삭제할 수 있습니다. 
- ‘신규등록’을 클릭하여 공휴일을 추가할 수 있습니다. 


## FAQ관리
고객사들의 시스템 사용을 돕기 위해 FAQ를 만들어서 제공할 수 있습니다. 이곳에서 등록한 FAQ는 운영관리자가 우측 상단의 물음표(?) 버튼을 눌러서 확인합니다. 

### 신규 FAQ를 등록하는 방법 

- 카테고리관리 : 카테고리를 등록할 수 있습니다.
- 신규등록을 클릭합니다. 
- 카테고리를 선택합니다. 
- 제목과 내용을 입력하고 ‘등록’을 클릭합니다. 

# CS 운영관리자 매뉴얼 

## 시스템 초기 세팅 가이드
*오토라이드 CS 시스템을 사용하기 위해서는 초기 세팅이 필요합니다.  
차량 예약을 위한 준비: **차량 등록 -->  결제 세팅--> 앱정보 세팅** * 

## 카셰어링 시스템 공통 정책

1. 회원 자격
	- 만21세 이상 

2. 운전 자격
	- 운전면허 취득 1년 이후 이용 가능 (취득 1년 미만의 운전면허증이더라도 시스템에 등록할 수는 있으며, 운전면허증을 관리자가 승인해주면 차량 예약이 가능합니다.) 

3. 회원의 구분 
	- 법인회원: 법인 소속으로 업무용으로 차량을 이용하는 회원 (법인관리자가 등록한한 법인카드로 요금 결제)
	- 개인회원: 법인 소속으로 개인용으로 차량을 이용하는 회원 (개인이 요금 결제)
	- 일반회원: 법인회원과 개인회원을 제외한 모든 회원

4. 이용조건 
	- 일반회원 : 가입 후 관리자의 면허승인과 결제카드 등록이 필요
	- 법인회원 : 가입 후 관리자의 회원승인과 면허승인이 필요
	- 개인회원 : 가입 후 관리자의 회원승인, 면허승인과 결제카드 등록이 필요

5. 차량 예약
	- 예약 시간 단위 : 10분
	- 최소 예약 시간 : 30분
	- 최대 예약 시간 : 30일 (720시간)
	- 최대 예약 가능한 미래 일자 : 대여종료일 기준 1년 후
	- 현재 시간의 이후로만 차량 예약 가능
		- 차량 검색시점 기준 5분 이후의 차량 예약 가능(10분 단위)
		-조회일시가 9:33경우, 9:40 이후 예약 가능한 차량이 조회
		-조회일시가 9:37경우, 9:50 이후 예약 가능한 차량이 조회
	- 두 예약 건 사이의 최소 간격은 20분
		-9:00까지 예약된 차량은 14:20부터 예약 가능
		-반납처리 유예시간 10분 + 다음 사용자의 예약 시간 확보하기 위한 10분
	- 반납 완료 차량은 바로 예약이 가능한 상태로 전환 (예약 유효성검사 프로세스와 동일)
		-14:21 에 반납완료된 차량은 14:30부터 예약 가능
		-14:26 에 반납완료된 차량은 14:40부터 예약 가능

6. 예약 변경
	- 변경 가능 : 시간변경, 보험, 옵션 변경만 가능 
	- 예약 변경시, 기존 결제 취소 이후 새 결제 진행
	- 변경 불가 : 차량 (차량을 변경하는 경우에는 예약을 취소) 

7. 예약 취소
	- 이용시작시간 전 취소 가능
	: 이용시작시간 전이더라도 차량제어를 시작했다면 취소 불가 (스마트키 이용시작 버튼 누른 시점)

8. 요금 결제 시점
	- 대여요금: 사용자 예약 완료 시점에 결제가 동시에 진행 (결제 실패 시 차량 예약이 되지 않습니다)
	- 주행요금: 반납 완료 후 10분 이내 자동 결제
	- 연장요금: 대여중 대여종료시간을 연장한 경우, 반납 완료 후 주행요금과 함께 자동 결제
	- 예약취소수수료: 예약취소를 시도한 시점에 자동 결제
	- 추가과금: 패널티, 범칙금, 실패한 결제건 등에 대해서 관리자가 수동으로 결제 시도

9. 차량의 제어
	- 이용 시작시간 5분전 부터 차량 제어가능
	- 사용자가 차량을 반납하면 차량 제어 불가능
	- 반납이 지연되더라도 스마트키 제어 가능

10. 차량 반납 조건
	- 차량시동 OFF, 도어락, 미등OFF
	- 지정된 반납 위치에 주차 (관리자 설정시에만)
	- 전기차의 경우 충전플러그에 연결되어 있어야 한다. 
	- 키박스가 연결되어져 있는 경우 키박스가 ‘반납’상태로 되어 있어야 한다. 


# 차량 등록 하기
차량을 등록하기 위해서는 아래 항목의 사전등록이 완료되어야 합니다. 
- **단말기등록, 구역등록 , 지점등록, 모델등록**
- 단말기등록은 차량에 단말기장착이 완료되면 시스템관리자에서 진행합니다.

## 차량관리
### 신규 차량을 등록하는 방법

> 차량관리 > 차량관리 > ‘신규등록’ 클릭

차량에  단말기가  장착이  완료되고  시스템  관리자가  단말기와  차대번호를  맵핑하여  사전에  등록을  합니다. 단말기  장착이  완료된  차량만  등록이  가능하며, 단말기  등록이  완료되었지만  아직  등록하지  않은  차량은  차대번호를  눌러서  확인할  수  있습니다.

-   차량  정보  입력
차량정보에  입력한  정보는  모바일앱 > 차량상세정보에  표시되는  내용을  포함하고  있습니다.
앱에  표시되는  정보 : 제조사, 모델, 연식, 변속기, 색상, 승차정원, 유류타입, 차량이미지
	-   클래스: 예약  단위가  클래스인경우, 차량이  속할  클래스를  선택합니다.
	-   차량알림: 차량에  발생하는  알림을  관리자에게  발송할지  선택합니다.
	-   차대번호: 차량의  고유값으로, 단말기  등록이  완료된후  자동으로  리스트업  됩니다.
	-   차량번호: 단말기  장착이  완료된  차량의  경우  자동으로  리스트가  제공됩니다.
	-   차량구분: 정상, 정비, 사고, 매각, 기타  중에  선택합니다. 정상인  경우에만  서비스  운영에  활용할  수  있습니다.
	-   제조사, 모델명: 사전에  차량관리>모델관리에서  등록한  모델을  선택합니다.
	-   초기주행거리: 단말기가  차량에서  자동으로  불러오는  정보입니다.
	-   이미지: 앱에  표시되는  차량  이미지로  미등록  시  기본  이미지를  제공합니다.
	-   전기차  여부 : 차량이  전기차이지  아닌지  선택합니다.
	-   저전압경고: 저전압  경고  알림을  받을  기준치를  등록합니다. 차량의  전압이  입력한  하한선  수치로  내려갔을  때  알림이  발송되며, 상한선  이상으로  다시  올라왔을  때  알림  발송  해제됩니다.

-   차량  장비  입력
	-   입력한  정보는  모바일앱 > 차량상세정보에  표시됩니다.
	-   차량에  장착되어  있는  장비를  입력합니다.
	-   EX) 에어백, 후방감지센서, 운전보조장치, 블랙박스, 열선시트  등

-   정보  입력
	-   차량은  반드시  하나의  지점에  소속되어  있어야  합니다.
	-   사전에  지점관리에서  등록한  지점  중에  선택이  가능합니다.
	-   새로운  구역을  추가하고  싶으면  지점관리 > [구역관리](#구역관리)  에서  등록해주세요.
	-   새로운  지점을  추가하고  싶으면  지점관리 > [지점관리](#지점관리)  에서  등록해주세요.

-   요금제정보
	-   차량의  요금제를  선택합니다.
	-   등록시에  선택하지  않고  추후에  선택할  수  있습니다.
	-   ‘상세확인’을  눌러서  요금제의  상세  정보를  확인할  수  있습니다.

-   옵션정보
	-   차량에  보험상품과  옵션상품을  추가하는  방법
	-   차량에  추가하여  판매할  보험상품과  옵션상품을  지정할  수  있습니다.
	-   보험과  옵션  등록시 ‘필수’로  지정된  경우에는  차량에서  판매를  해제할  수  없습니다.
	-   옵션정보에  추가된  정보는  유저앱에서  차량  예약시  표시됩니다.

-   이용  정보
	-   특정  법인  소속  회원에게만  차량을  보이게  하는  방법
	-   이용대상을  선택합니다. 법인차량  선택시, 선택한  법인회원들만  이용  가능합니다.
	-   복수의  법인이  이용하는  차량의  경우에는 ‘법인추가’를  클릭해  추가할  수  있습니다.
	-   일반차량을  선택하면, 일반회원에게만  차량이  표시됩니다.

-   취소정보
	-   차량  예약시에  적용할  취소  정책을  선택합니다.

-   단말기  정보
	-   차량에  장착된  단말기  정보로서  선택한  차대번호  에  따라  자동으로  입력됩니다.

-   보험  정보

	-   차량이  가입되어있는  보험을  선택합니다.
	-   사전에  보험관리에서  등록한  보험  중에  선택이  가능하며, 선택시  보험정보가  자동으로  표시됩니다.

-   주유카드  정보

	-   차량  내  비치된  주유  카드정보를  등록하여  관리합니다.

-   사용/비사용

	-   차량을  서비스에서  제외하고  싶은  경우 ‘비사용’을  선택합니다.
	-   차량을  비사용으로  선택시  서비스  운영에  이용할  수  없습니다


### 차량을  일괄로  등록하는  방법

> 차량관리 > 차량관리 > ‘차량일괄등록’ 클릭

엑셀  파일을  업로드해서  차량을  일괄로  등록할  수  있습니다.

-   엑셀  양식  다운로드
-   엑셀  파일  작성
-   다운받은  양식에  맞춰  정보를  입력합니다.
-   ‘찾아보기’로  파일을  선택한  후 ‘업로드’ 클릭하여  업로드합니다.

## 클래스  관리

### 클래스를  등록하는  방법

클래스  관리는  클래스  단위로  차량  예약을  받는  경우  사용하는  메뉴입니다.

-   클래스  정보  입력
	-   클래스명, 클래스설명, 이미지는  모바일앱에서  클래스  상세  정보에  표시되는  내용입니다.

-   지점  정보  선택

	-   클래스를  표시할  구역과  지점을  선택합니다.
	-   전체구역과  전체지점  선택  시, 모든  지점에서  해당  클래스를  예약할  수  있습니다.
	-   클래스를  등록할  때  선택한  구역과  지점은  변경할  수  없습니다.
	-   선택한  지점에  따라  선택할  수  있는  요금제, 보험, 옵션  등이  달라집니다.

-   차량정보

	-   차량  정보를  입력합니다. 입력한  정보 (제조사,모델명, 색상, 변속기, 유류타입, 승차정원)는  모두  모바일앱의  클래스  상세정보에  표시됩니다.

-   차량장비

	-   입력한  정보는  모바일앱 > 클래스상세정보에  표시됩니다.
	-   차량에  장착되어  있는  장비를  입력합니다.
	-   EX) 에어백, 후방감지센서, 운전보조장치, 블랙박스, 열선시트  등

-   요금제  정보  선택

	-   클래스에  적용할  요금제를  선택합니다.
	-   요금제를  아직  만들지  않은  경우  나중에  선택할  수  있습니다.

-   옵션  정보  선택

	-   클래스에  판매할  옵션과  보험을  선택합니다.
	-   차량에  추가하여  판매할  보험상품과  옵션상품을  지정할  수  있습니다.
	-   보험과  옵션  등록시 ‘필수’로  지정된  경우에는  차량에서  판매를  해제할  수  없습니다.
	-   옵션정보에  추가된  정보는  유저앱에서  차량  예약시  표시됩니다.

-   차량  등록

	-   해당  클래스에  속하는  차량을  선택합니다.
	-   사용자가  클래스를  예약시  선택한  차량들  중에서  임의로  배정이  되며, 나중에  수동으로  차량을  변경할  수  있습니다.
	-   클래스에  맵핑된  차량을  수정하는  방법
	-   클래스에  등록하고  싶으면  체크박스에  체크를  한  후에  오른쪽  화살표를  클릭하여  우측으로  이동시킵니다. 해당  클래스에  맵핑된  차량을  해제  하고  싶으면  우측의  리스트에서  삭제를  선택합니다.

### 클래스를  삭제하는  방법

> 차량관리 > 클래스관리 > 클래스를  선택 > 클래스상세

- 페이지  하단  좌측에 ‘삭제’버튼을  누릅니다.

## 옵션관리

보험과  옵션을  등록하여  차량을  예약하는  사용자에게  판매할  수  있습니다.

### 옵션을  등록하는  방법

> 운영관리 > 옵션관리 > ‘신규등록’ 을  클릭합니다.

-   기본정보

	-   옵션구분: ‘상품’에  체크합니다.
	-   필수/선택: 등록하는  옵션을  모든  차량  전체에  필수로  판매할지  선택합니다. 필수인  경우  차량의  옵션에서  삭제가  불가능하고, 선택인  경우에는  차량  옵션  등록시  삭제가  가능합니다.
	-   본사관리자가 ‘필수’로  등록한  옵션은  구역이나  지점의  관리자가  삭제할  수  없습니다.
	-   보유개수 : 보유하고  있는  옵션의  개수를  입력합니다
	-   최대선택개수 : 사용자가  예약할  때  최대  선택할  수  있는  옵션의  개수를  입력합니다.
	-   업로드한  이미지는  사용자  앱의  옵션상세정보에  표시됩니다.

-   판매기간
	-   판매  시작일과  판매  종료일을  입력하면  해당  기간  내에만  옵션이  표시됩니다.
	-   판매기간  중이더라도 ‘중지’를  클릭하면  옵션이  표시되지  않습니다

-   요금정보
	-   일요금제: 일단위  과금  방식
	-   일  요금제일  경우, 양  일에  걸쳐  대여한  시간이  연속 6시간  초과  시 2일  요금으로  과금됩니다.
	-   시간요금제: 시간당  과금  방식
	-   최대요금: 사용자가  옵션  대여시  입력한  금액을  초과하지  않습니다.
-   조정요금
	- 입력한  누적대여일  이상  대여시  할인되는  요금입니다. 1일은 24시간입니다.
	- 누적대여일:3, 할인요금: 10,000원  입력하면, 3일이상(72시간) 대여시  전체금액에서 10,000원을  할인해줍니다.

-   지점정보
	-   옵션을  판매할  지점을  선택합니다.
	-   전체구역/전체지점 : 모든  지점에서  판매

### 보험을  등록하는  방법

> 운영관리 > 옵션관리 > ‘신규등록’

-   기본정보

	-   보험을  등록하는  방법은  옵션을  등록하는  방법과  동일하며  옵션구분에서  보험을  선택하면  됩니다.
	-   옵션구분: ‘보험’에  체크합니다.
	-   약관  추가 : 약관  추가를  클릭하여  약관을  입력할  수  있으며  입력한  약관의  내용은  사용자  앱의  보험은  상세정보에  표시됩니다. 보험별로  약관은  하나만  추가  가능합니다.

## 구역관리

> 지점관리 > 구역관리

구역은  지점을  관리하는  상위  그룹  체계로, 지점을  등록하기  위해서는  반드시 1개  이상의  구역의  등록되어져  있어야  합니다.

### 구역을  등록하는  방법
-   ‘구역추가’를  클릭하면  빈  필드가  생성됩니다.
-   필드에  구역명을  입력하고  저장을  누릅니다.

### 구역을  삭제하는  방법
-   구역을  삭제하기  위해서는  해당  구역에  연결되어  있는  지점이  없어야  합니다.
-   연결된  지점이  없는  구역을  먼저 ‘비사용’처리  합니다.
-   비사용처리를  하면  사이트에  표시되지  않습니다.
-   ‘삭제’를  클릭해  구역을  삭제하고 ‘저장’을  누릅니다.

## 지점관리

지점은  차량  등록  시  필수로  입력되어져야  하는  정보로, 반드시 1개  이상의  지점을  등록해야  합니다. 지점을  등록하기  위해서는  반드시  하나  이상의  구역이  만들어져  있어야  합니다. ‘ (지점관리 > 구역관리) ’

### 지점을  등록하는  방법

> 지점  관리 > 지점  관리 > 신규등록

-   지점정보  입력
	-   구역명: 지점의  상위  분류  개념 (내부적으로  사용하는  용어로  변경  가능합니다.)
	-   지점코드: 지점코드는  영문과  숫자를  사용하여  임의로  입력합니다.
	-   대표자명, 연락처: 해당  지점의  현장관리  대표자의  정보를  입력합니다.
	-   이벤트 SMS 수신 : 정비, 이벤트, 도난의심  등에  따른  문자  알림을  수신  받는  여부를  선택합니다. Y로  체크하면  해당지점의  관리자  전원에게  알림을  발송합니다.
	-   개점일시와  폐점일시: 개점일시와  폐점일시  내에만  사용자가  차량을  예약할  수  있습니다.
	
-   관리자  정보  입력
	-   해당  지점의  관리자를  최대 10명까지  추가  가능합니다.
	-   관리자  개별 SMS 알림수신  여부를  선택합니다.
	
-   위치  정보  입력
	-   상세주소를  입력하면  지도에  핀이  표시됩니다.
	-   지점의  주소를  입력한  후  위도/경도의  필드를  클릭하면  입력한  주소의  위경도가  자동으로  입력되고, 지도상에  핀이  표시됩니다.
	-   반납거리: 사용자가  차량  반납시  반납  처리의  기준이  되는  거리로, 입력한  거리에  들어와야만  차량이  반납됩니다.
	-   도난알림  거리: 차량이  운영시간  외에  해당지점의  위경도를  중심으로  일정  거리  이상  벗어났을  경우  알림이  발송되는  되는  기준입니다.
	-   주행영역  거리: 차량이  운영시간  중  일정  거리  이상을  이탈해  주행했을  경우  알림이  발송되는  기준입니다.
	
-   주차장  위치 (선택입력)
	-   차량이  특정  위치에  주차되어  있는  경우  입력합니다.
	-   이  필드를  입력할  경우, 사용자가  모바일앱에서  차량을  반납할  때  주차위치를  선택할  수  있습니다.
	
-   추가정보
	-   유저앱 > 메인지도(예약하기) > 지점  선택 > 지점상세정보에서  표시되는  내용입니다.
	-   지점 1곳당 URL 1개를  등록할  수  있습니다.(선택)
	-   URL은  반드시 http:// 또는 https://를  포함하여  입력해야  합니다.
	-   사용자가  모바일앱에서 URL을  클릭하면  브라우저가  열리고  페이지로  이동합니다.
	-   ‘설명&이미지’를  추가하여  지점에  대한  상세  정보를  자유롭게  입력할  수  있습니다.
	
-   랜드마크정보
	-   지점과  연결되어  있는  랜드마크가  표시됩니다.
	-   지점의  랜드마크를  연결하는  것은  랜드마크관리에서  해주세요.

### 예약  알림  발송  주기를  관리하는  방법

지점의  예약알림발송을  관리하기  위해선  지점의  신규등록을  완료하고  나서  지점상세  화면으로  진입해야합니다.

> 지점관리 > 지점관리 > 지점  선택 > 지점상세화면  하단의 ‘예약알림관리’ 클릭

-   차량을  예약한  사용자에게  배차  알림을  수동/자동  으로  보낼지  선택합니다.
-   설정된  발송  주기에  따라  예약  회원에게  배차알림  메일을  자동발송합니다.
-   발송주기보다  짧은  시간  내  예약시, 예약완료  시점에  바로  발송합니다.

### 지점별  운영시간을  관리하는  방법

-   지점의  운영시간을  관리하기  위해선  지점의  신규등록을  완료하고  나서  지점상세  화면으로  진입해야합니다.	

> 지점관리 > 지점관리 > 지점  선택 > 지점상세화면  하단의 ‘운영시간관리’ 클릭

-   유저앱 > 메인지도(예약하기) > 지점  선택 > 지점상세정보에서  표시되는  내용입니다.
-   지점에  소속되어  있는  차량은  운영시간에만  차량을  대여할  수  있습니다.
-   운영시간  외의  차량은  차량  검색시  표시되지  않습니다.

### 지점별  영업일을  관리하는  방법

지점의  영업일을  관리하기  위해선  지점의  신규등록을  완료하고  나서  지점상세  화면으로  진입해야합니다.

> 지점관리 > 지점관리 > 지점  선택 > 지점상세화면  하단의 ‘영업일관리’ 클릭

-   지점별로  영업일을  관리할  수  있습니다.
-   기본적으로  모든  날짜가  영업일로  지정되어  있습니다. (영업일  핑크색)
-   월달력에서  일자별로  클릭해서  영업일<>비영업일  전환합니다.
-   전체/평일/주말공휴일  선택  후, 영업일/비영업일  선택하고 ‘적용’을  클릭하면  선택된  조건대로  일괄  적용됩니다.
-   ex) 평일  선택 & 영업일  선택  후 ‘적용’ 클릭 → 팝업에  보이는  월달력의  모든  평일을  영업일로  적용
-   영업일  지정이  끝났으면 ‘저장하기’를  누릅니다.

## 모델관리

### 차량의  모델을  등록하는  방법
모델은  차량  등록  시  필수로  입력되어져야  하는  정보로, 반드시 1개  이상의  모델을  등록해야  합니다.
> 운영관리 > 모델관리

-   차량  모델  별로  저전압  발생  및  해제  값을  입력합니다.
-   입력된  값을  기준으로  관리자에게 ‘저전압  경고’알림이  발송됩니다.
-   저전압  경고  알림  기능을  사용하지  않는  경우, 모두 0으로  입력합니다.

## 랜드마크  관리

시스템에  등록된  여러지점을  랜드마크로  묶어서  관리하면  사용자가  랜드마크로  지점을  쉽게  검색할  수  있습니다.

### 랜드마크를  등록하는  방법

> 지점관리 > 랜드마크  관리 > ‘신규등록’

-   랜드마크명을  입력합니다.
-   ‘지점추가’를  클릭해서  랜드마크에  연결할  지점을  추가합니다.
-   복수의  지점을  추가할  수  있습니다.

# 결제  세팅하기

## 요금제관리

### 요금제를  등록하는  방법

> 정산관리 > 요금제관리 > ‘신규등록’

하나의  요금제를  만들어서  여러  차량에  등록할  수  있습니다.

-   요금제  정보  입력
	-   요금제명을  입력합니다.
	-   구역명을  선택합니다.
	-   지점명을  선택합니다.

-   요금제  설정

	-   회원유형별로  다르게  요금제를  적용하는  방법
	-   각  회원  타입의  맞춰서  각각의  요금제를  설정할  수  있습니다. (일반회원/개인회원/법인회원)
	-   만약  어떤  차량이  일반  회원만  이용  할  수  있는  일반차량인  경우  나면은  일반회원의  요금제만  입력합니다. 법인  소속  회원만  이용할  수  있는  법인차량  이라면  개인회원과  법인  회원의  요금을  입력합니다. 모든  회원이  이용할  수  있는  차량이라면  모든  회원의  요금제를  각각  입력합니다.
	-   요금제  적용시작일을  선택합니다. 요금제의  적용시작일  이후에  있는  경우에만  차량의  예약이  가능합니다.
	-   1km 주행  당  주행요금을  입력합니다.
	-   등록하는  요금제가  고정요금제인지  변동요금제인지  선택합니다.
	-   사용/비사용 : 등록한  요금제를  사용하지  않는  경우에는  사용을  체크합니다.


#### 고정요금제  적용하기
고정요금제는  하나의  차량에  단일  대여요금을  적용하는  요금제입니다.
-   요금타입  중에서 ‘고정’에  체크합니다.
-   대여요금(10분)을  입력합니다. 입력한  대여  요금은  일자에  관계없이  모두  똑같이  적용됩니다.	
-   누적일에  따른  할인을  적용하기  위해 ‘조정요금’을  추가할  수  있습니다.
-   입력한  누적대여일  이상  대여시  할인되는  요금입니다. 1일은 24시간입니다.
	-   ex) 누적대여일:3, 할인요금: 10,000원  입력하면, 3일이상(72시간) 대여시  전체금액에서 10,000원을  할인해줍니다.

#### 변동요금제  적용하기
  변동요금제는  일단위로  다른  대여요금을  적용하는  요금제입니다.
-   변동요금제를  등록하는  방법은  기간  적용과  개별적용  두  가지  방법이  있습니다.
-   기간적용은  달력에서  시작일과  종료일을  정해서  지정한  기간에  요금을  적용  할  수  있습니다.
-   개별적용은  달력에서  원하는  날짜를  개별적으로  체크하여  대여  요금을  등록하는  방법입니다.

## 요금관리

요금제관리에서  생성한  요금제를  차량에  맵핑하는  단계입니다.
신규등록: 요금제 1개를  차량 1대에  등록합니다.
일괄등록: 요금제 1개를  여러대의  차량에  등록합니다.

### 요금제를  차량에  맵핑하는  방법

> 정산관리 > 요금관리 > 신규등록  클릭

-   구역과  지점  선택: 요금제를  등록할  차량의  지점을  선택합니다.
-   차량번호  선택: 요금제를  등록한  차량  번호를  선택합니다.
-   요금제명  선택: 등록할  요금제를  선택합니다.
-   차량관리의  각  차량  상세정보  페이지에서도  차량의  요금제를  변경할  수  있습니다.

### 요금제를  여러개의  차량에  한번에  맵핑하는  방법

> 정산관리 > 요금관리 > 일괄등록  클릭

-   구역과  지점  선택: 요금제를  등록할  차량의  지점을  선택합니다. 선택한  구역과  지점에  따라  아래  차량등록  리스트에  차량이  표시됩니다.
-   요금제명  선택: 등록할  요금제를  선택합니다.
-   차량등록: 좌측  차량리스트에서  요금제르  등록할  차량의  체크박스에  체크하고, ‘>’ 버튼을  눌러  우측  선택차량으로  이동시킵니다.
-   좌측의  차량  리스트에는  요금제가  맵핑  되지  않은  차량만  표시됩니다.
-   저장을  누릅니다.

## 취소정책관리

사용자가  차량  예약을  취소할  경우  발생하는  취소수수료를  책정하고  차량별로  취소  정책을  관리할  수  있습니다.

### 취소  정책을  등록하는  방법

> 정산관리 > 취소  정책  관리> 신규  등록

-   정책명을  입력합니다.
#### 차량별로  취소  정책을  지정하는  방법
-   개별과  기본  중에서  택일  합니다. 기본은  한  개만  등록할  수  있습니다.
-   개별은  차량  각각  별로  적용할  수  있는  취소  정책이며, 개별취소  정책이  적용되지  않은  차량은  모두  기본  취소  정책에  따르게  됩니다.
-   최저  취소  요금은  취소금액  계산  결과가  입력한  값보다  적을  경우, 입력한  금액을  취소수수료로  적용하는  값입니다.
-   적용  시작일을  선택합니다. 취소  정책을  적용하기  위해서는  예약  건이  반드시  적용  시작일  이후에  있어야  합니다.
-   생성된  취소  정책은  차량관리  각각  차량상세정보  페이지에서  적용할  수  있습니다.

아래는  입력  예시입니다.
*대여시작 5시간전~ 대여시작전에  취소하면 20%,
10시간전 ~ 5시간전에  취소하면 10%
10시간  이전에  취소하면  취소수수료가  없다는  뜻입니다.
1번째  행의  취소  요금  계산  결과 9,900원일  때, 입력값 10,000을  취소  요금으로  적용합니다.* 

## 쿠폰관리

### 신규  쿠폰을  등록하는  방법

> 정산관리 > 쿠폰  관리 > 신규  등록

쿠폰  관리에서는  신규  쿠폰  정책을  등록하여  유저에게  조건과  기간에  따라  쿠폰을  발급할  수  있습니다.

-   쿠폰  명을  입력합니다.
-   발급  기간을  선택합니다. 발급  기간  내에만  쿠폰이  발급됩니다.
-   쿠폰의  설명을  입력합니다.
-   쿠폰을  등록하고  나서  단  한  사람에게라도  쿠폰이  발급된  경우에는  쿠폰의  내용을  수정할  수  없습니다.

### 신규가입회원에게  쿠폰을  발급하는  방법

-   발급  조건에서  신규가입을  선택합니다.
-   할인조건을  택일  합니다
-   할인  단위를  입력합니다.
-   쿠폰을  사용할  수  있는  최소결제금액을  입력합니다.
-   쿠폰  유효기간을  입력합니다.

### 예약자  모두에게  쿠폰을  발급하는  방법

-   발급  조건에서  예약  결제를  입력합니다.
-   할인조건을  택일합니다.
-   할인  단위를  입력합니다.
-   쿠폰을  사용할  수  있는  최소결제금액을  입력합니다. 거기  아니야
-   유효  기간을  입력합니다.

### 쿠폰의  발급을  중지하는  방법

-   발급  기간  이내더라도  쿠폰에  발급을  중지할  수  있습니다.
-   발급을  중지  하고  싶은  쿠폰을  클릭하여  쿠폰  상세  페이지에  이동합니다.
-   페이지  하단의  발급  중지를  선택하고  수정을  클릭합니다.

### 쿠폰  발급/사용  내역을  조회하는  방법

-   정산관리 > 쿠폰조회  에서  유저에게  발급된  전체쿠폰  내역과  쿠폰  사용  내역을  확인할  수  있습니다.

## 포인트관리

### 포인트  적립  정책을  등록하는  방법

> 정산관리 > 포인트  정책  관리

포인트정책  관리에는  크게  기본  설정과  기간별  설정이  있습니다. 기본  설정은  포인트  적립  정책으로  기본이  되는  기준입니다.

#### 포인트  기본  적립  정책  설정하는  방법

-   적립  비율에  입력한  비율대로  모든  회원에게  포인트가  적립됩니다.
-   최소  결제  금액은  포인트를  사용할  수  있는  최소  결제  금액입니다.
-   최소  사용  포인트를  설정할  수  있습니다.

#### 기간에  따라  포인트  적립  비율을  다르게  설정하는  방법

-   기간별  설정  우측  하단의 ‘ 설정  추가’를  클릭합니다.
-   포인트  적립  비율을  다르게  설정  하고  싶은  시작일과  종료일을  선택합니다. 선택한  기간  내에  포인트  적립  비율을  입력합니다.
-   기간별로  다르게  설정한  포인트  적립  비율을  삭제  하고  싶으면  우측의  삭제  버튼을  클릭합니다.

### 포인트  적립/사용  내역을  조회하는  방법

> 정산관리 > 사용  포인트  조회 
- 유저에게  적립된  전체  포인트  내역과  사용  내역을  확인할  수  있습니다.	



# 유저앱  기본  세팅하기

## 기업정보관리

### 유저앱에  표시되는  기본적인  정보들을  관리하는  방법

서비스명과  서비스로고를  등록하기, 사업장  주소  및  고객센터  등록, 소수점  처리  정책을  관리할  수  있습니다.

-   기업정보

	-   유저앱에  표시되는  서비스의  기본적인  정보들을  기입해주세요.
	-   서비스명과  서비스  로고를  등록하는  방법
	-   서비스명 : 입력한  서비스  명은  사용자에게  발송되는  알림에  표시됩니다.
	-   서비스로고 : 서비스로고를  규격에  맞게  등록합니다. 등록한  서비스  로고는  유저앱  맨  상단에  표시됩니다.
	-   지도의  기본  위치를  설정하는  방법
	-   사업장  주소 : 입력한  사업장  주소는  사용자가  유저  앱에서  위치  정보  제공을  동의하지  않은  경우  지도에  기본  위치로  표시됩니다.
	-   고객센터  전화  번호를  수정하는  방법
	-   사고접수  전화번호 : 스마트키의  사고접수  화면에  표시됩니다.
	-   고객센터  운영시간/전화번호 : 고객센터  전화번호는  서비스  운영회사  단위로  관리됩니다.
	-   면허  승인대기  일수를  수정하는  방법
	-   면허  승인대기일 : 사용자가  면허를  등록하거나  수정할경우  표시되는  승인까지  소요되는  기간입니다.

-   과금정책관리

	-   소수점  이하  자리의  숫자를  처리하는  방법
	-   시스템  내에서  비율에  따라  금액이  계산되는  부분은  취소정책  수수료와  포인트  적립 2가지가  있습니다.
	-   2가지  각각에  대하여  소수점이하  자리의  숫자를  어떻게  처리할지에  대한  반올림  정책을  결정할  수  있습니다.

### 이용가이드에  글을  등록하는  방법

> 기업정보관리 > 추가  정보  영역

-   추가  정보  영역에  글을  등록하면  사용자앱의  이용가이드에  표시됩니다.



## 배너  관리

유저앱에  표시되는  커스텀  이미지를  관리합니다.
각  이미지는  규격에  맞게  업로드  해주세요.

### Splash 배너를  수정하는  방법

-   이미지  규격 (1440*2560px)에  맞는  이미지를  준비합니다.
-   이미지를  업로드  합니다.
-   비사용을  선택하면  기본  이미지가  표시됩니다.

### 로그인  배너를  수정하는  방법

-   이미지  규격 (1440*800px)에  맞는  이미지를  준비합니다.
-   이미지를  업로드  합니다.
-   비사용을  선택하면  기본  이미지가  표시됩니다.

### 패널티  정보를  수정하는  방법

-   이미지  규격 (가로 1440px)에  맞는  이미지를  준비합니다.
-   이미지를  업로드  합니다.
-   비사용을  선택하면  기본  이미지가  표시됩니다.

### 차량  반납  조건을  수정하는  방법

-   이미지  규격 (가로 1440px)에  맞는  이미지를  준비합니다.
-   이미지를  업로드  합니다.
-   비사용을  선택하면  기본  이미지가  표시됩니다.

## 알림메일  관리

### 사용자에게  발송되는  알림을  수정하는  방법

-   알림메일  관리에서는  상황에  따라  사용자에게  발송되는  알림을  관리할  수  있습니다.
-   이메일과  스마트폰  푸시알림  두가지가  제공됩니다.
-   기본  내용이  제공되며  입력안내의  각  필드를  활용해  내용을  수정할  수  있습니다

## 약관관리

유저앱에서  표시되는  약관들을  관리합니다. 유저앱의  아래  각  단계(화면)에서  약관이  표시됩니다.

1.  회원가입: 유저  회원가입시  동의가  필요한  약관. 다중  등록  가능.
2.  탈퇴: 유저의  서비스  탈퇴  시  동의가  필요한  약관. 하나만  등록  가능
3.  환경설정 : 환경설정  약관이  표시되는  약관. 다중  등록  가능.
4.  대여: 유저가  차량을  대여할  때마다  반드시  동의해야하는  약관. 하나만  등록  가능

-   기본정보를  입력합니다.

	-   약관유형 : 약관  동의의  필수/선택  여부를  선택합니다.
	-   화면타입선택 : 회원가입/탈퇴/대여/환경설정  중  택일합니다. 탈퇴와  대여  약관은  하나만  등록  가능합니다.
	-   동의조건 : 약관  동의  시, 약관  내용의  확인  여부를  선택합니다. ‘내용  확인’을  선택하면  유저는  약관의  내용을  읽고  하단의 ‘확인’버튼을  눌러야만  약관에  동의할  수  있습니다.

-   약관  이력  관리

	-   약관이  개정되는  경우 ‘약관  추가’ 버튼을  눌러  계속적으로  약관을  등록할  수  있으며, 등록시마다  적용일을  선택할  수  있습니다.


## FAQ관리

유저앱>마이페이지>FAQ에  표시되는  질문들을  관리합니다.

### 신규 FAQ를  등록하는  방법

> 게시판관리 > FAQ관리 > 신규등록

-   ‘신규등록’을  클릭합니다.
-   카테고리를  선택합니다.
-   제목과  내용을  입력하고 ‘등록’을  클릭합니다.
-   대표 FAQ로  지정하면 FAQ의  메인페이지에  표시됩니다.

### FAQ 카테고리를  등록하는  방법

-   FAQ를  신규등록  하기전 ‘카테고리관리’에서 FAQ의  카테고리를  추가합니다.
-   ‘카테고리  추가’를  클릭하면  빈  필드가  생성됩니다.
-   해당  필드에  카테고리명을  입력하고 ‘저장’을  누릅니다.

### FAQ를  삭제하는  방법

-   삭제하려는 FAQ를  선택해 FAQ 상세페이지로  이동합니다.
-   우측  하단의 ‘삭제’를  클릭합니다.
-   데이터는  삭제하지  않고, 사용자에게  표시되지  않도록만  하고  싶다면  좌측의 ‘비사용’을  선택합니다.


# 서비스  운영

## 법인관리

법인차량을  운영하는  법인은  차량을  등록하여  법인구성원이  업무용으로도  사용할  수  있고, 개인용도로  사용할  수  있게  합니다.

### 법인관리자를  등록하는  방법

> 회원관리 > 법인관리 > ‘신규등록’

- 법인명을  입력합니다.
- 법인코드 : 법인구성원이  회원가입할  때  입력해야하는  코드입니다.
- 관리자ID: 최초의  비밀번호는  관리자ID와  동일하게  설정되므로, 법인관리자에게  최초  로그인  후  비밀번호를  변경하도록  합니다.	

### 법인관리자로  로그인하는  방법

-   법인관리자는 ID를  전달받아  시스템에  로그인합니다. 최초의  비밀번호는  아이디와  동일합니다.
-   법인관리자가  접근할  수  있는  메뉴와  권한은  아래와  같습니다.
	- 운영관리: 알림조회, 사고관리, 범칙금관리, 주행조회
	- 예약관리: 예약관리
	- 회원관리: 법인회원관리, 개인회원관리, 법인정보관리
	- 정산관리: 결제조회
	- 게시판관리: 1:1문의관리

## 법인정보관리

> 회원관리 > 법인관리 > 법인상세정보 > 법인정보관리

-   법인관리자 ID로  로그인하면  법인정보관리  화면에  접근할  수  있습니다.
-   법인 정보 입력
	-  대표자명, 대표연락처, 사업자등록번호, 사업자등록증, 상세주소를  입력합니다.
	-   법인관리자는  법인정보관리의  화면에서  법인의  기본정보와  결제카드  등의  정보를  입력합니다.
	-   이용목적 : 법인  회원이  차량을  대여할때, 이용목적의  입력의  필수여부를  선택합니다.
	-   예약메일 : 소속  회원들의  예약  시, 관리자가  예약알림을  수신받을지  여부를  선택합니다.
-   결제정보  입력
	-   입력한  결제  카드  정보는  소속  법인회원들의  업무용  차량  이용시  요금  결제용으로  사용됩니다.
-   법인관리자  정보
	-   법인관리자  정보를  입력합니다.
	-   이메일 : 법인소속  회원들의  활동  알림을  수신받습니다.
	-   ‘관리자  추가’를  통해서  법인관리자를  추가  할  수  있습니다.

### 법인  차량을  등록하는  방법

-   차량관리에서  이용대상을 ‘법인’을  선택합니다.
-   어느  법인  소속  회원이  이용할  수  있는지  선택할  수  있습니다.

### 개인회원(개인용도) 대여일  등록하기

-   차량관리 > 이용대상: 법인차량  선택 > ‘개인회원대여일’ 에서  개인회원이  차량을  이용할  수  있는  날을  지정할  수  있습니다.
-   최대 3개월치의  달력을  제공합니다.
-   전체, 평일, 공휴일  별로  대여가능/대여불가를  한꺼번에  지정할  수  있습니다.
-   일별로  가능일자를  선택하고  싶은  경우엔  캘린더에서  해당  날짜를  선택하면  됩니다.
-   ‘저장하기’를  클릭합니다.

## 법인회원관리

시스템에서  법인소속회원은  두가지로  나뉩니다.

1.  법인회원은  법인에  소속되어  업무용으로  차량을  이용하는  회원입니다.
2.  개인회원은  법인에  소속되어  개인용으로  차량을  이용하는  회원입니다.

### 법인  소속  회원의  가입승인과  면허승인  방법

법인  소속의  구성원은  회원  가입  후, 법인관리자  또는  운영회사  관리자가  회원승인을  해줘야만  서비스를  이용할  수  있습니다.

1.  개인회원의  승인 : 회원관리 > 개인회원관리
2.  법인회원의  승인 : 회원관리 > 법인회원관리

-   승인대기중인  회원을  클릭해서  회원상세  화면에  진입합니다.
-   회원의  정보를  확인하고  정보가  맞는  경우  가입승인  상태를 ‘승인완료’로  체크합니다.
-   법인  소속  회원이  아니거나  정보가  틀린  경우 ‘비승인’으로  체크합니다.
-   면허의  정보를  확인하고  정보가  맞는  경우  면허승인  상태를 ‘승인완료’로  체크합니다.
-   면허  정보가  올바르지  않은  경우에는  면허승인  상태를 ‘비승인’으로  체크합니다.
-   저장을  클릭합니다.

### 승인대기중인  회원을  한번에  승인하는  방법 (일괄승인)

> 회원관리 > 법인회원관리 or 개인회원관리

-   회원  리스트에서  회원  승인대기중인  회원은  테이블  우측에  체크박스가  표시됩니다.
-   승인하고자하는  회원  행의  체크박스에  체크를  하고 ‘회원일괄승인’버튼을  클릭합니다.

## 일반회원관리

### 면허를  승인하는  방법

일반회원이  차량  예약을  하기  위해서는  관리자가  반드시  면허  승인을  해줘야  합니다.

> 회원관리 > 일반회원관리 > 일반회원상세

-   회원  리스트에서  면허  승인대기중인  회원을  클릭해서  회원상세  화면에  진입합니다.
-   면허의  정보를  확인하고  정보가  맞는  경우  면허승인  상태를 ‘승인완료’로  체크합니다.
-   면허  정보가  올바르지  않은  경우에는  면허승인  상태를 ‘비승인’으로  체크합니다.

## 예약관리

### 사용자의  예약을  확인하는  방법

스마트폰  모바일앱을  통해  신규예약이  들어왔을  경우, 예약관리에서  확인할  수  있습니다.

-   예약번호 : 예약  생성시  발생하는  고유  번호
-   예약자
-   예약상태
	-   예약  완료 : 예약과  결제가  정상적으로  완료된  차량
	-   결제  실패 : 요금의  결제가  실패한  내역이  있는  예약
	-   대여  대기 : 대여  시작  시간이  경과했지만  사용자가  아직  이용  시작  버튼을  누르지  않은  황태
	-   대여중 : 사용자가  이용중인  차량
	-   반납  완료 : 정상적으로  반납이  완료된  차량
	-   반납지연 : 반납  시간이  초과  할  때까지  반납이  되지  않은  차량
	-   예약  취소 : 사용자  또는  관리자가  예약을  취소한다
	-   강제  반납 : 관리자에  의해  강제  반납이  이루어진  상태
-   대여시작일시
-   대여종료일시
-   제어시작일시 : 사용자가  이용  시작  버튼을  누른  시점
-   회원타입
-   소속법인
-   알림메일
-   예약구분
-   차량정보
-   예약접수일자

### 관리자가  신규  예약을  등록하는  방법

관리자는  시스템에서  신규  예약을  생성할  수  있습니다. 관리자가  예약  관리에서  신규  예약을  생성하는  경우  사용자가  등록한  결제  카드로  결제가  됩니다.

> 예약관리 > ‘신규등록’ 클릭

#### 회원  예약을  등록하는  방법

-   예약구분: 회원  예약을  선택합니다.
-   예약시작일과  종료일을  선택합니다. 예약시작일은  현재  시간  이후로  선택할  수  있습니다.
-   ‘예약자  선택’을  클릭해  차량을  이용할  예약자를  지정합니다.
-   차량의  선택: 구역명과  지점명을  선택하면, 지점에  속한  차량  중에  해당  시간에  예약이  가능한  차량을  불러옵니다. 차량번호  드롭다운리스트에서  차량을  선택합니다.
-   클래스로  운영하는  업체의  경우에는  클래스를  선택합니다.

#### 정비예약을  등록하는  방법

관리자는  사용자의 예약을 막기 위해 정비 예약을  생성해 둘 수  있습니다.	

> 예약관리 > ‘신규등록’ 클릭

-   예약구분 : 정비예약을  선택합니다.
-   정비  예약시작일과  종료일을  선택합니다. 예약시작일은  현재  시간  이후로  선택할  수  있습니다.
-   정비예약에서는  예약자를  선택하지  않습니다.
-   차량의  선택: 구역명과  지점명을  선택하면, 지점에  속한  차량  중에  해당  시간에  예약이  가능한  차량을  불러옵니다. 차량번호  드롭다운리스트에서  차량을  선택합니다.
-   ‘등록’을  클릭합니다.

#### 옵션을  추가하는  방법

-   옵션은  추가하기  위해서는  반드시  지점을  선택해야  합니다.
-   지점을  선택하면  해당  차량의  추가  할  수있는  옵션이  리스트업  됩니다.

#### 동반  운전자를  추가하는  방법

-   ‘동반운전자  추가’를  클릭합니다.
-   추가하려는  동반운전자는  반드시  시스템  내에  등록된  회원이어야  합니다.

### 예약을  변경하는  방법

> 예악관리 > 예약  건  선택 > 예약상세

예약이  완료된  건의  예약  내용을  변경할  수  있습니다.

-   변경할  수  있는  내용 : 대여시작일, 대여종료일
-   지점과  차량은  변경할  수  없습니다. 지점과  차량을  변경하기  위해선  예약을  취소하고  재예약을  합니다.

### 예약을  취소하는  방법

> 예약관리 > 취소하고자  하는  예약건  클릭 > 예약상세

-   페이지  하단의 ‘예약  취소’ 클릭
-   예약을  취소하면  사용자가  결제했던  이용  요금이  모두  환불되고  취소정책에  따라  취소정책수수료도  함께  부과됩니다.

### 차량을  강제  반납하는  방법

관리자는  사용자가  부득이하게  차량을  반납하지  못하는  상황에  처하거나  문제가  발생한  경우, 사용자가  이용중인  차량을  강제로  반납할  수  있습니다.

> 예약관리 > 예약  건  클릭 > 예약상세

-   페이지  하단의 ‘반납’ 또는 ‘강제반납’을  클릭합니다.

	-   관리자가  반납을  처리할  경우  사용자에게  요금이  환불되지  않습니다.
	-   반납  처리  이후에는  사용자는  더이상  차량을  제어할  수  없게됩니다.
	-   사용자가  스마트키의 ‘이용시작’을  누른  시점  이후, 페이지  하단에 ‘반납’과 ‘강제반납’이  표시됩니다.
	-   반납은  정상적으로  주행요금을  결제하고, 반납  조건이  충족시켜야만  반납을  시키는  버튼입니다.
	-   강제반납은  반납조건을  무시하고, 주행요금  결제도  하지  않고, 차량의  예약상태만  강제적으로  반납으로만  바꾸는  버튼입니다.

-   관리자는  각  상황에  따라  예약취소 / 반납 / 강제반납을  활용할  수  있습니다.

### 클래스  예약  건의  배차  차량  변경

> 예약관리 > 차량을  변경하고자  하는  예약  건을  선택

-   클래스  단위로  운영하는  경우, 유저가  클래스를  예약하면  자동으로  배차가  됩니다.
-   관리자는  유저에게  배차된  차량을  변경할  수  있습니다.

### 사용자의  결제  내역을  확인하는  방법

> 예약관리 > 예약상세

-   예약건별로  결제  내역을  확인할  수  있습니다.

### 추가과금  결제하는  방법

> 예약관리 > 추가과금이  필요한  예약건  클릭

-   페이지  중간에 ‘추가과금  결제’ 클릭합니다.
-   추가과금액과  추가과금사유를  입력한후 ‘선택’을  클릭합니다.

## 범칙금관리

### 범칙금을  등록하는  방법

사용자가  차량을  이용하는  도중  발생한  범칙금을  관리할  수  있습니다.

> 운영관리 > 범칙금관리 > 신규  등록

-   범칙금이  발생한  차량의  지점과  차량  번호를  선택합니다.
-   범칙금  발생시점을  선택하면  해당  날짜에  예약  건들이  리스트업  됩니다.
-   예약번호와  운전자  병을  확인하고  선택합니다.
-   범칙금  정보를  입력합니다.

## 사고관리

### 접수된  사고  내역을  확인  하는  방법

사용자가  차량을  이용하는  도중  사고가  발생한  경우  사용자는  유저  앱을  통해  사고를  접수할  수  있습니다. 유저  앱에서  접수된  사고는  작업  관리에서  확인할  수  있습니다.

> 운영관리 > 사고  관리 > 접수된  사고  건을  클릭

-   사고  상세페이지에서  사고가  발생한  예약건의  차량과  회원의  정보를  확인할  수  있습니다.
-   사고  정보에서  사용자가  등록한  사고  설명과  업로드한  사진을  확인할  수  있습니다.
-   피해자  정보는  사용자가  입력하는  정보가  아니고, 필요할  경우  추가적으로  입력하여  관리할  수  있습니다.

# 차량  관리  서비스

## 메인화면(지도)

### 메인  화면의  지도  활용  방법

-   시스템에  등록되어  있는  차량들의  현재  위치와  상태를  지도상에서  확인할  수  있습니다.
-   차량  상태가  정상으로  설정되어  있는  경우에만  지도상에서  확인할  수  있습니다.
-   현재  차량  상태에  따라서  아이콘의  모양이  아래와  같이  다르게  표시됩니다.
-   차량의  아이콘을  클릭하면  차량에  현재  운행  정보, 운전자정보, 차량의  상태  정보를  확인할  수  있습니다.
-   차량  제어를  클릭하면 4가지  차량  제어  버튼이  표시됩니다.
-  지점  아이콘을  클릭하면  지점에  간단한  정보가  표시됩니다

### 차량리스트  필터  활용하는  방법

-   우측의  차량  리스트  영역에서  필터를  사용해  조회하고  싶은  차량만  조회할  수  있습니다.
-   시동  상태, 차량상태, 예약  상태에  따라서  필터링할  수  있습니다.
-   조회된  차량을  클릭하면  차량의  현재  위치로  지도가  포커싱  되고  차량  정보  팝업이  표시됩니다.
-   현재  예약  정보가  있을  경우  예약  상태를  클릭하면  예약  상세정보  페이지로  이동합니다.
-   차량  제어  아이콘을  클릭해서  차량을  제어할  수  있습니다.
-   주행조회  아이콘을  클릭해서  주행  조회  화면으로  이동할  수  있습니다.

## 주행조회

### 차량의  주행기록을  조회하는  방법

> 운영관리 > 주행  조회 > 차량  선택

> 또는  메인지도에서  주행조회  아이콘을  클릭하여  진입할  수  있습니다.

-   주행조회에서는  차량  시동 ACC On/Off를  기준으로  운행이력을  조회할  수  있습니다.
-   조회기간을  선택합니다. 선택한  조회  기간  내에  차량  시동ON 기록이  있는  주행기록을  모두  불러올  수  있습니다.
-   조회를  클릭하면  주행경로와  주기정보시점을  아이콘으로  표시됩니다.
-   주기정보  아이콘을  클릭하면  해당  시점의  차량상태  상세  내역을  확인할  수  있습니다.

### 주행기록을  다운로드  받는  방법

-   우측  상단의  다운로드  버튼을  클릭하면  조회한  기간  내의  차량의  주기  정보를  엑셀  파일로  다운  받을  수  있습니다.

## 알림조회

시스템에서  발생하는  모든  알림은  해당  차량이  소속된  지점의  관리자의  메일로  발송  됩니다.

> 운영관리 > 알림  조회

-   시스템에서  발생한  모든  알림  내역을  확인할  수  있습니다. 또한  상단의  알림  아이콘을  통해  최근  발생한  알림내역을  확인할  수도  있습니다.

CS 시스템에서  아래의  각  상황에서  알림이  발생합니다.

1.  정비필요 : 장비  관리에  설정한  정비항목과 km에  따라서  정비  알림이  발생합니다. 정비  알림을  해제하기  위해선  알림  항목  상세  페이지로  이동해서 ‘ 정비 km 확인’을  클릭합니다.
2.  단말기무응답 : 차량에  장착한  단말기가  응답하지  않는  경우로  현장  관리자의  확인이  필요합니다. 6시간  간격(0시/6시/12시/18시)으로  상태를  체크하여  알림을  발송합니다.
3.  저전압경고 : 차량관리 > 차량상세  에서  입력한  저전압  경고  조치에  따라  알림이  발생합니다. 차량에  배터리가  저전압  하한선  밑으로  내려  간  경우에  알림이  발생하며, 상한선  이상의  조치로  복귀했을  때  알림이  해제됩니다. 저전압  경고가  최초  발생  후  경고가  해제되기  전까지 10분마다  알림이  발송됩니다.
4.  구역  외  이동 : 지점  관리에서  설정한  주행  영역  거리(반경거리)밖에서  차량이  운행  중인  경우  알림이  발생합니다. 지정구역  이탈  알림을  사용하지  않기  위해선  주행영역거리에 0을  입력하면  됩니다.
5.  시간  외  이동 : 지점  관리에서  설정한  지점  운영  시간  외에  도난의심거리(반경거리) 밖을  벗어난  경우  알림이  발생합니다. 60분마다  주기적으로  체크되어  알림이  발생합니다.
6.  반납지연 : 대여  종료  시간이 10분이  지날때까지  차량이  반납  되지  않은  경우  반납지연  알림이  발생합니다. 차량이  반납  되기  전까지  지점  관리자에게  알림메일이  발송됩니다.
7.  결제실패 : 결제  실패가  발생한  경우  최초 1회  관리자에게  결제  실패  알림이  발송됩니다.

## 정비관리

### 정비  항목을  등록하는  방법

> 운영관리 > 정비관리

-   ‘정비추가’를  클릭하면  정비  항목  입력필드가  추가됩니다.
-   제조사, 모델명을  선택하고서  정비  항목과  알림  주기 (km)를  입력합니다.
-   설정한  모델의  차량의  주행거리가  알림주기(km)에  도달할  경우  정비  필요  알림이  발생합니다.

## 차게부출력

### 차게부를  출력하는  방법

> 차게부출력

-   법인차량  세금감면  증빙을  위한  차계부  출력  기능입니다.
-   차계부  조회가  필요한  기간에  따라  조건부로  검색을  할  수  있습니다.
-   차계부에  포함할  차량을  선택한  후  엑셀  다운로드를  클릭합니다.

# CS (Customer Service)

## 공지사항  관리

스마트폰  유저앱의  공지사항에  게시되는  글들을  관리합니다.

### 공지사항을  등록하는  방법

> 게시판관리 > 공지사항  관리 > 하단의 ‘신규등록’ 클릭

-   카테고리: 공지  게시글의  유형을  선택합니다. (공지 or 이벤트)
-   노출  구분 : 전체  또는  특정  법인에게  게시글을  노출할  수  있습니다.
-   노출  설정 : 게시글이  모바일앱에  노출되는  기간을  선택합니다.

### 공지사항을  삭제하는  방법

-   게시판관리 > 공지사항  관리 > 삭제하고자  하는  공지사항  클릭
-   하단의 ‘삭제’를  클릭합니다.

## 1:1문의  관리

사용자가  앱에서  전송한 1:1문의를  관리합니다.

### 1:1문의에  답하는  방법

> 게시판  관리 > 1:1 관리

-   아직  답변하지  않은 1:1문의 (답변대기  상태)를  클릭합니다.
-   답변  내용을  등록하고서  확인을  클릭하면  사용자에게  답변이  발송됩니다.

## 팝업관리

유저앱을  켰을  때  메인에  표시되는  팝업  이미지를  관리합니다. 중요한  공지사항  또는  이벤트  알림  용도로  사용할  수  있습니다.

### 팝업을  등록하는  방법

> 게시판관리 > 팝업관리 > ‘신규등록’ 클릭

-   제목을  입력하고, 규격에  맞는  사이즈의  이미지를  업로드합니다.
-   Full 사이즈와 Half 사이즈 2가지  중  하나를  선택합니다.
-   노출기간과  노출  조건을  선택합니다.
-   ‘등록’을  클릭합니다.

### 팝업을  삭제하는  방법

> 게시판관리 > 팝업관리 > 팝업  선택 > 팝업  상세  페이지

-   하단의 ‘삭제’를  클릭합니다.
-   팝업을  삭제하지  않고, 숨기고  싶은  경우에는  우측  하단의 ‘미노출’을  선택합니다.

# 관리자관리

시스템을  사용하는  관리자를  등록하고, 관리자별로  시스템  접근  권한을  설정합니다.

### 관리자  등록하는  방법

> 관리자관리 > ‘신규등록’ 클릭

-   빈칸에  관리자  정보를  입력합니다.
-   최초의  비밀번호는  관리자ID와  동일하게  생성되므로, 로그인  후  비밀번호를  변경하도록  요청합니다.
-   구역과  지점을  선택하여, 관리  레벨을  지정합니다.
	-   본사관리자  지정 : 전체구역 & 전체지점  선택
	-   구역관리자  지정 : 특정구역 & 전체지점  선택
	-   지점관리자  지정 : 특정구역 & 특정지점  선택
-   관리자는  선택된  지점의  정보만  보고  관리할  수  있습니다.
-   메뉴접근권한  지정
	-   0단계: 메뉴  접근  불가
	-   1단계: 목록  확인 / 상세  확인
	-   2단계: 목록  확인 / 상세  확인 / 상세  수정 / 신규  등록
	-   3단계: 목록  확인 / 상세  확인 / 상세  수정 / 신규  등록 / 삭제
	-   엑셀다운로드권한  체크박스에  체크시, 해당  관리자는  엑셀  다운로드  권한을  가지게  됩니다.
	-   면허승인권한  체크박스에  체크시, 해당  관리자는  면허승인권한을  가지게  됩니다.
	-   가입승인권한  체크박스에  체크시, 해당  관리자는  가입승인권한을  가지게  됩니다.
