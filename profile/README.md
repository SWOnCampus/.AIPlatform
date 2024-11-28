<div align="center">
  <img src="https://github.com/user-attachments/assets/27a1a463-0ccf-48fc-b5c5-ef31567b3b25" alt="Biz Mind" width="45"/>
  <h1>Biz Mind</h1>
</div>

<div align="center">
  <h2>📑 목차</h2>
  <p>
    <a href="#-프로젝트-소개">📖 프로젝트 소개</a><br><br>
    <a href="#-주요-기능">🚀 주요 기능</a><br><br>
    <a href="#-기술-스택">📊 기술 스택</a><br><br>
    <a href="#-시스템-아키텍처">🛠 시스템 아키텍처</a><br><br>
    <a href="#-프로젝트-결과">📈 프로젝트 결과</a><br><br>
    <a href="#-팀-소개">🌟 팀 소개</a><br><br>
    <a href="#-메인화면-및-기업-컨설팅-예시-화면">🖼 메인화면 및 기업 컨설팅 예시 화면</a>
  </p>
</div>


## 📖 프로젝트 소개
본 프로젝트는 중소기업의 채팅형 형태로 정보를 입력받아 **LLM 기반의 AI Transformation 컨설팅**과 리포트를 제공하는 플랫폼입니다.  
- 사용자는 자신의 기업 정보와 요구사항을 입력하면, 플랫폼이 이를 분석하고 맞춤형 솔루션과 컨설팅 결과를 생성합니다.
- **간단한 도입**만으로도 기업 전반에 AI를 통합하여 혁신을 이룰 수 있도록 지원합니다.
- 이 플랫폼은 **시간과 비용**을 절감하며 **전문적인 AI 컨설팅** 결과를 제공합니다.

---

## 🚀 주요 기능

1. **컨설팅 프로세스**
    - 문의 접수 → 담당자 배정 → 초기 대응 → 컨설팅 → 리포팅
    - 중소기업 정보 입력 (회사 정보, pain point) 후 AI가 컨설팅 결과를 자동으로 생성합니다.

2. **주요 워크플로우**
    - AI 컨설턴트의 리포트를 통해 효율적인 도입 전략 제공.
    - Hallucination 검증 및 텍스트 유사도 계산을 통한 신뢰도 높은 결과 제공.

---

## 📊 기술 스택

### Backend
- **Spring Boot**: 백엔드 서버 개발
- **PostgreSQL**: 데이터 저장
- **AWS**
  - **EC2**: 애플리케이션 서버 호스팅 및 관리
  - **RDS**: 클라우드 데이터베이스 관리
- **Docker & Docker Compose**: 멀티 컨테이너 환경 구축
- **Github Actions**: CI/CD 파이프라인 구축

### Frontend
- **React**: UI 개발
- **Styled-Components**: 컴포넌트 스타일링
- **Recoil**: 전역 상태 관리
- **Netlify**: 프론트엔드 배포

### AI
- **Elastic Search**: 백터 기반 검색, 문장 임베딩 검색
- **BERT-Score**: 텍스트 유사도 계산 및 Hallucination 검증
- **SentenceTransformer**: 문장 임베딩 생성
- **FastAPI**: REST API 서버

---

## 🛠 시스템 아키텍처

### 주요 구성 요소
- **Frontend**: React 기반 UI 및 사용자 입력 처리.
- **Backend**: FastAPI 및 Spring Boot 기반의 서버 통합.
- **AI Core**: Sentence Transformer와 Elastic Search를 활용한 AI 기반 검색 및 컨설팅 결과 생성.
- **Database**: PostgreSQL 및 AWS RDS를 활용한 데이터 저장 및 관리.
- **DevOps**: Docker 및 Github Actions를 이용한 배포 및 운영 관리.

---

## 📈 프로젝트 결과
- 간단한 입력만으로 중소기업 맞춤형 AI 컨설팅 결과 제공.
- 기업의 생산성과 효율성을 개선하며 도입 비용과 시간을 획기적으로 절감.
- AI 기반 텍스트 분석 및 검증 기술로 신뢰도 높은 리포트 생성.

---

## 🌟 팀 소개
- **Frontend (FE), 기획, 디자인**: 이세은, 장수희
- **Backend (BE)**: 김진하, 유민아
- **AI**: 김준하

---

## 🖼 메인화면 및 기업 컨설팅 예시 화면

![image](https://github.com/user-attachments/assets/a97841cc-d0d8-498c-ae21-40da83045049)
메인화면

<img width="1440" alt="BizMind 기업컨설팅사진" src="https://github.com/user-attachments/assets/5a380d78-b180-4f94-ab20-039f7fe6415c">
기업 컨설팅 예시 화면
