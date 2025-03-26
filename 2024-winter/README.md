# 🏫 비상교육 – 데이터플랫폼셀 인턴십 (2024.01 - 2024.02)

## 📌 프로젝트 개요

비상교육은 약 21개의 사내 브랜드를 운영하고 있으나, 브랜드별 데이터가 분산되어 통합 관리가 어려운 상황이었습니다.  
**Data Platform Cell**은 이러한 문제를 해결하기 위해 **브랜드 데이터를 통합 운영하고 데이터 중심의 조직으로 전환**하기 위한 데이터 플랫폼을 구축하였습니다.

---

## 💡 주요 기여 및 성과

### ✅ 데이터 파이프라인 구축 및 운영

- **데이터 웨어하우스 구축 및 ELT 파이프라인 구축:**  
  - AWS VPC 환경 내에서 **Airflow 기반 파이프라인**을 Docker 컨테이너에 구성
  - **사내 브랜드 DB → 데이터 웨어하우스** 간 연계 수행
  - 데이터 플랫폼의 확장성을 고려해 단순 소스 DB가 아닌 **DBMS 종류별 파이프라인 구축 (MySQL, PostgreSQL 담당)**

- **ETL 파이프라인 구축:**
  - **데이터 웨어하우스 → 사내 데이터 포털 DB** 간 메타데이터 수집∙가공∙적재를 위한 파이프라인 개발
  - **성능 최적화:**  코드 리팩토링 및 쿼리 최적화를 통해 **52,714개 메타데이터 레코드 처리 시간 5% 단축**
    - 기존: 12분 9초 → 개선: 11분 32초
  - **정합성 확보:** 메타데이터 수집·가공·적재 과정 중 발생한 오류를 **테스트 케이스 기반으로 분석 및 해결**
  - **데이터 품질 모니터링:** 메타데이터 적재 과정에서 브랜드별 **데이터 품질 통계 관리 프로세스 설계 및 구현**

---

## 🧰 사용 기술 및 도구

### 💻 Skill Set

- **기술:**  
  `PostgreSQL`, `MySQL`, `Oracle`, `Airflow`, `AWS (EC2, RDS, VPC, S3)`, `Docker`, `Git`

- **도구:**  
  `Cloud Beaver`, `VSCode`, `DataGrip`, `Jira`, `Confluence`, `MS Teams`

---

## 📷 시각 자료

### Airflow Dag 리스트  
<div align="center">
    <img src="https://github.com/user-attachments/assets/86b33ad5-6bf5-460f-8fca-be516126a639">
</div>

### Airflow DAG 예시  
<div align="center">
    <img src="https://github.com/jeongmin1217/Visang-Education-Data-Platform-Cell-Review/assets/79658037/8c548eff-ffb9-423f-8d9c-4d8beb711114">
</div>

### 사내 브랜드 DB 리스트  
<div align="center">
    <img src="https://github.com/user-attachments/assets/6134822e-cba5-4bf5-8dd9-10fdc0398d92">
</div>

### VPC 구성도  
<div align="center">
    <img src="https://github.com/jeongmin1217/Visang-Education-Data-Platform-Cell-Review/assets/79658037/c6cf2c5c-a249-4bf5-9223-5c2bb4a5effa">
</div>
---

## 🗣️ 피드백

### 사수님 피드백  
<div align="center">
    <img src="https://github.com/jeongmin1217/Visang-Education-Data-Platform-Cell-Review/assets/79658037/577d388d-d5fb-4a6a-9c4d-f5a8d0effb24">
</div>
---

# Visang Education Data Platform Cell Internship (Jan 2024 - Feb 2024)

## Key Achievements

- Constructed a data pipeline connecting the internal brand databases to the data warehouse
- Built a data pipeline for ETL tasks of metadata information from the data warehouse to the in-house data portal service

## Role & Skill Set

#### Role : Data Engineer

#### Skill Set

<b>PostgreSQL, MySQL, Oracle, Airflow, AWS(EC2, RDS, Internet Gateway, NAT Gateway, Application Load Balancer, subnet), Docker, Git<br> VScode, DataGrip, Cloud Beaver, Jira, Confluence, MS Teams</b>

## Main Tasks

- The construction of the data pipeline was performed using Airflow within a Docker container
<div align="center">
    <img src = "https://github.com/jeongmin1217/Visang-Education-Data-Platform-Cell-Review/assets/79658037/259658ed-1231-459d-bec5-cad4c18b1f20">
</div>

- The internal data portal was developed within an AWS VPC network
<div align="center">
    <img src = "https://github.com/jeongmin1217/Visang-Education-Data-Platform-Cell-Review/assets/79658037/c6cf2c5c-a249-4bf5-9223-5c2bb4a5effa">
</div>

- Used a variety of databases (PostgreSQL, MySQL, Oracle) while connecting internal brand databases and performing some jobs in the data warehouse
<div align="center">
    <img src = "https://github.com/jeongmin1217/Visang-Education-Data-Platform-Cell-Review/assets/79658037/c8367040-bb4c-4e0f-9797-f3718d58a8b2">
</div>

- Used Cloud Beaver, a Cloud Database Manager, for collaborative work
- <b>Optimized queries and refactored code, reducing the ETL task time for about 52,000 metadata entries by 37 seconds compared to the initial duration</b>
- Progressed an automation task to classify metadata subject areas to be uploaded to the in-house data portal service using the Chat GPT API (Worked on after GPT Prompt Engineering)
- Sample Airflow DAG job
  <img src = "https://github.com/jeongmin1217/Visang-Education-Data-Platform-Cell-Review/assets/79658037/8c548eff-ffb9-423f-8d9c-4d8beb711114">

## Etc

### Feedback from supervisor

<div align="center">
    <img src = "https://github.com/jeongmin1217/Visang-Education-Data-Platform-Cell-Review/assets/79658037/577d388d-d5fb-4a6a-9c4d-f5a8d0effb24">
</div>
