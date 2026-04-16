##  프로젝트 상태

본 프로젝트는 **팀 프로젝트를 기반으로 한 개인 포트폴리오**입니다.

* 원본 레포지토리: [(팀 레포 링크)](https://github.com/prgrms-be-adv-devcourse/beadv5_5_ChamomileChicken_BE)
* 개발 인원: 6명
* 진행 기간: 2026.03 ~ 2025.05.04

현재 프로젝트는 **진행 중**이며,  
추가 요구사항을 우선 반영하고 있습니다.  

이후 성능 최적화 및 운영 환경 개선을 단계적으로 진행할 예정입니다.



## 프로젝트 목표

대규모 트래픽을 고려한 MSA 기반 서비스의  
인프라 구축 및 운영 환경 설계에 중점을 두었습니다.



## 설계 및 기획 참여

- 서비스 주제 선정 및 기능 정의 과정 참여
- 전반적인 ERD 설계 및 도메인 구조 설계 협업



## 담당 영역 및 기여

### Product 도메인

- 상품 및 일정 관리 기능 구현
- 재고 관련 핵심 로직 설계 및 처리

### 인프라 및 배포

- Docker 기반 서비스 컨테이너화
- EC2 환경에서 서비스 배포 및 실행 환경 구성

### CI/CD

- GitHub Actions 기반 빌드 및 배포 자동화
- 서비스별 이미지 빌드 및 배포 파이프라인 구성 (2인 협업)


## 협업

- 주문 서비스 담당자와 협업하여 주문 흐름 연동
- Elasticsearch 담당자와 협업하여 검색 기능 연동
- Kafka 기반 이벤트 처리 로직은 별도 담당자가 구현



## 향후 개선 계획

- **K3s 기반 컨테이너 오케스트레이션 적용**
  - 기존 docker-compose 환경을 K3s로 전환하여 서비스 운영 및 확장성 개선

- **서비스별 메모리 사용량 최적화**
  - 제한된 인프라 환경에서의 안정적인 운영을 위한 리소스 튜닝

- **모니터링 시스템 구축**
  - Prometheus 및 Grafana를 활용한 서비스 상태 및 성능 모니터링 환경 구성
  - AI 담당자와 협력해 LLM 활용 모니터링 기획
 
## 기획서 정리
https://www.notion.so/5-3445219e8c9a8005b6e9e358e9866e12?source=copy_link

## 인프라 설계 고민 (K3s)
K3s 도입을 검토하는 과정에서 아직 개념을 정리해가는 단계였기 때문에,  
다양한 운영 방식 중 어떤 접근이 현재 환경에서 효율적인지에 대해 고민했습니다.

초기에는 전체 구조를 완벽히 설계하기보다는,  
실제 환경에서의 이해도를 높이기 위해 기본적인 셋업부터 진행하는 방향으로 접근했습니다.

https://www.notion.so/5-K3s-3445219e8c9a805da3abc0942aa16133?source=copy_link



## 참여 인원
| <img src="https://github.com/xub2.png" width="100" height="100"/> | <img src="https://github.com/choi38995.png" width="100" height="100"/> | <img src="https://github.com/JK-LEE98.png" width="100" height="100"/> | <img src="https://github.com/maark1106.png" width="100" height="100"/> | <img src="https://github.com/mirupio.png" width="100" height="100"/> | <img src="https://github.com/reflash407.png" width="100" height="100"/> |
| :---: | :---: | :---: | :---: | :---: | :---: |
| [@xub2](https://github.com/xub2) | [@choi38995](https://github.com/choi38995) | [@JK-LEE98](https://github.com/JK-LEE98) | [@maark1106](https://github.com/maark1106) | [@mirupio](https://github.com/mirupio) | [@reflash407](https://github.com/reflash407) |
