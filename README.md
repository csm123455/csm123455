<div align="center">
  
# 안녕하세요, 클라우드 네이티브 백엔드 개발자 조성민입니다. 👋
### 코드를 클라우드에 배포하고, 안정적으로 운영하는 경험을 사랑합니다.

<p>
  MSA 환경에서 발생하는 복잡한 문제들을 마주하고, 데이터 기반의 트러블슈팅을 통해 해결하는 과정에서 성장합니다.
  <br>
  Terraform(IaC)으로 인프라를 구축하고, Kubernetes 위에서 애플리케이션을 운영하며, CI/CD 파이프라인을 통해 배포를 자동화한 경험을 가지고 있습니다.
</p>

<p>
  <a href="mailto:csm123455@gmail.com"><img src="https://img.shields.io/badge/Email-ea4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://csm123455.github.io" target="_blank"><img src="https://img.shields.io/badge/Portfolio-25D366?style=for-the-badge&logo=wechat&logoColor=white"></a>
  <a href="[https://linkedin.com/in/your-profile]" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
</p>
</div>

---

## 🚀 Featured Projects

### 🛍️ MSA 기반 실시간 중고거래 플랫폼 구축 (Final Project)
**대규모 트래픽에도 안정적이고 확장 가능한 서비스를 목표로, MSA 구조의 중고거래 플랫폼을 설계하고 구축했습니다.**

- **My Role & Contributions**:
  - **주요 도메인(회원, 상품, 주문) 마이크로서비스 API 서버 설계 및 개발**
  - **Terraform(IaC)을 활용한 AWS EKS 클러스터 및 클라우드 인프라(VPC, MSK, Aurora 등) 설계/구축**
  - **GitHub Actions, ArgoCD 기반의 GitOps CI/CD 파이프라인 구축 및 배포 자동화**
  - **Istio 서비스 메쉬를 도입하여 mTLS 암호화 및 트래픽 제어, 모니터링 환경 구현**
- **Troubleshooting & Achievements**:
  - **`문제`**: `k6` 부하 테스트 중, 상품 조회 API에서 DB 과부하로 인한 지연 시간 급증(3000ms 이상) 현상 발견
  - **`해결`**: CloudWatch, Prometheus 지표 분석으로 병목 지점 확인 후, `ElasticCache for Redis`를 도입하여 DB 조회 결과를 캐싱하는 아키텍처로 개선
  - **`성과`**: **API 평균 응답 속도를 350ms로 단축하여 약 88%의 성능 개선 달성**
- **Tech Stack**: `Spring Boot & Cloud`, `gRPC`, `Kafka`, `MySQL`, `Redis`, `DynamoDB`, `AWS EKS`, `Terraform`, `Istio`, `ArgoCD`
- **Links**: `[자세한 회고록/Notion 링크]` `[GitHub Repository 링크]`

<br/>

### 🚢 AWS 기반 웹 서비스 배포 자동화 (Mid Project)
**수동 배포의 비효율성을 개선하고 배포 안정성을 확보하기 위해 CI/CD 파이프라인을 구축했습니다.**

- **My Role & Contributions**:
  - **GitHub Actions를 CI 툴로 사용하여 코드 Push 시 자동 빌드/테스트 파이프라인 구성**
  - **AWS CodeDeploy, S3를 연동하여 EC2 서버에 Blue/Green 무중단 배포 파이프라인 구축**
  - **정적 프론트엔드 자산을 S3와 CloudFront(CDN)를 통해 배포하여 로딩 속도 최적화**
- **Tech Stack**: `Spring Boot`, `React`, `AWS (EC2, S3, CloudFront, CodeDeploy, Route53)`, `GitHub Actions`
- **Links**: `[자세한 회고록/Notion 링크]` `[GitHub Repository 링크]`

---

### 📚 Studying
- **Kubernetes**: 컨테이너 오케스트레이션 심화 학습 및 운영 경험 확장
- **Effective Java**: 더 나은 Java 코드를 위한 원칙 학습
- **Algorithm**: 문제 해결 능력 향상을 위한 꾸준한 코딩 테스트 풀이

---

## 🛠️ Tech Stack
<table>
  <tr>
    <td align="center" width="160">
      <strong>Frontend</strong>
    </td>
    <td>
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
      <strong>Database & Message Queue</strong>
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
      <img src="https://img.shields.io/badge/Istio-466BB0?style=for-the-badge&logo=istio&logoColor=white"/>
      <img src="https://img.shields.io/badge/GitHub Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white"/>
      <img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white"/>
    </td>
  </tr>
</table>

---
 
### 🤝 Collaboration Tools
<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white"/>
  <img src="https://img.shields.io/badge/VS Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white"/>
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
  <img src="https://img.shields.io/badge/SpringToolSuite4-6DB33F?style=for-the-badge&logo=spring&logoColor=white"/>
</p>

---
 
### 📫 Contact
- **Email**: csm123455@gmail.com
- **Portfolio**: https://csm123455.github.io

---

## 📊 My GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=csm123455&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true" alt="csm123455's GitHub stats" />
  <br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=csm123455&layout=compact&langs_count=10&theme=tokyonight" alt="Top Languages" />
  <br/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=csm123455&theme=tokyonight" alt="GitHub Streak" />
</div>
