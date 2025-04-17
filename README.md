# DOVI

DOVI는 도보 여행자를 위한 내비게이션 서비스입니다. 안전한 도보 경로를 **음성 안내**로 제공하며, **CCTV 데이터를 활용**하여 실시간으로 안전한 경로를 계산하고 표시합니다.

## Features

- **실시간 경로 탐색** - 시작 지점과 목적지를 기반으로 최적의 도보 경로를 제공
- **CCTV 데이터 연동** - CCTV 위치 정보를 분석하여 안전한 경로 계산
- **경로 시각화** - 지도 위에 경로를 표시하고 CCTV 마커 추가
- **REST API 통합** - 실시간 경로 데이터를 안정적으로 제공

## Tech Stack

### Frontend
- **React** - 사용자 인터페이스 개발
- **React Router** - 페이지 간 탐색 관리
- **Axios** - REST API 통신

### Backend
- **Java Spring Boot** - API 서버 및 비즈니스 로직 구현
- **Spring Data JPA** - 데이터베이스 CRUD 처리
- **MySQL** - 위치 데이터 저장 및 관리

### Cloud & Tools
- **AWS EC2** - 백엔드 서버 배포
- **AWS RDS** - MySQL 데이터베이스 운영
- **Postman** - API 테스트 및 문서화
- **GitHub Actions** - CI/CD 파이프라인 구축
