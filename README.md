# Backend Lab

백엔드 기술을 학습하고 실험한 내용을 기록하는 저장소입니다.  
Spring 기반 서버 개발, 배치 처리, 메시지 큐, 데이터 처리 등  
**백엔드 시스템 설계와 운영에 필요한 기술들을 단계적으로 학습하고 구현합니다.**

이 저장소는 단순 코드 보관이 아니라  
**학습 기록 + 실습 코드 + 개념 정리**를 함께 담는 것을 목표로 합니다.

---

## Tech Stack

### Language
- Java 17

### Framework
- Spring Boot
- Spring Batch

### Data / Infra
- H2 Database
- Apache Kafka (학습 예정)

### Build Tool
- Gradle

---

## Repository Structure

```
Backend_lab
 ├─ batch-system
 │   └─ Spring Batch 학습 프로젝트
 ├─ kafka-lab (planned)
 │   └─ Kafka 실습 프로젝트
 └─ README.md
```

---

## Learning Roadmap

### 1. Spring Batch
배치 처리의 기본 개념과 실행 구조를 이해하고 Job / Step 기반 처리 시스템을 구현합니다.

학습 내용:
- Job / Step 구조
- ItemReader / ItemProcessor / ItemWriter
- JobRepository
- Chunk Processing
- H2 기반 메타데이터 관리

프로젝트:
```
batch-system/
```

---

### 2. Kafka (예정)
이벤트 기반 아키텍처와 메시지 스트리밍 시스템을 학습합니다.

학습 예정 내용:
- Kafka Broker / Topic / Partition
- Producer / Consumer
- Consumer Group
- Kafka Connect
- 이벤트 기반 처리 구조

예정 프로젝트:
```
kafka-lab/
```


## Goal

이 저장소의 목표는 다음과 같습니다:

- 백엔드 시스템 처리 흐름 이해
- 배치 처리 시스템 구현 경험
- 메시지 기반 아키텍처 이해
- 실무에서 사용되는 백엔드 기술 학습
- 기술 학습 기록 포트폴리오화

---

## Author

Backend Developer Lab
