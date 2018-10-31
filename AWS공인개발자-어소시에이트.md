### 1. CloudFormation 템플릿을 사용하여 RDS 읽기 복제본을 구성할 수 있는가?
새로운 CloudFormation 템플릿을 만들면 가능함.

AWS ClodFormation은 개발자와 시스템 관리자에게 AWS 리소스 모음을 쉽게 만들고 관리할 수 있는 방법을 제공합니다. 새로운 CloudFormation 템플릿을 만들 때 RDS를 사용하여 데이터베이스에 대한 읽기 복제본을 설정할 수 있습니다. CloudFormation의 샘플 템플릿을 사용하여 시작할 수 있습니다.

> RDS - Relational Database Service

### 2. 사용자가 ELB를 구성하였다. ELB를 설정하는 동안 사용자가 ELB 상태 검사를 위해 구성할 수 있는 프로토콜은 무엇인가?
ELB는 인스턴스에 대한 상태 검사를 수행하여 트래픽이 정상 인스턴스로만 전환되도록 한다.
ELB는 HTTP, HTTPS, TCP 및 SSL 프로토콜에 대한 상태 검사를 수행할 수 있다.

> ELB - Elastic Load Balancer

### 3. DynamoDB 용 AWS 콘솔을 사용하여 수행할 수 없는 작업은 무엇인가?
다른 데이터베이스 또는 파일에서 데이터 가져오기.

### 4. AWS에서 새로운 애플리케이션을 개발하고 실행해야 할 때, Elastic Beanstalk과 CloudFormation이 광범위한 AWS 리소스에 대한 배포 메커니즘의 도움을 받을 수 있다는 것을 알고 있다. 다음 중 Elastic Beanstalk과 CloudFormation의 차이점을 가장 잘 설명한 문장을 무엇인가?
CloudFormation은 Elastic Beanstalk보다 훨씬 강력하다. 사용자 정의 리소스를 실제로 디자인하고 스크립트 할 수 있기 때문이다.

AWS Elastic Beanstalk은 응용 프로그램을 쉽게 개발하고 실행할 수 있는 환경을 제공한다. 이 도구는 개발자 도구와 통합되어있어 응용 프로그램의 수명주기를 관리할 수 있는 원 스톱 환경을 제공한다. AWS CloudFormation은 광범위한 AWS 리소스를 위한 편리한 배포 메커니즘이다.

### 5. 다음 작업 중 DynamoDB 작업이 아닌 작업은 무엇인가요?
BatchDeleteItem

DynamoDB에서 DeleteItem은 기본 키로 테이블의 단일 항목을 삭제하지만 BatchDeleteItem은 존재하지 않습니다.

### 6. Amazon EC2에서 5분 동안 무료로 사용할 수 있는 Amazon EBS 볼륨의 모니터링 데이터 유형은 다음 중 무엇입니까?
Basic

Basic은 Amazon EBS 볼륨용 모니터링 데이터의 유형으로 5분 동안 무료로 사용할 수 있습니다.

> EC2 : Elastic Compute Cloud

> EBS : Elastic Block Store

### 7. 어느 사용자가 그의 회사의 직원들을 위해 50개의 IAM 사용자를 생성했습니다. 해당 사용자는 모든 직원 사용자들에게 다음과 같이 AWS console 로그인 URL을 만들고 싶어 합니다. https://examCooler.signin.aws.amazon.com/console/. 어떻게 구성하면 될까요?
별칭에는 대문자를 사용할 수 없습니다.

사용자가 AWS IAM 로그인 페이지의 URL에 AWS 계정 ID 대신 회사 이름을 사용하기를 원하면 AWS 계정 ID의 별칭을 만들 수 있습니다. 별칭은 모든 Amazon Web Services 제품에서 고유해야 하며 숫자, 소문자 및 하이픈 만 포함해야 합니다.

> IAM: Identity and Access Management

> bucket: Amazon S3 bucket is public cloud storage resource available in AWS

### 8. AutoScaling이 조건을 기반으로 새 인스턴스를 시작하면 어떤 정책이 정용됩니까?
가장 적은 인스턴스를 AZ에서 인스턴스를 실행합니다.

AutoScaling은 사용자의 AutoScaling 그룹에 대해 사용 가능한 가용 영역간에 인스턴스를 균등하게 배포하려고 시도합니다. Auto Scaling은 가용성이 가장 적은 인스턴스로 가용성 영역에서 새 인스턴스를 시작하려고 시도함으로써이를 수행합니다.
