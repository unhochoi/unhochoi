### Introduction

- 안녕하세요! 최운호입니다. :)

---

### Contact & Channel

- Mail : officialunho@gmail.com
- GitHub : https://github.com/unhochoi
- Tec Blog : https://wooono.tistory.com/pages/About
- LinkedIn : https://www.linkedin.com/in/unho-choi-9593871b4/

---

### Skills

- Machine Learning & Data Science
    - NumPy, Pandas, TensorFlow
- Data Engineering & Analysis
    - Spark(Scala), Hadoop, Airflow
    - Google Cloud Pub/Sub, Prometheus, MySQL, Google Cloud BigQuery
- Infra
    - Terraform, Google Kubernetes Engine, Helm, Istio
- CI/CD
    - Google Cloud Build
- Serverless Computing
    - AWS Lambda
- Monitoring & Logging
    - Grafana

---

### Experience

- **엔라이튼 DevOps팀 매니저 - 전문연구요원 (2023/01 ~ ing)**
    - Cloud Service IAM 관리 (Terraform)
    - 사내 Backoffice 시스템 SSO 적용 (Keycloak)
    - CI/CD 고도화 (Datadog Synthetic Test)
    - GKE 기반 Airflow 구축 및 운영 (Helm Chart)
    - Airflow Metric Monitoring 대시보드 및 알람 생성 (StatsD Exporter, Prometheus, Grafana)
    - 엔라이튼↔RTU 간 통신 상태 확인 프로세스 구현 (Pub/Sub, MySQL, Airflow)
    - 날씨 예보 데이터 적재 (Cloud Storage, Pub/Sub, Airflow, BigQuery)

- **삼성전자 클라우드 아키텍트 특강 교육 조교 (2021/03 ~ 2021/05)**
    - 삼성 개발자 대상 3~5일간 특강 교육 조교로 참여
    - 고가용성 및 확장성을 만족하는 클라우드 네이티브 딥러닝 추론 애플리케이션 개발 (Classic, Container, Serverless 버전)

- **국민대학교 분산 데이터 처리 시스템 연구실 연구 조교 (2020/02 ~ 2022/12)**
    - 빅데이터 엔지니어링, 분산 처리, 클라우드 컴퓨팅, 머신러닝 관련 연구 진행

---

### Projects

- **효율적인 대용량 분산 처리를 위한 Spark 패키지 최적화 (2021/03 ~ 2022/08)**
    - **목표**
        - Spark의 Sparse Matrix Multiplication(SPMM) 패키지를 최적화하여, 행렬 곱셈에 따른 최적의 SPMM을 제공하는 서비스 구현
    - **기여 내용**
        - 기존 Spark의 SPMM 한계를 극복하는 새로운 SPMM 알고리즘 구현
        - 기존 Spark의 SPMM Latency와 새롭게 구현한 SPMM의 Latency를 예측할 수 있는 DNN 회귀 모델 학습
        - 학습된 DNN 회귀 모델을 사용하여, 행렬 곱셈 입력에 따른 최적의 SPMM을 추천해주는 마이크로서비스 구현
        - 구현한 마이크로서비스를 Spark 패키지 내부에 적용 및 배포
    - **결과**
        - 실제 그래프 데이터셋을 사용하여 행렬 곱셈을 진행한 결과, 기존 Spark의 SPMM Latency보다 약 2.2배 향상된 성능을 얻음
        - "Dense or Sparse : Elastic SPMM Implementation for Optimal Big-Data Processing"라는 논문으로 발전하여, IEEE Transactions on Big Data, NO. 1, AUGUST, 2022에 게재됨
    - **주요 사용 기술**
        - Spark, Tensorflow, Docker, AWS 서비스 (ECR, EMR, API Gateway, Lambda)
    - **관련 링크**
        - https://www.computer.org/csdl/journal/bd/5555/01/09858628/1FUYvtRM2gE
        - https://github.com/ddps-lab/dos

- **클라우드 기반의 딥러닝 추론 애플리케이션 (2021/03 ~ 2021/05)**
    - **목표**
        - 삼성전자에서 진행하는 클라우드 아키텍트 특강의 교육 조교로 참여하여, 수강생들의 실습 환경을 구축
    - **기여 내용**
        - AWS CloudFormation을 사용하여 VPC, Subnet, Internet Gateway, Route Table, NAT Gateway 등을 구성하여 실습 환경을 구축
        - 고가용성과 확장성을 만족하는 클라우드 네이티브 딥러닝 추론 애플리케이션을 Classic, Container, Serverless 버전으로 구현
            - Classic 버전: EC2, Load Balancer, Auto Scaling을 사용
            - Container 버전: ECR, ECS, Load Balancer를 사용
            - Serverless 버전: S3, API Gateway, Lambda, EFS를 사용
        - 각 버전별 애플리케이션의 대규모 트래픽 처리 성능을 확인하기 위해, 오픈소스 로드테스트 도구인 Locust를 사용하여 로드테스트 애플리케이션 구현
    - **결과**
        - 구축한 실습 환경을 기반으로 클라우드 아키텍트 특강을 성공적으로 진행
    - **주요 사용 기술**
        - Docker, Tensorflow, AWS 서비스 (EC2, Cloudformation, ECR, ECS, API Gateway, Lambda, EFS)

- **서버리스 기반의 확장 가능한 추천 시스템 (2020/09 ~ 2020/12)**
    - **목표**
        - 서버리스 아키텍처를 활용한 확장 가능한 추천 시스템 구현
    - **기여 내용**
        - 협업 필터링 알고리즘의 추론 단계를 서버리스 기반으로 구현
            - 사용자로부터 입력 받은 아이템 평점 벡터를 API Gateway를 통해 AWS Lambda로 전달
            - Lambda 함수는 입력 받은 아이템 평점 벡터와 S3에 저장된 아이템 유사도 행렬을 내적하여, 해당 사용자의 모든 아이템에 대한 평점을 예측
    - **결과**
        - "서버리스 컴퓨팅 기반의 확장 가능한 추천 시스템”라는 논문으로 발전하여, 한국 정보과학회 학술발표 논문집(2020/12, 16-18, KIISE)에 게재됨
    - **주요 사용 기술**
        - AWS 서비스 (CloudWatch, RDS, Lambda, S3, API Gateway)
    - **관련 링크**
        - https://github.com/unhochoi/scalable-recommender-system-based-on-serverless-computing/blob/main/scalable-recommender-system-based-on-serverless-computing.pdf

- **엣지 가속기 모니터링 시스템 (2021/07 ~ 2021/12)**
    - **목표**
        - Kubernetes Cluster의 Worker Node에서 사용되는 가속기(GPU, TPU 등)에 대한 정보를 Cluster 사용자에게 자동으로 제공하는 서비스 개발
    - **기여 내용**
        - 다양한 엣지 가속기(NVIDIA Jetson TX1, TX2, Nano, Xavier, Google Edge TPU)의 하드웨어 세부 정보를 추출하고 전처리하는 컨테이너 이미지 구현
    - **결과**
        - "Accelerator-Aware Kubernetes Scheduler for DNN Tasks on Edge Computing Environment"라는 논문으로 발전하여, The Sixth ACM/IEEE Symposium on Edge Computing (SEC 2021 Poster session)에 게재됨
    - **주요 사용 기술**
        - Linux, Docker
    - **관련 링크**
        - https://ieeexplore.ieee.org/document/9709001
        - https://github.com/unhochoi/edge-accelerator-monitor

---

### Publications

- **International**
    - **Unho Choi** and Kyungyong Lee, “Dense or Sparse : Elastic SPMM Implementation for Optimal Big-Data Processing”, IEEE Transactions on Big Data, NO. 1, AUGUST, 2022
        - https://www.computer.org/csdl/journal/bd/5555/01/09858628/1FUYvtRM2gE
        - https://github.com/ddps-lab/dos
    - Jungae Park, **Unho Choi**, Seungwoo Kum, Jaewon Moon, and Kyungyong Lee, ‘Accelerator-Aware Kubernetes Scheduler for DNN Tasks on Edge Computing Environment’, The Sixth ACM/IEEE Symposium on Edge Computing (SEC 2021 Poster session)
        - https://ieeexplore.ieee.org/document/9709001
        - https://github.com/unhochoi/edge-accelerator-monitor

- **Domestic**
    - Sungjae Lee, Jaeghang Choi, **Unho Choi**, Kyungyong Lee. Scalable Recommender System based on Serverless Computing, KSC 2020.
        - https://github.com/unhochoi/scalable-recommender-system-based-on-serverless-computing/blob/main/scalable-recommender-system-based-on-serverless-computing.pdf

---

### Certification

- **AWS Certified Cloud Practitioner**
    - AWS 서비스 기반 고가용성, 확장성, 보안성을 갖춘 시스템 설계 역량 증명
    - 취득일 : 2020년 6월 29일
- **SQL Developer**
    - 데이터베이스 및 데이터 모델링에 대한 지식을 바탕으로, SQL 역량 증명
    - 취득일 : 2019년 9월 24일

---

### Education

- **국민대학교 컴퓨터공학과 컴퓨터공학전공 석사 졸업 (2021.03 ~ 2023.02)**
    - 빅데이터 엔지니어링, 분산 처리, 클라우드 컴퓨팅, 머신러닝 연구
- **국민대학교 소프트웨어학과 소프트웨어전공 학사 졸업 (2017.03 ~ 2021.02)**
    - 개발 기반 과목 이수
