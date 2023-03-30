# **Cloud Computing**

## **1. Cloud Computing**
* CSP가 인터넷을 통해 컴퓨팅 서비스를 사용자에게 제공하는 것
* 컴퓨팅 서비스 : 서버, 네트워크, 스토리지 등 IT 인프라 포함 다양한 IT 서비스 (ML, AI, IoT 등)

→ **CSP (Cloud Service Provider)** - 클라우드 서비스 제공자 EX) AWS, Microsoft Azure, GCP

→ **MSP (Managed Service Provider)** - 클라우드 도입, 컨설팅, 이전, 운영 관리, 보안 등의 서비스를 지원하는 기업

<br>

***

## **2. 사용량 기반 모델 (CapEx  OpEx)**
* 클라우드 컴퓨팅 = OpEx

→ **OpEx** - 시간 지남에 따라 서비스 운영하는데 지출되는 비용

→ **CapEx** - 유형의 리소스를 구입하거나 보호하기 위한 일회성 선불 지출 비용

<br>

***

## **3. Cloud Computing Deployment Model (배포 모델)**

### **▶ Public Cloud**
* 인터넷 접속 가능한 모든 사용자들을 위한 서비스 운용 형태
* 클라우드 서비스를 구매하려는 모든 사용자가 리소스에 액세스하고 사용 가능

EX) AWS, Microsoft Azure, GCP 등

### **▶ Private Cloud**
* 특정 기업 또는 특정 사용자만을 위한 서비스 운용 형태
* 기업 및 기관 내부에 클라우드 서비스 환경 구성하여 제한적 서비스 제공

### **▶ Hybrid Cloud**
* 두 가지 이상의 클라우드 배포 모델로 구성된 클라우드 환경 운용 형태

EX) Azure Stack - Microsoft 사의 Hybrid Computing Appliance

### **▶ Multi Cloud**
* 2개 이상의 CSP의 클라우드 서비스를 사용하는 운용 형태

<br>

***

## **4. Cloud Computing Service Model (서비스 모델)**

### **▶ IaaS (Infrastructu)re as a Service)**
* 물리적 자원을 가상화하여 제공
* 서버, 스토리지 등의 인프라가 가상화된 환경 (데이터 센터에서의 공간 임대)

### **▶ PaaS (Platform as a Service)**
* 소프트웨어 개발, 테스트 및 배포를 돕는 플랫폼 가상화하여 제공
* 인프라 위에 사용자가 원하는 서비스를 개발할 수 있는 환경 제공

### **▶ SaaS (Software as a Service)**
* 사용자가 사용하는 소프트웨어를 가상화하여 제공
* 응용프로그램 서비스 형태로 제공하여 서비스를 사용하는 환경

<br>

<p align = "center">
    <img src="Pictures\Cloud Computing Service Model.jpg">
    </p>
    <p align = "center"> # Cloud Computing Service Model </p>

흰색 : 기업 관리 영역 <br>
<span style="color:#ffd33d">노란색</span> : 서비스로 제공

Runtime : 애플리케이션을 실행하는 데 사용되는 리소스 라이브러리<br>
Middleware : OS와 애플리케이션 사이에서 OS가 제공하는 서비스 이외에 추가적인 서비스를 제공하는 소프트웨어

<br>

***

## **5. Cloud Computing Features**

### **▶ High-Availability (고가용성)**
* 운영 중지 없이 장시간 서비스 가동 시간을 보장

### **▶ Scalability (확장성)**
* 작업 부하에 따라 직접 자원을 늘리거나 줄일 수 있다

### **▶ Elasticity (탄력성)**
* 작업 요구사항에 따라 자원을 자동으로 늘리거나 줄일 수 있다
  
### **▶ Agility (민첩성)**
* 컴퓨팅 자원 요구에 빠르게 응답한다

### **▶ Fault tolerance (내결함성)**
* 구성요소나 서비스 일부에 문제가 생겨도 시스템이 계속 작동할 수 있는 기능

### **▶ Disaster Recovery (재해복구)**
* 클라우드 서비스를 중단시킨 이벤트가 발생했을 때 이를 자동으로 복구하거나 빠르게 서비스를 재가동 시킨다

### **▶ 낮은 기술 요구사항**
* 물리적 인프라 구축과 유지 관리에 필요한 기술 요구사항이 낮거나 없으므로 서비스 개발과 개선, 유지에 집중할 수 있다

### **▶ 글로벌 서비스**
* 전 세계에 배치된 데이터센터를 통해 전 세계 고객에게 서비스를 배포

### **▶ (Low Latency) 짧은 서비스 대기시간**
* 한정적인 위치에 있는 데이터센터에서 서비스를 제공받는 것의 시간을 단축 가능

### **▶ 예측 가능성**
* 사용자는 클라우드 서비스에서 발생하는 비용을 예측, 분석 가능
* 성능 예측 가능성 - 고객에게 긍정적인 환경을 제공하는 데 필요한 리소스를 예측하는 것에 중점
* 비용 예측 가능성 - 클라우드 지출 비용을 예측하는 것에 중점

### **▶ 보안**
* 더 적은 노력으로 더 빠르고 편리하게 보안을 강화할 수 있다