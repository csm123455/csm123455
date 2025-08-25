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

## 🚀 Build Projects

### 🗺️ Map.zip: 장거리 이동 맞춤형 AI 맛집 추천 서비스
**MSA 구조와 AI 추천 시스템을 결합하여, 사용자의 장거리 이동 경로와 스케줄에 최적화된 맛집을 추천하는 플랫폼을 구축했습니다.**
- **My Role & Contributions**:
  - **AI 추천, 사용자, 장소 등 핵심 도메인별 마이크로서비스 API 설계 및 개발**
  - **Terraform(IaC) 기반 AWS EKS 클러스터 및 VPC, MSK, Aurora 등 클라우드 인프라 아키텍처 설계 및 구축**
  - **GitHub Actions와 ArgoCD를 연동한 GitOps 기반 CI/CD 파이프라인 구축으로 배포 자동화**
  - **Istio 서비스 메쉬를 도입하여 MSA 환경의 트래픽 제어, mTLS 암호화 및 통합 모니터링 시스템 구현**
- **Tech Stack**: `Spring Boot & Cloud`, `gRPC`, `Kafka`, `MySQL`, `Redis`, `DynamoDB`, `AWS EKS`, `Terraform`, `Istio`, `ArgoCD`
<br/>
<a href="https://www.notion.so/likelion/1f444860a4f480339472e6f8743816aa?p=25344860a4f480e994e7ea34ff53a849&pm=s"><img src="https://img.shields.io/badge/Project_Details-Notion-000000?style=for-the-badge&logo=notion&logoColor=white"></a>
<a href="https://github.com/CLD3rd-Team4/App"><img src="https://img.shields.io/badge/Application_Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white"></a>
<a href="https://github.com/CLD3rd-Team4/Infra"><img src="https://img.shields.io/badge/Infrastructure_Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white"></a>

<br/>

### 🎶 Jazz LP E-commerce Platform: 재즈 LP 중고거래 플랫폼
**재즈 LP 매니아를 위한 중고거래 플랫폼을 구축하고, 안정적인 서비스 운영을 위해 CI/CD 배포 자동화 파이프라인을 설계했습니다.**
- **My Role & Contributions**:
  - **GitHub Actions를 활용하여 코드 Push 시 자동 빌드, 테스트, 컨테이너 이미지 빌드 및 푸시 자동화**
  - **AWS CodeDeploy, S3, EC2를 연동하여 Blue/Green 무중단 배포 파이프라인 구축**
  - **React 기반의 프론트엔드 정적 파일을 S3와 CloudFront(CDN)로 배포하여 로딩 속도 최적화**
  - **Terraform을 사용하여 EC2, ALB, Route53 등 AWS 인프라를 코드로 관리**
- **Tech Stack**: `Spring Boot`, `React`, `AWS (EC2, S3, CloudFront, CodeDeploy, Route53)`, `Terraform`, `GitHub Actions`
<br/>
<a href="https://www.notion.so/likelion/1f444860a4f480339472e6f8743816aa?p=22a44860a4f4803bb60cf51c5424d90f&pm=c"><img src="https://img.shields.io/badge/Project_Details-Notion-000000?style=for-the-badge&logo=notion&logoColor=white"></a>
<a href="https://github.com/CLD-3rd/team1-infra/tree/dev"><img src="https://img.shields.io/badge/Infrastructure_Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white"></a>
<a href="https://github.com/CLD-3rd/team1-manifest/tree/dev"><img src="https://img.shields.io/badge/Manifest_Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white"></a>

<br/>

### 🚬 Smokezone: 흡연구역 정보 공유 애플리케이션
**Kotlin으로 안드로이드 앱을 개발하고 Spring Boot로 백엔드 서버를 구축하여, 사용자 참여형 흡연구역 정보 공유 서비스를 완성했습니다.**
- **My Role & Contributions**:
  - **[Android] Kotlin 기반 네이티브 앱 UI/UX 설계 및 개발, Retrofit2를 이용한 서버 API 연동**
  - **[Backend] Spring Security 기반 JWT 인증 및 OAuth2 소셜 로그인(카카오, 구글) 기능 구현**
  - **흡연구역 정보 CRUD API 개발 및 AWS S3를 연동한 이미지 업로드/관리 기능 구현**
  - **Querydsl을 활용한 동적 검색 기능 구현 및 Redis를 통한 Refresh Token 관리**
- **Tech Stack**: `Kotlin`, `Android Studio`, `Retrofit2`, `Java 17`, `Spring Boot`, `JPA`, `Querydsl`, `MySQL`, `Redis`, `AWS S3`, `Docker`
<br/>
<a href="https://github.com/csm123455/Smokezone"><img src="https://img.shields.io/badge/Source_Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white"></a>

<br/>

### 📚 Study Room Management: 스터디룸 예약 및 알림 서비스
**스터디룸의 예약 및 관리를 위한 백엔드 시스템을 개발하고, FCM을 통해 사용자에게 실시간 예약 알림을 제공하는 기능을 구현했습니다.**
- **My Role & Contributions**:
  - **Spring Boot, JPA를 활용한 스터디룸 예약/조회/수정/삭제 API 개발**
  - **Firebase Cloud Messaging(FCM)을 연동하여 예약 변동 시 사용자에게 푸시 알림 전송 기능 구현**
- **Tech Stack**: `Spring Boot`, `JPA`, `MySQL`, `FCM`
<br/>
<a href="https://www.notion.so/likelion/1f444860a4f480339472e6f8743816aa?p=1f544860a4f48080a2fde7549105b848&pm=c"><img src="https://img.shields.io/badge/Project_Details-Notion-000000?style=for-the-badge&logo=notion&logoColor=white"></a>
<a href="https://github.com/CLD-3rd/infra-team4"><img src="https://img.shields.io/badge/Source_Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white"></a>

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

## 🛠️ Technical Skills
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
