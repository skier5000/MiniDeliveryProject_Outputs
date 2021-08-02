# 미니 배달 플랫폼 구축 산출물 내역

+ 엔티티 설계 수정 내역 
   + 유저 테이블 통합 (내부적으로 구분코드 Customer, Platform, Store)
   + 주문 이력, 주문 상세 통합
   + 공지사항 통합 (내부적으로 구분코드 Customer, Platform, Store)
   + 메뉴 추가 테이블
   + 주문 마스터, 고객 관계 X
   + 장바구니 (주문 마스터 테이블에 구분 코드 Stay, Ongoing, Complete)

+ H2DB 설정
  + "C:\Users\***\Desktop\...\h2\bin\h2.bat" 파일을 실행 → H2DB 실행
  + "C:\Users\***\test.mv.db" 파일을 프로젝트의 application.properties 설정 정보에 맞게 세팅
