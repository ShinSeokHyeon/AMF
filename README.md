# Welcome to Application Modernization Factory



### 입과자 사전 설문 
- AMF 과정 진행을 위해 몇가지 정보가 필요합니다. 링크를 클릭하여 설문을 작성해 주세요~ :   
   ▶︎▶︎ [설문조사 시작](https://url.kr/k7vjf2)

<br>

### 작업공간 안내
- 본 과정의 일정 및 공식 자료와 각 조별 산출물은 myshare에서 관리합니다.
  - 3차수 ▶︎ https://myshare.skcc.com/pages/viewpage.action?pageId=113477047
- myshare 공간은 사번과 VDI 비번으로 로그인 가능합니다.
- myshare 로그인 실패할 경우(계정이 없거나 초기화가 되지 않은 경우 등.... ), devops4u@sk.com으로 계정 및 권한을 요청하십시오.

<br>

### 종료 설문 
- AMF 과정을 지속적으로 개선하기 위해 여러분의 소중한 의견이 필요합니다. 퇴소 전까지 종료 설문 부탁드립니다.   
   ▶︎▶︎ [종료 설문](https://url.kr/dvth1j) <br>
  ![](/images/amf-post-questionaire.png)
<br>

***
### [ Agile Section](./Agile.md/) 

***

### [ MSA Section ](./MSA.md/) 

***

### [ Cloud Section ](./cloud.md/) 

***

### [ DevOps Section ](./devops.md/) 

***
### 실습을 위한 PC 설정 가이드 

- 실습용으로 제공해드린 PC에는 아래 내용이 모두 설치되어 있습니다.
  - 개인용 PC에 설치하고 싶은 경우, 아래 내용을 설치하시면 됩니다.
  - 개인용 PC설치 도중, 문제가 발생할 경우 각 과정별 담당자에게 문의하시기 바랍니다.

- 실습용 노트북 상세 Spec
  - cpu - i7, 메모리 8G


- 설치 SW
  - [ MSA 영역 상세 가이드 ](./MSA_install.md/)
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