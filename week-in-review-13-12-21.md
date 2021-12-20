## AWS 주간 소식 모음 - 2021년 12월 13일 

### 주요 AWS 최신 뉴스
- AWS 보안 공지 – Apache Log4j2 이슈(CVE-2021-44228) (2021-12-10)
  - Log4j는 Java 기반의 오픈소스 로그 유틸리티로 프로그램 작성 및 실행 중 로그를 남기기 위해 사용됩니다.
  - 이번 취약점은 JNDI(Java naming and Directory Interface) 인젝션 취약점으로 이를 악용하여 원격 코드 실행(RCE, Remote Code Execution)도 가능하며, CVSS 스코어 10점 만점 중 10점으로 가장 높은 위험도를 가진 취약점입니다.

- Amazon Lex, AWS CloudFormation 지원 시작 (2021-12-11)
  - Amazon Lex는 대화형 인터페이스를 애플리케이션에 구축하기 위한 자연어 처리(NLU)를 사용하는 AI 서비스입니다.
  - CloudFormation은 AWS에서 제공하는 IaC(Infra as a Service) 서비스로 인프라를 코드로 처리하여 AWS 및 서드파티 리소스를 모델링, 프로비저닝 및 관리할 수 있는 서비스입니다.

- Amazon Route 53, API 작업 업데이트 (2021-12-10)
  - Amazon Route 53은 도메인 주소를 IP주소로 변환하여 최종 사용자에게 인터넷 애플리케이션을 라우팅해주는 DNS 서비스입니다.
  - 이번에 추가된 기능은 AWS 콘솔에서만 설정할 수 있었던 작업을 HTTP 통신을 통해 작업할 수 있도록 업데이트 되었습니다.

- AWS Network Firewall, AWS 관리형 규칙 지원 (2021-12-10)
  - AWS Network Firewall은 모든 Amazon VPC에 대한 필수 네트워크 보호 기능을 쉽게 배포할 수 있는 관리형 서비스입니다.
  - Amazon VPC란, 다른 고객과 완벽하기 논리적으로 격리된 네트워크 공간을 제공하여 프로비저닝하여 가상 네트워크에서 AWS 리소스를 만드는데 사용하는 리소스입니다.

- AWS App2Container, Linux 기 .NET의 컨테이너화 지원 (2021-12-10)
  - A2C는 .NET과 Java 애플리케이션을 컨테이너화된 애플리케이션으로 현대화하는 명령줄 도구입니다.

- AWS Systems Manager, 애플리케이션 수준 비용 보고 지원 (2021-12-09)
  - AWS Systems Manager는 AWS에서 인프라를 보고 제어하기 위해 사용할 수 있는 서비스로써, 운영 데이터를 보고 운영 태스크를 자동화할 수 있으며 관리형 인스턴스를 검사하고 탐지된 정책 위반을 보고하거나 시정 조치를 취해 보안 및 규정 준수를 유지하는데 도움이 되는 기능입니다.
  - 이번 지원 기능은 콘솔 내에서 애플리케이션 및 애플리케이션 구성 요소의 비용을 보고 시각화할 수 있습니다.

- Amazon Redshift, 단일 노드 RA3.xlplus 클러스터 출시 (2021-12-10)
  - Amazon Redshift는 클라우드에서 완벽하게 관리되는 PB급 데이터 웨어하우스 서비스로, 작게는 수백 GB부터 PB 이상까지 데이터를 확장할 수 있는 기능입니다.
  - 이번에 추가된 기능은 EC2의 지원 인스턴스가 추가된 것처럼 Redshift에서 사용할 수 있는 클라스터가 추가되었다는 내용입니다.

- Amazon Polly, 일본 남성 목소리 Takumi 소개 (2021-12-07)
  - Amazon Polly란, TTS를 지원하는 클라우드 서비스로 여러 언어와 다양한 음성을 지원합니다.
  - 이번에 추가된 기능은 일본 남성의 새로운 목소리가 추가되었다는 내용입니다.

- Amazon Pinpoint, 일회용 비밀번호(OTP) 관리 기능 추가 (2021-12-07)
  - Amazon Pinpoint란, 푸시 알림, 이메일, SMS 메세지 및 음성 메세지를 전송할 수 있는 AWS 서비스입니다. 서울리전에서 이용이 가능하지만 음성 및 는 SMS 전송을 지원하지 않습니다.
  - 이번에 추가된 기능은 단일 로그인 시도 또는 거래를 위해 사용자를 인증하는 문자열을 자동으로 생성하는 OTP 기능입니다.

- AWS 클라우드 개발 키트(AWS CDK) v2 정식 출시 (2021-12-10)
  - AWS CDK란 프로그래밍 언어를 사용해서 클라우드 인프라를 코드로 정의하고 AWS CloudFormation을 통해 배포하는 오픈 소스 소프트웨어 개발 프레임 워크입니다.
  - 이번 v2 버전에서는 JavaScript, TypeScript, Python, Java, C#에서 정식 버전으로, Go에서 개발자 평가판 버전으로 지원됩니다.

<br />

### AWS 제품별 블로그(영문)
- KIXEYE의 베어메탈에서 클라우드로의 마이그레이션 (2021-12-09)
- Amazon WorkSpaces용 AWS Systems Manager 활성화 자동화 (2021-12-11)
- Grafana 및 Amazon CloudWatch Metrics Insights 기반 운영 문제 신속 식별하기 (2021-12-10)
- Amazon VPC 흐름 로그를 활용한 데이터 전송 계산 (2021-12-09)
- AWS AppSync API용 사용자 지정 도메인 이름 소개 (2021-12-07)
- AWS Snowball Edge로 산업현장을 위한 Private 4G/5G 및 영상분석 (2021-12-11)
- 초기 스타트업을 위한 빠른 비용 최적화 전략 (2021-12-10)
- Amazon EBS gp3 볼륨으로 SAP HANA의 퍼시스턴스 레이어 최적화 (2021-12-10)
- Amazon S3 Intelligent-Tiering으로 전환하기 위한 대규모 S3 수명 주기 규칙 자동화 (2021-12-09)
- AWS 서비스로 멀티 리전 애플리케이션 만들기 – 1부, 컴퓨팅, 네트워킹 및 보안 (2021-12-09)
- Amazon SageMaker를 사용한 계층적 예측 (2021-12-11)
- Amazon SageMaker 내장 알고리즘으로 친환경 자동차 충전소 위치 계획 (2021-12-09)
- 코드형 인프라로 Amazon EKS 업그레이드 자동화 (2021-12-09)
- EC2 Mac 인스턴스용 Auto Scaling 구현 (2021-12-10)
- AWS App Runner 서비스를 위한 중앙 집중식 관찰 가능성 (2021-12-07)
- 성능 벤치마크 – AWS 및 Azure의 SQL Server 워크로드 (2021-12-10)
