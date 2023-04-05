# **Global Infrastructure**

<p align = "center">
    <img src="Pictures\Global Infrastructure.jpg">
    </p>
    <p align = "center"> # Global Infrastructure </p>

## **1. Geography (지리)**
* 2개 이상의 Region을 포함해 데이터와 애플리케이션을 동일한 지리적 위치에 유지해야 하는 데이터 유지 및 규정 준수의 경계<br>
EX) 한국, 오스트레일리아, 뉴질랜드와 같은 나라별 지리적 구분과 아시아 태평양과 같은 지리적 구분도 포함한다

<br>

***

## **2. Region (지역)**
* 고속 네트워크로 연결된 데이터센터의 집합

<br>

***

## **3. Region Pair (지역 쌍)**
* 일반적으로 동일한 지리적 위치 내에 있는 2개의 지역을 쌍을 이룬다.
* 지역 쌍을 통해 비즈니스의 연속성을 보장하고 데이터 손실을 방지하며 데이터 가용성을 보장한다.

<br>

***

## **4. Availability Zone (가용성 영역)**
* Region 내의 물리적 데이터센터 위치
* 데이터센터의 오류나 손상을 대비해 서비스의 논리적 격리와 중복성, 내결함성을 제공

### **▶Availability Zone에서 제공하는 서비스**
* 영역 서비스 (Zonal Services) - 리소스를 특정 영역 (EX) VM, 관리 디스크, IP Address)에 고정한다.
* 영역 중복 서비스 (Zone-Redundant Services) - 플랫폼 영역 간에 자동으로 복제된다 (EX) 영역 중복 저장소)
* 항상 사용 가능한 서비스 (Always-available Services) - 모든 Azure Region에서 항상 사용 가능하며 Zone 전체 가동 중단 및 Region 전체 가동 중단에 탄력적이다.

<br>

***


