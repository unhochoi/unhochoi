### Introduction

- 안녕하세요! 꾸준하고 겸손한 데이터 엔지니어가 되고 싶은 최운호입니다.
- 빅데이터 엔지니어링, 분산 처리, 클라우드 컴퓨팅, 머신러닝 등에 관심이 있습니다.
- 학습한 것을 남기기 위해 기술 블로그를 운영 하고 있습니다.
- 데이터에 기반한 의사결정을 통해, 많은 유저에게 맞춤형 서비스를 제공하고 싶은 목표가 있습니다.

----

### Contact & Channel

- GMail : officialunho@gmail.com
- GitHub : [https://github.com/unhochoi](https://github.com/unhochoi)
- Tec Blog : [https://wooono.tistory.com/pages/About](https://wooono.tistory.com/pages/About)
- LinkedIn : [https://www.linkedin.com/in/unho-choi-9593871b4/](https://www.linkedin.com/in/unho-choi-9593871b4/)

----

### Skills

- **Data**
    - Spark(Scala, Python), Hadoop, AWS EMR
    - NumPy, Pandas, Matplotlib
    - Scikit-learn, TensorFlow
    - ELK Stack

- **DevOps**
    - Docker
    - AWS (Route 53, API Gateway, S3, DynamoDB, DocumnetDB, RDS, EC2, ECS, Lambda)
    - Database (MySQL, MongoDB)

- **ETC**
    - Frontend (HTML, CSS, JS)
    - Backend (Django, Flask)
    - Language (Python, Scala, C++, Java, R, Shell Script, Json)

- **Tools & Collaboration**
    - Apache Zeppelin, Eclipse, IntelliJ IDEA
    - Jupyter Notebook, Pycharm, Colab, Rstudio
    - Vim, Atom, Visual Studio Code
    - Jira, Slack, GitHub, Notion

----

### Experience

- **국민대학교 분산 데이터 처리 시스템 연구실 연구 조교 (2020/02 ~ ing)**
    - 담당업무 : 빅데이터 엔지니어링, 분산 처리, 클라우드 컴퓨팅, 머신러닝 연구

- **국민대학교 비이공계 학생 대상 프로그래밍 교육 조교 (2021/3 ~ ing)**
    - 담당업무
        - 비이공계 학생을 대상으로 석사 과정 매 학기 프로그래밍 교육 수업 진행
            - 파이썬 기초 실습
            - 공공 데이터(COVID 19, etc)를 사용한 데이터분석 기초 실습
            - Teachable Machine 을 활용한 인공지능 기초 실습

- **삼성전자 클라우드 아키텍트 특강 교육 조교 (2021/03 ~ 2021/05)**
    - 담당업무
        - 삼성 개발자분들을 대상으로 하는 3~5일간의 특강에 교육 조교로 참여
        - 고가용성 및 확장성을 만족하는 클라우드 네이티브 딥러닝 추론 애플리케이션을 Classic, Container, Serverless 버전 별로 개발
        - 실습 보조 및 질문 처리

- **고부기엔터테이먼트 인턴 (2019/12 ~ 2020/02)**
    - 담당업무 : 프론트 엔드 개발, 서비스 유지보수, 신규 서비스 기획, 서비스 QA

- **위크앤데이 인턴 (2019/06 ~ 2020/08)**
    - 담당업무 : 프론트 엔드 개발

----

### Projects

- **효율적인 대용량 분산 처리를 위한 Spark 패키지 최적화 (2021/03 ~ ing)**
    - 목표
        - Spark 의 Sparse Matrix Multiplication(SPMM) 패키지를 최적화함으로써, 행렬 곱셈에 따른 최적의 SPMM 을 제공해주는 서비스 구현
    - 기여 내용
        - 기존 Spark 의 SPMM 한계를 극복하는 새로운 SPMM 알고리즘 구현
        - 기존 Spark 의 SPMM Latency 와 새롭게 구현한 SPMM 의 Latency 를 예측할 수 있는 DNN 회귀 모델 학습
        - 학습된 DNN 회귀 모델을 사용해, 행렬 곱셈 입력에 따른 최적의 SPMM 을 추천해주는 마이크로서비스 구현
        - 구현한 마이크로서비스를 Spark 패키지 내부에 적용 및 배포
    - 결과
        - 실제 그래프 데이터셋을 사용해 행렬 곱셈을 진행했을 때, 기존 Spark 의 SPMM Latency보다 약 2.2배 향상된 결과를 얻음
    - 주사용기술
        - Spark, Tensorflow, Docker, AWS (ECR, EMR, API Gateway, Lambda)

- **엣지 가속기 모니터링 시스템 (2021/07 ~ 2021/12)**
    - 목표
        - Kubernetes Cluster 의 Worker Node 들이 사용하는 가속기들에 대한 정보를, Cluster 사용자에게 자동으로 제공하는 서비스 구현
    - 기여 내용
        - 엣지 가속기(NVIDIA Jetson TX1, TX2, Nano, Xavier, Google Edge TPU) 별 하드웨어 세부 정보를 추출 및 전처리하는 컨테이너 이미지 구현
    - 결과
        - "Accelerator-Aware Kubernetes Scheduler for DNN Tasks on Edge Computing Environment"라는 제목의 논문으로 발전하여, The Sixth ACM/IEEE Symposium on Edge Computing (SEC 2021 Poster session)에 게재됨
    - 주사용기술 : Linux, Docker, Kubernetes

- **클라우드 기반의 딥러닝 추론 애플리케이션 (2021/03 ~ 2021/05)**
    - 목표
        - 삼성에서 진행하는 클라우드 아키텍트 특강의 교육 조교로 참여함으로써, 수강생분들의 실습 환경을 구축하기 위해, 고가용성 및 확장성을 만족하는 클라우드 네이티브 딥러닝 추론 애플리케이션을 Classic, Container, Serverless 버전 별로 구현
    - 기여 내용
        - Cloudformation을 사용해 VPC, Subnet, Internet Gateway, Route Table, NAT Gateway 를 구성함으로써, 실습 환경 자동화
        - Flask 와 딥러닝 모델을 사용한 간단한 이미지 분류 애플리케이션을 Classic, Container, Serverless 버전 별로 구현
            - Classic 버전의 딥러닝 추론 애플리케이션은, EC2, Load Balancer, Auto Scaling을 사용해 구현
            - Container 버전의 딥러닝 추론 애플리케이션은, ECR, ECS, Load Balancer를 사용해 구현
            - Serverless 버전의 딥러닝 추론 애플리케이션은, S3, API Gateway, Lambda, EFS를 사용해 구현
        - 버전 별 애플리케이션의 대규모 트래픽 처리 성능을 확인하기 위해, 오픈소스 로드테스트 툴인 Locust를 사용하여, 로드테스트 애플리케이션을 구현
    - 결과
        - 해당 애플리케이션을 기반으로 클라우드 아키텍트 특강을 성공적으로 마침
    - 주사용기술
        - Docker, Tensorflow, AWS (EC2, Cloudformation, ECR, ECS, API Gateway, Lambda, EFS)

- **서버리스 기반의 확장 가능한 추천 시스템 (2020/09 ~ 2020/12)**
    - 목표
        - 추천 시스템의 핵심이 되는 협업 필터링 알고리즘을 서버리스 컴퓨팅을 사용해 배포
    - 기여 내용
        - 협업 필터링 알고리즘의 학습과 추론 단계 중, 추론 과정을 서버리스 환경으로 구현
            - 사용자로부터 아이템에 대한 평점 정보를 1xn 의 벡터 형태로 전달받은 뒤, API Gateway를 사용해, 추론 작업을 진행하는 Lambda를 호출하여, 아이템에 대한 평점 정보를 전달
            - 호출된 Lambda는, 전달받은 아이템 평점 정보와 S3에 저장되어 있는 아이템 유사도 행렬을 내적함으로써, 해당 사용자가 각각의 아이템에 대해 가지게 될 평가 점수를 나타내는 1xn 의 벡터를 산출
            - 최종적으로, 해당 1xn 벡터에서 실제로 평가하지 않은 아이템 항목을 추출하여, 가장 평가 점수가 높을 것으로 예상되는 아이템을 k개 선정하여 반환
            - 선정된 k개의 아이템은, 해당 사용자가 관심을 가질 가능성이 가장 높은 것으로 판단될 수 있으며, 이를 활용하여 개인 맞춤형 서비스 제공할 수 있음
    - 결과
        - "서버리스 컴퓨팅 기반의 확장 가능한 추천 시스템”라는 제목의 논문으로 발전하여, 한국 정보과학회 학술발표 논문집(2020/12, 16-18, KIISE)에 게재됨
    - 주사용기술 : AWS (CloudWatch, RDS, Lambda, S3, API Gateway)

- **이벤트 로그 분석 서비스 (2020/03 ~ 2020/06)**
    - 목표
        - 졸업 프로젝트로 진행하였으며, IPS 장비로부터 수집된 이벤트 로그를 분석하여, 보안 관제사에게 분석 결과를 시각적으로 제공하는 서비스를 구현
    - 기여 내용
        - Logstash를 통해 IPS 장비로부터 수집된 로그 데이터를 Elasticsearch에 저장
        - Elasticsearch에 저장되어 있는 로그 데이터를 딥러닝 추론 결과를 바탕으로 라벨링
        - Kibana Dashboard를 통해 Elasticsearch 로그데이터 분석 및 시각화
        - Kibana Dashboard를 Django 기반의 웹과 연동해, 데이터 분석 결과를 보안 관제사에게 시각적으로 제공
    - 결과
        - 해당 프로젝트는 성공적으로 마무리되었으나, 수상은 하지 못했음
    - 주사용기술 : ELK, Django, Tensorflow

----

### Publications

- **International**
    - Jungae Park, **Unho Choi**, Seungwoo Kum, Jaewon Moon, and Kyungyong Lee, ‘Accelerator-Aware Kubernetes Scheduler for DNN Tasks on Edge Computing Environment’, The Sixth ACM/IEEE Symposium on Edge Computing (SEC 2021 Poster session)
- **Domestic**
    - Sungjae Lee, Jaeghang Choi, **Unho Choi**, Kyungyong Lee. Scalable Recommender System based on Serverless Computing, KSC 2020.

----

### Certification

- AWS Certified Cloud Practitioner
    - AWS 서비스 기반 고가용성, 확장성, 보안성을 갖춘 시스템 설계 역량 증명
    - 취득일 : 2020년 6월 29일
- SQL Developer
    - 데이터베이스 및 데이터 모델링에 대한 지식을 바탕으로, SQL 역량 증명
    - 취득일 : 2019년 9월 24일

----

### Education

- 국민대학교 컴퓨터공학과 컴퓨터공학전공 석사 재학 (2021.03 ~ Current)
    - 빅데이터 엔지니어링, 분산 처리, 클라우드 컴퓨팅, 머신러닝 연구
- 국민대학교 소프트웨어학과 소프트웨어전공 학사 졸업 (2017.03 ~ 2021.02)
