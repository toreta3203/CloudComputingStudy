# **Management Infrastructure**

<p align = "center">
    <img src="Pictures\Management Infrastructure.jpg">
    </p>
    <p align = "center"> # Management Infrastructure </p>

### **▶리소스 관리 체계**
* Tenant → Management Group → Subscription → Resource Group → Resource

## **1. Azure Active Directory**
* Azure 상에서의 Active Directory이며 클라우드 기반 ID 및 액세스 관리 서비스<br>
→ Active Directory - 회사나 조직에서 구성원들의 계정 정보 (ID, Password)와 PC 정보, 각 User에게 정책, 권한 할당 정보 등을 저장하고 있는 일종의 DB

<br>

***

## **2.Tenant**
* Azure AD의 신뢰할 수 있는 전용 인스턴스
* 단일 조직을 나타낸다
* Azure AD에 Tenant 생성하면 ".onmicrosoft.com" 도메인이 기본값으로 설정된다.
* Azure AD가 User를 추가하고, 해당 User의 권한을 할당할 수 있다.

<br>

***

## **3. Management Group (관리 그룹)**
* 하나 이상의 구독에 사용하는 논리적 컨테이너
* 하나 이상의 구독이 존재할 때 각 구독마다 정책, 권한 등 효율적인 관리 불가
* 구독을 그룹화하여 구독에 대한 액세스, 정책 및 규정 준수를 효율적으로 관리

<br>

***

## **4. Subscription (구독)**
* 리소스의 논리적 컨테이너
* 모든 리소스는 하나의 구독에만 연결됨.
* 구독을 사용해 리소스 사용량을 확인하고, 청구 및 지불되는 방식 제어<br>
→ 청구 경계 - Azure 사용에 따른 Azure 계정 청구 방식 결정, 각 구독에 대해 별도의 청구 보고서 및 송장 생성
→ 액세스 제어 경계 - Azure는 구독 Level 에서 액세스 관리를 적용한다.<br>
특정 구독으로 사용자가 프로비저닝하는 리소스에 대한 액세스를 제어할 수 있다.
다른 조직 구조를 반영하기 위해 별도의 구독을 만들 수 있다.

<br>

***

## **5. Resource Group (리소스 그룹)**
* 구독에서 관련 리소스를 그룹화하는데 사용하는 논리적 컨테이너
* 구독 내에서 더 세분화된 그룹화가 가능

<br>

***

## **6. Resource (리소스)**
* Azure에서 관리되는 엔터티<br>
EX) Azure VM, Azure Virtual Network, Storage 등
