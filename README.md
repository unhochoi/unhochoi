### Introduction

- 안녕하세요! 꾸준하고 겸손한 개발자가 되고 싶은 최운호입니다. :)

---

### Contact & Channel

- GMail : officialunho@gmail.com
- GitHub : https://github.com/unhochoi
- Tec Blog : https://wooono.tistory.com/pages/About
- LinkedIn : https://www.linkedin.com/in/unho-choi-9593871b4/

---

### Skills

- **Data**
    - Spark(Scala), Hadoop, AWS EMR
    - NumPy, Pandas, Scikit-learn, TensorFlow
    - Airflow, Google Cloud Composer

- **DevOps**
    - IaC
        - Terraform, AWS Cloudformation
    - Cluster
        - Google Kubernetes Engine, Amazon ECS
    - CI/CD
        - Google Cloud Build, Github Actions
    - Serverless
        - Google Cloud Functions, Google Cloud Run, AWS Lambda
    - Messaging Services
        - Google Cloud Pub/Sub
    - Monitoring
        - Datadog, Grafana
    - ETC
        - Docker, Kubernetes, Helm, Istio

---

### Experience

- **엔라이튼 서비스인프라팀 매니저 - 전문연구요원 (2023/01 ~ ing)**
    - Cloud Service IAM을 IaC로 관리 - Terraform
    - 사내 Backoffice 시스템에 SSO 적용 - Keycloak
    - CI/CD 고도화 - Datadog Synthetic Test
    - Airflow 구축 및 운영 - Helm Chart
    - RTU 통신 단절 판단 알고리즘 개선 - Airflow
        - 인버터 OFF로 인한 RTU 통신 단절 오인을 개선
    - Airflow Metric Monitoring Pipeline 구축 - StatsD Exporter, Prometheus, Grafana

- **삼성전자 클라우드 아키텍트 특강 교육 조교 (2021/03 ~ 2021/05)**
    - 삼성 개발자분들을 대상으로 하는 3~5일간의 특강에 교육 조교로 참여
        - 고가용성 및 확장성을 만족하는 클라우드 네이티브 딥러닝 추론 애플리케이션을 Classic, Container, Serverless 버전 별로 개발

- **국민대학교 비이공계 학생 대상 프로그래밍 교육 조교 (2021/03 ~ 2022/06)**
    - 비이공계 학생을 대상으로 석사 과정 매 학기 프로그래밍 교육 수업 진행
        - 파이썬 기초 실습
        - 공공 데이터(COVID 19, etc)를 사용한 데이터분석 기초 실습
        - Teachable Machine 을 활용한 인공지능 기초 실습

- **국민대학교 분산 데이터 처리 시스템 연구실 연구 조교 (2020/02 ~ 2022/12)**
    - 빅데이터 엔지니어링, 분산 처리, 클라우드 컴퓨팅, 머신러닝 관련 연구 진행

---

### Projects

- **효율적인 대용량 분산 처리를 위한 Spark 패키지 최적화 (2021/03 ~ 2022/08)**
    - **목표**
        - Spark의 Sparse Matrix Multiplication(SPMM) 패키지를 최적화함으로써, 행렬 곱셈에 따른 최적의 SPMM 을 제공해주는 서비스 구현
    - **기여 내용**
        - 기존 Spark의 SPMM 한계를 극복하는 새로운 SPMM 알고리즘 구현
        - 기존 Spark의 SPMM Latency와 새롭게 구현한 SPMM의 Latency를 예측할 수 있는 DNN 회귀 모델 학습
        - 학습된 DNN 회귀 모델을 사용해, 행렬 곱셈 입력에 따른 최적의 SPMM을 추천해주는 마이크로서비스 구현
        - 구현한 마이크로서비스를 Spark 패키지 내부에 적용 및 배포
    - **결과**
        - 실제 그래프 데이터셋을 사용해 행렬 곱셈을 진행했을 때, 기존 Spark의 SPMM Latency보다 약 2.2배 향상된 결과를 얻음
        - "Dense or Sparse : Elastic SPMM Implementation for Optimal Big-Data Processing"라는 논문으로 발전하여, IEEE Transactions on Big Data, NO. 1, AUGUST, 2022에 게재함
    - **주사용기술**
        - Spark, Tensorflow, Docker, AWS (ECR, EMR, API Gateway, Lambda)
    - **링크**
        - https://ddps-publications.s3.ap-northeast-1.amazonaws.com/dos-tbd.pdf
        - https://www.computer.org/csdl/journal/bd/5555/01/09858628/1FUYvtRM2gE
        - https://github.com/ddps-lab/dos

- **이벤트 로그 분석 서비스 (2020/03 ~ 2020/06)**
    - **목표**
        - IPS 장비로부터 수집된 로그 데이터를 분석하여, 보안 관제사에게 분석 결과를 시각적으로 제공
    - **기여 내용**
        - IPS 장비로부터 수집된 로그 데이터를 Logstash를 거쳐 Elasticsearch에 저장
        - Kibana Dashboard를 통해 로그데이터 분석 및 시각화
    - **결과**
        - 졸업 프로젝트로 진행했으며, 성공적으로 완성했으나, 수상은 하지 못함
    - **주사용기술**
        - ELK Stack
    - **링크**
        - https://github.com/unhochoi/capstone-2020-7

- **클라우드 기반의 딥러닝 추론 애플리케이션 (2021/03 ~ 2021/05)**
    - **목표**
        - 삼성전자에서 진행하는 클라우드 아키텍트 특강의 교육 조교로 참여함으로써, 수강생분들의 실습 환경을 구축
    - **기여 내용**
        - Cloudformation을 사용해 VPC, Subnet, Internet Gateway, Route Table, NAT Gateway를 구성함으로써, 실습 환경 구축
        - 고가용성 및 확장성을 만족하는 클라우드 네이티브 딥러닝 추론 애플리케이션을 Classic, Container, Serverless 버전 별로 구현
            - Classic : EC2, Load Balancer, Auto Scaling 사용
            - Container : ECR, ECS, Load Balancer 사용
            - Serverless : S3, API Gateway, Lambda, EFS 사용
        - 버전 별 애플리케이션의 대규모 트래픽 처리 성능을 확인하기 위해, 오픈소스 로드테스트 툴인 Locust를 사용하여, 로드테스트 애플리케이션을 구현
    - **결과**
        - 해당 실습 환경을 기반으로 클라우드 아키텍트 특강을 성공적으로 마침
    - **주사용기술**
        - Docker, Tensorflow, AWS (EC2, Cloudformation, ECR, ECS, API Gateway, Lambda, EFS)

- **서버리스 기반의 확장 가능한 추천 시스템 (2020/09 ~ 2020/12)**
    - **목표**
        - 서버리스 기반의 추천 시스템 구현
    - **기여 내용**
        - 협업 필터링 알고리즘의 학습과 추론 단계 중, 추론 과정을 서버리스 기반으로 구현
            - 사용자로부터 입력 받은 아이템 평점 벡터를 API Gateway를 사용해 Lambda로 전달
            - Lambda는 입력 받은 아이템 평점 벡터와 S3에 저장되어있는 아이템 유사도 행렬을 내적함으로써, 해당 사용자의 모든 아이템에 대한 평점을 예측
    - **결과**
        - "서버리스 컴퓨팅 기반의 확장 가능한 추천 시스템”라는 논문으로 발전하여, 한국 정보과학회 학술발표 논문집(2020/12, 16-18, KIISE)에 게재함
    - **주사용기술**
        - AWS (CloudWatch, RDS, Lambda, S3, API Gateway)
    - **링크**
        - https://github.com/unhochoi/scalable-recommender-system-based-on-serverless-computing/blob/main/scalable-recommender-system-based-on-serverless-computing.pdf

- **엣지 가속기 모니터링 시스템 (2021/07 ~ 2021/12)**
    - **목표**
        - Kubernetes Cluster의 Worker Node들이 사용하는 가속기들에 대한 정보를, Cluster 사용자에게 자동으로 제공하는 서비스 구현
    - **기여 내용**
        - 엣지 가속기(NVIDIA Jetson TX1, TX2, Nano, Xavier, Google Edge TPU) 별 하드웨어 세부 정보를 추출 및 전처리하는 컨테이너 이미지 구현
    - **결과**
        - "Accelerator-Aware Kubernetes Scheduler for DNN Tasks on Edge Computing Environment"라는 논문으로 발전하여, The Sixth ACM/IEEE Symposium on Edge Computing (SEC 2021 Poster session)에 게재함
    - **주사용기술**
        - Linux, Docker
    - **링크**
        - https://edge-k8s-project.s3.amazonaws.com/Accelerator-Aware+Kubernetes+Scheduler+for+DNN+Tasks+on+Edge+Computing+Environment.pdf
        - https://ieeexplore.ieee.org/document/9709001
        - https://github.com/unhochoi/edge-accelerator-monitor

---

### Publications

- **International**
    - **Unho Choi** and Kyungyong Lee, “Dense or Sparse : Elastic SPMM Implementation for Optimal Big-Data Processing”, IEEE Transactions on Big Data, NO. 1, AUGUST, 2022
        - https://ddps-publications.s3.ap-northeast-1.amazonaws.com/dos-tbd.pdf
        - https://www.computer.org/csdl/journal/bd/5555/01/09858628/1FUYvtRM2gE
        - https://github.com/ddps-lab/dos
    - Jungae Park, **Unho Choi**, Seungwoo Kum, Jaewon Moon, and Kyungyong Lee, ‘Accelerator-Aware Kubernetes Scheduler for DNN Tasks on Edge Computing Environment’, The Sixth ACM/IEEE Symposium on Edge Computing (SEC 2021 Poster session)
        - https://edge-k8s-project.s3.amazonaws.com/Accelerator-Aware+Kubernetes+Scheduler+for+DNN+Tasks+on+Edge+Computing+Environment.pdf
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
