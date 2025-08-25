<div align="center">
  
# 안녕하세요, 클라우드 엔지니어 조성민입니다. 👋
### 안정성과 확장성을 모두 갖춘 클라우드 플랫폼을 구축하고 자동화합니다.

<p>
  Terraform(IaC)을 통해 인프라를 코드로 관리하고, Kubernetes 기반의 컨테이너 플랫폼 위에서 애플리케이션이 안정적으로 동작하는 환경을 만듭니다.
  <br>
  대규모 트래픽 환경에서 발생하는 복잡한 문제를 데이터 기반으로 해결하고, GitOps 워크플로우를 적용한 CI/CD 파이프라인으로 배포 과정을 자동화하는 데 깊은 흥미를 가지고 있습니다.
</p>

<p>
  <a href="https://csm123455.github.io" target="_blank"><img src="https://img.shields.io/badge/Portfolio-25D366?style=for-the-badge&logo=wechat&logoColor=white"></a>
  <a href="https://memo0051.tistory.com/" target="_blank"><img src="https://img.shields.io/badge/Blog-F74C02?style=for-the-badge&logo=tistory&logoColor=white"></a>
  <a href="https://www.notion.so/1c290cdc092e80519852ec8ad4252243" target="_blank"><img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white"></a>
</p>
</div>

---

## 🚀 개발 프로젝트

### 🛍️ MSA 기반 실시간 중고거래 플랫폼 구축
**대규모 트래픽에도 안정적이고 확장 가능한 서비스를 목표로, MSA 구조의 중고거래 플랫폼을 설계하고 구축했습니다.**
- **My Role & Contributions**:
  - **주요 도메인(회원, 상품, 주문) 마이크로서비스 API 서버 설계 및 개발**
  - **Terraform(IaC)을 활용한 AWS EKS 클러스터 및 클라우드 인프라(VPC, MSK, Aurora 등) 설계/구축**
  - **GitHub Actions, ArgoCD 기반의 GitOps CI/CD 파이프라인 구축 및 배포 자동화**
  - **Istio 서비스 메쉬를 도입하여 mTLS 암호화 및 트래픽 제어, 모니터링 환경 구현**
- **Tech Stack**: `Spring Boot & Cloud`, `gRPC`, `Kafka`, `MySQL`, `Redis`, `DynamoDB`, `AWS EKS`, `Terraform`, `Istio`, `ArgoCD`
<br/>
프로젝트 상세보기 : <a href="https://www.notion.so/likelion/CLD3-Final-4-23244860a4f480699abecc33952f04ee?p=25344860a4f480e994e7ea34ff53a849&pm=s"><img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white"></a>

<br/>

### 🚬 Smokezone: 흡연구역 정보 공유 애플리케이션
**Kotlin으로 안드로이드 앱을 개발하고, Spring Boot로 백엔드 서버를 구축하여 사용자 참여형 흡연구역 정보 공유 서비스를 완성했습니다.**
- **My Role & Contributions**:
  - **[Android - Client]**
    - **Kotlin 및 Android Studio를 활용하여 네이티브 안드로이드 앱의 UI/UX 설계 및 개발**
    - **Retrofit2 라이브러리를 이용한 REST API 통신 및 서버 데이터 연동 구현**
    - **사용자 위치 기반 흡연구역 정보 조회 및 지도 연동 기능 개발**
  - **[Backend - Server]**
    - **Spring Security 기반 JWT 인증 및 OAuth2 소셜 로그인(카카오, 구글) 기능 구현**
    - **흡연구역 CRUD API 개발 및 AWS S3를 연동한 이미지 업로드/관리 기능 구현**
    - **Querydsl을 활용하여 동적 검색 쿼리 및 복잡한 조회 로직의 성능과 가독성 개선**
    - **Redis를 활용하여 Refresh Token 관리 및 이메일 인증 코드 저장**
- **Tech Stack**: `Kotlin`, `Android Studio`, `Retrofit2`, `Java 17`, `Spring Boot`, `JPA`, `Querydsl`, `MySQL`, `Redis`, `AWS S3`, `Docker`
<br/>
프로젝트 상세보기 : <a href="https://github.com/csm123455/Smokezone"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"></a>

<br/>

### 🚢 AWS 기반 웹 서비스 배포 자동화
**수동 배포의 비효율성을 개선하고 배포 안정성을 확보하기 위해 CI/CD 파이프라인을 구축했습니다.**
- **My Role & Contributions**:
  - **GitHub Actions를 CI 툴로 사용하여 코드 Push 시 자동 빌드/테스트 파이프라인 구성**
  - **AWS CodeDeploy, S3를 연동하여 EC2 서버에 Blue/Green 무중단 배포 파이프라인 구축**
  - **정적 프론트엔드 자산을 S3와 CloudFront(CDN)를 통해 배포하여 로딩 속도 최적화**
- **Tech Stack**: `Spring Boot`, `React`, `AWS (EC2, S3, CloudFront, CodeDeploy, Route53)`, `GitHub Actions`
<br/>
프로젝트 상세보기 : <a href="https://www.notion.so/likelion/1f444860a4f480339472e6f8743816aa?p=22a44860a4f4803bb60cf51c5424d90f&pm=c"><img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white"></a>

<br/>

### 🌱 웹 개발 기초 다지기: Spring Boot 게시판
**HTTP, Spring Boot CRUD, 배포의 웹 개발 전체 사이클을 처음부터 끝까지 경험한 프로젝트입니다.**
- **Learnings**:
  - **Spring Boot, JPA를 활용한 기본적인 게시판 CRUD 기능 구현**
  - **MySQL 데이터베이스 연동 및 데이터 관리**
  - **서버 배포를 통해 웹 서비스 동작 원리 학습**
- **Tech Stack**: `Spring Boot`, `JPA`, `MySQL`, `HTML`, `JavaScript`
<br/>
프로젝트 상세보기 : <a href="https://www.notion.so/likelion/1f544860a4f48080a2fde7549105b848?p=1f544860a4f48080a2fde7549105b848&pm=c"><img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white"></a>

---

### 📚 Studying & Interests
- **MSA & Cloud Native Architecture**:
  - Kubernetes 심화 패턴(Operator, CRD)을 학습하고, 프로메테우스와 그라파나를 활용한 실시간 모니터링 및 트러블슈팅 역량을 강화하고 있습니다.
  - Terraform 모듈화를 통해 재사용 가능한 인프라 코드를 작성하고, GitOps 워크플로우를 고도화하는 방법을 연구합니다.
- **Building for Scale: High-Performance Systems**:
  - 다양한 캐싱 전략(e.g., Look-aside, Write-through)을 실제 시나리오에 적용하며 시스템 응답 속도를 개선하는 방법을 탐구합니다.
  - 메시지 큐(Kafka)를 활용한 비동기 처리와 데이터 파이프라인을 구축하여 시스템의 부하를 분산하고 안정성을 높이는 데 관심이 많습니다.
- **Crafting Quality Code**:
  - TDD(Test-Driven Development)와 도메인 주도 설계(DDD) 원칙을 개인 프로젝트에 적용하며, 테스트 가능하고 유연한 코드 구조를 만드는 연습을 꾸준히 하고 있습니다.
- **Algorithm & CS Fundamentals**:
  - 문제 해결 능력과 CS 기본기를 다지기 위해 꾸준히 알고리즘 문제를 풀이하며 탄탄한 기반을 다지고 있습니다.

---

## 🛠️ Tech Stack
<table>
  <tr>
    <td align="center" width="160">
      <strong>Mobile & Frontend</strong>
    </td>
    <td>
      <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white"/>
      <img src="https://img.shields.io/badge/Android Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white"/>
      <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
      <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white"/>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>Backend</strong>
    </td>
    <td>
      <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white"/>
      <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white"/>
      <img src="https://img.shields.io/badge/Spring Cloud-6DB33F?style=for-the-badge&logo=spring&logoColor=white"/>
      <img src="https://img.shields.io/badge/gRPC-000000?style=for-the-badge&logo=grpc&logoColor=white"/>
      <img src="https://img.shields.io/badge/JPA-A46A42?style=for-the-badge&logo=hibernate&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>Database & MQ</strong>
    </td>
    <td>
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
      <img src="https://img.shields.io/badge/Amazon Aurora-007396?style=for-the-badge&logo=amazon-aurora&logoColor=white"/>
      <img src="https://img.shields.io/badge/Amazon DynamoDB-4053D6?style=for-the-badge&logo=amazon-dynamodb&logoColor=white"/>
      <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
      <img src="https://img.shields.io/badge/Apache Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white"/>
    </td>
  </tr>
    <tr>
    <td align="center">
      <strong>DevOps & Infra</strong>
    </td>
    <td>
      <img src="https://img.shields.io/badge/Amazon AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white"/>
      <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
      <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white"/>
      <img src="https://img.shields.io/badge/GitHub Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white"/>
      <img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>Monitoring</strong>
    </td>
    <td>
      <img src="https://img.shields.io/badge/Istio-466BB0?style=for-the-badge&logo=istio&logoColor=white"/>
      <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white"/>
      <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white"/>
    </td>
  </tr>
</table>

---
 
### 🤝 Collaboration & Tools
<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white"/>
  <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white"/>
  <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white"/>
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"/>
  <br/>
  <img src="https://img.shields.io/badge/Android Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white"/>
  <img src="https://img.shields.io/badge/VS Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white"/>
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
</p>

---
 
### 📫 Contact
EMAIL : csm123455@gmail.com
<br/>
PORTFOLIO : https://csm123455.github.io

---

## 📊 My GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=csm123455&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true" alt="csm123455's GitHub stats" />
  <br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=csm123455&layout=compact&langs_count=10&theme=tokyonight" alt="Top Languages" />
</div>
