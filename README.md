# Welcome to Application Modernization Factory

<br>

## AMF 과정 참여를 위한 준비
- gather town 입장 : https://app.gather.town/app/9HTmUf3uGr7IR3To/AMF-L3
  - 일단 아바타까지만 생성하시고, 비번은 당일 아침 공지해드립니다.
- [miro.com](https://miro.com/) 가입
- [marimba.team](https://www.marimba.team/) 가입   
**모두 같은 이메일 계정으로 가입해주시고, 가능하다면 gmail 계정으로 가입을 권고합니다.**

<br>

## Time Table
![](./images/AMF-TimeTable-2022-v1.png)

<br>

## 학습 목표 및 강의자료
**Sprint#0**   
| 일차 | 과목명 | 주요학습 내용 |  비고  |
|---|:---:|:---|:---|:---|
|1일차(월)|과정 Orientation|||


**Sprint#1**   
| 일차 | 과목명 | 주요학습 내용 |  비고  |
|---|:---:|:---|:---|:---|

***

### [ Agile Section](./agile/about-agile.md/) 

***

### [ MSA Section ](./msa/about-msa.md/) 

***

### [ ZCP Section ](./cloud-zcp/about-zcp.md/) 

***
### [ AWS Section ](./cloud-aws/about-aws.md/) 

***
### [ Azure Section ](./cloud-azure/about-azure.md/) 

***

### [ DevOps Section ](./devops/devops.md/) 

***
### 실습을 위한 PC 설정 가이드 

- 실습용으로 제공해드린 PC에는 아래 내용이 모두 설치되어 있습니다.
  - 개인용 PC에 설치하고 싶은 경우, 아래 내용을 설치하시면 됩니다.
  - 개인용 PC설치 도중, 문제가 발생할 경우 각 과정별 담당자에게 문의하시기 바랍니다.

- 실습용 노트북 상세 Spec
  - cpu - i7, 메모리 8G


- 설치 SW
  - [ MSA 영역 상세 가이드 ](./MSA/MSA_install.md/)
    - JDK, STS, Lombok, Git, Docker, MariaDB
   
| SW 명 | 버전 | 다운로드 URL |  비고  |
|---|:---:|:---|:---|
| JDK | 11 | https://adoptopenjdk.net/| 자바 개발 도구 오픈소스|
| STS | 4.9.0 | https://spring.io/tools | 이클립스 기반 스프링 애플리케이션 개발 도구 | 
| Lombok | 1.18.20 |  http://projectlombok.org/download.html | 자바 코드 경량화 라이브러리 |
| Git | 2.31.1 | http://git-scm.com/downloads | 소스 형상 관리 도구 |
| Docker | 20.10.5 | http://docker.com/products/docker-desktop | 애플리케이션 컨테이너 관리 도구 |
| MariaDB | 10.5.8 | https://mariadb.com/downloads | 관계형 데이터 베이스 |
| Choco	| | https://chocolatey.org/install	| kustomize 등을 설치하기 위한 목적으로 윈도우 패키지 관리 매니져를 선행 설치 |
| kustomize	| 3.9.1	 | https://community.chocolatey.org/packages/kustomize | 설치 - choco install kustomize <br> 삭제 - choco uninstall kustomize |
| kubectl	| | https://kubernetes.io/ko/docs/tasks/tools/install-kubectl-windows/ | 설치 - choco install kubernetes-cli	<br>< 삭제 - choco uninstall kubernetes-cli |
| maven	| 3.8.1	| https://community.chocolatey.org/packages/maven | * 로컬 환경에서 애플리케이션 빌드 목적으로 설치<br> 설치 - choco install maven	 <br> 삭제 - choco uninstall maven | 
| postman	| 8.3.1	| https://dl.pstmn.io/download/latest/win64	| 기능(API) 테스트 |
| postman desktop agent	| 0.3.4	| https://dl-agent.pstmn.io/download/latest/win64	| 기능(API) 테스트 |
| Node.js	| 14.16.1	| https://nodejs.org/ko/download/	| 기능(API) 테스트 |
| newman	| 5.2.3 |	Node.js (& NPM) 설치 후... <br>$ npm install -g newman <br>$ npm install -g newman-reporter-html <br>$ npm install -g newman-reporter-htmlextra <br> | 기능(API) 테스트 |
| JMeter | 5.4.1 | https://jmeter.apache.org/download_jmeter.cgi | 성능 테스트 |


<br>

<EOF>