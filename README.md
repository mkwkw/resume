# 민경원 | Kyoungwon Min
### Backend Developer

**Email**: mkkw2047@gmail.com <br>
**Blog**: https://mkwkw.tistory.com/ <br>
**Skills**: `Spring boot JPA` `Spring boot Mybatis` `Java` `AWS` `MySQL` <br>
**Algorithm Skill**:<br>
[![Solved.ac
mkkw0228](http://mazassumnida.wtf/api/v2/generate_badge?boj=mkkw0228)](https://solved.ac/mkkw0228)

## ✈️ About Me
>안녕하세요. 저는 서버와 클라우드에 관심있는 개발자 민경원입니다. <br>
>서비스의 개선점을 찾고 해결하는 것을 좋아합니다. <br>
>여러 동료들과 함께 공동의 목표를 향해 나아가는 과정을 좋아합니다. <br>
>주변 사람들이 말하는 저는 "항상 믿고 의지할 수 있는 든든한 사람"입니다. <br>

## 💻 Work Experiences
**2022.10-2022.12** | 모바일 앱개발 협동조합 - 백엔드 개발 인턴 (Backend Developer Intern) <br>
## 📚 Education
**2019.03-2023.08** | 이화여자대학교 컴퓨터공학전공 <br>
**2015.03-2018.02** | 용인한국외국어대학교부설고등학교(HAFS) 자연과학계열<br>
## 🎯 Experiences
### 부트캠프
**2023.06.26-2023.10.20** | 슈퍼코딩 1:1 관리형 웹개발 백엔드 부트캠프 수강
### 동아리
**2022.03-2023.02** | GDSC Ewha <br>
**2020.07-2022.06** | 이화여자대학교 소프트웨어학부 알고리즘 동아리 EDOC <br>
### 활동 
**2022.07-2022.07** | 이화여자대학교 소프트웨어학부 해외단기파견프로그램(프랑스) - EPITA (Ecole pour l' Informatique et Les Techniques Avancées) Summer Program AI course - AI <br> 
**2022.02-2022.06** | 이화여자대학교 원스탑튜터링 Altu-Bitu - 알고리즘 튜터 - Git, Code Review <br>
**2021.08-2021.08** | Microsoft Hackalearn - My Gift Savor 프론트엔드 개발 - HTML, CSS, JS <br>
**2021.07-2021.08** | SW 중심대학 주관 실리콘밸리 교육 프로그램 - 업사이클링 제품 판매 서비스 Up it! 기획, 팀장 - Figma, Android <br>
**2021.06-2021.07** | 이화여자대학교 2021 여름 계절학기 스타트업해커톤캠프 - 음식점 실시간 정보 공유 커뮤니티 서비스 RENO 기획 - Figma <br>

## 🖇️Projects
**2023.08.28-2023.09.22**
**의류 쇼핑몰**
`Spring boot JPA` `Java` `AWS RDS(MySQL)/EC2/S3/RabbitMQ/MongoDB`
- 백엔드 5명, 프론트엔드 5명 협업
- **쿠폰, 회원 등급 담당**
  1. 회원 등급별 쿠폰 발급 구현
  2. Pessimistic Lock 이용하여 쿠폰 재고 관리(동시성 문제 해결)
  3. Spring Batch와 Scheduling 사용하여 유효기간 만료 쿠폰 삭제 기능 및 구매 총액에 따른 회원 등급 조정 기능 구현 & 리팩토링
    - @Scheduled만 사용 → Spring Batch와 @Scheduled 함께 사용
    - Tasklet 방식 사용
- JMeter 이용 부하 테스트

**2023.08.14-2023.08.25**     
**고양이 용품 쇼핑몰**
`Spring boot JPA` `Java` `AWS RDS(MySQL)/EC2`
- 백엔드 6명, 프론트엔드 5명 협업
- 백엔드 역할 분배: 회원 2명, 마이페이지와 장바구니 2명, 상품 담당: 2명
- **AWS RDS 담당 및 상품 담당 - 상품 옵션, 조회, 검색**
  1. AWS RDS 파라미터 그룹 튜닝(max connections, wait timeout)
  2. 상품 조회 및 검색 성능 향상(Spring Cache, MySQL Index)- 전체 상품 조회 시, 651ms에서 10ms로 시간 감축
  3. Stream API 사용하여 가독성 향상
  4. LEFT JOIN 이용하여 판매순 정렬 개발

**2023.08.07-2023.08.11**    
**게시판 만들기 프로젝트**
`Spring boot JPA` `Java` `AWS RDS(MySQL)`
- 백엔드 개발자 5명이 각자 JWT, 회원, 게시글, 댓글, 좋아요 파트를 맡아서 협업
- **JWT 담당**
    1. JWT 토큰 발급
    2. JWT 토큰 복호화(Argument Resolver 이용)
    3. JWT 사용 범위 지정하는 어노테이션 생성 및 활용

**2022.10-2022.12** | **모바일 앱개발 협동조합 - 백엔드 개발 인턴**<br>
**외국인 대상 한국 여행 일정 계획 서비스**<br>
`Spring boot Mybatis` `Java` `MySQL` `Azure` `Nginx` `Let's Encrypt` `AWS` <br>
- API 개발, DB 설계, 테스트 서버 구축 및 배포
- Spring boot Mybatis MVC 패턴 약 100개의 REST API 개발
- MySQL 데이터베이스 테이블 24개 설계, 수정, 구축 및 SQL쿼리 작성
- openAPI 데이터 활용(한국관광공사, 기상청, 한국수출입은행)
- 데이터 저장, 조회, 삭제 기능 구현 (Azure Database 및 AWS S3)
- 테스트 서버 배포(Azure VM, Ubuntu OS) 및 HTTPS 적용(Nginx, Let’s encrypt)
- 로그인 기능 구현(Spring Security)
- 테스트 코드 작성(JUnit)
<br>

**2022.10-2022.12** | **모바일 앱개발 협동조합 - 백엔드 개발 인턴**<br>
**마카오/홍콩 여행 상품 판매 서비스** <br>
`Spring boot JPA` `Java` `MySQL` `AWS`
- API 개발
- Spring boot JPA MVC 패턴 40개의 REST API 개발
- 여행 상품 검색 기능 구현
- 여행 상품 요금 계산 알고리즘 설계 및 구현
- 데이터 저장, 조회, 삭제 기능 구현 (AWS RDS 및 S3)
- 로그인 기능 구현(Spring Security)
- 테스트 코드 작성(JUnit)
<br>

**2021.09-2022.06** | **이화여자대학교 컴퓨터공학전공 졸업 프로젝트 - 백엔드 개발** <br>
**딥러닝기반 글씨 검사 기능을 탑재한 태블릿 PC용 글씨연습어플,  바른글씨** <br>
`Spring boot JPA` `Java` `MySQL` `AWS`
1. 태블릿 PC에 필기할 때 사용자가 원하는 글씨체로 글씨를 쓸 수 있도록 도와주는 서비스 <br>
2. 사용자의 글씨에 대한 3가지 피드백 (글자의 기울기/크기/음소의 비율 검사) 제시 <br>
- 아이디어 제안
- API 개발, DB 설계, 서버 구축 및 배포
- 한글 음소 손글씨 데이터셋 팀 자체 제작
- 선택된 폰트와 사용자 글씨를 비교하여 점수를 매기는 알고리즘 설계 및 구현
- Spring boot JPA 기반의 MVC 패턴으로 6개의 REST API 개발
- MySQL 데이터베이스 테이블 3개 설계 및 구축
- AWS RDS 및 S3를 활용하여 데이터 저장, 조회, 삭제 기능 구현
- AWS EC2(Linux OS), Route 53, ACM을 이용하여 HTTPS 적용하여 서버 배포
- 2022 한국정보처리학회 춘계학술발표대회(ASK) 참여 및 논문 게재

## 🏆 Prizes
**2022.12** | 모바일 앱개발 협동조합 - 백엔드 개발 인턴 - 최우수상 <br>
**2022.06** | 이화여자대학교 - 졸업프로젝트 - 장려상 <br>

## 📎 Certificates
**2023.05** | AWS Solutions Architect - Associate <br>
**2021.09** | SQLD <br>
<!--
**mkwkw/mkwkw** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


