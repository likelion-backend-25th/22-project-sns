# SNS 솔루션 서비스 개발 프로젝트

멋쟁이사자처럼 백엔드 부트캠프 25기 응용 프로젝트(SNS 솔루션) 저장소입니다.  
React 프론트엔드와 Spring Boot 4 REST API, MyBatis 3.x, MySQL 9.x를 기반으로 풀스택 SNS 서비스를 개발하고 AWS 환경에 배포합니다.

## 1. 프로젝트 개요
- 과정명: 멋쟁이사자처럼 백엔드 부트캠프 25기
- 프로젝트 유형: SNS 솔루션 서비스 구축 및 배포 (2주간 진행)
- 핵심 목표:
  - React SPA와 Spring Boot 간의 비동기 REST API 연동
  - 회원 관리, 피드 업로드, 해시태그 검색, 댓글/좋아요/북마크 상호작용 구현
  - 서드파티 결제(PortOne) 연동을 통한 VIP 정기 구독 및 결제 3단계 검증
  - Docker Compose 및 AWS 클라우드 인프라 기반 배포

## 2. 기술 스택
- 프론트엔드: React SPA, Vite, Axios
- 백엔드: Java 17, Spring Boot 4.x, Spring Security, JWT (Access/Refresh RTR)
- 데이터 접근 계층: MyBatis 3.x
- 데이터베이스: MySQL 9.x (InnoDB, utf8mb4)
- 인프라 및 스토리지: AWS EC2 (Ubuntu), AWS S3, AWS CloudFront, Docker Compose
- 외부 연동: PortOne (결제 및 빌링키 정기 구독)

## 3. 상세 가이드 및 필수 산출물 안내
프로젝트 설정, 협업 규칙, 심화 과제 및 필수 산출물 작성 가이드는 아래 문서를 참고하세요.

- [프로젝트 진행 가이드 바로가기](guide/README.md)
  - 실습 가이드: 1장 프로젝트 시작, 2장 이슈 관리, 3장 깃허브 프로젝트, 4장 심화 자율 과제
  - 필수 산출물 기준: 기획서, PRD, 시스템 아키텍처, ERD, 화면 설계서, REST API 명세서, 트러블슈팅
