# 🙌Introduction
### 반갑습니다! 서버 개발자 양영식입니다.
서버 지식을 중심기둥으로, 다양한 분야의 지식을 쌓기위해 노력해오고 있습니다.
- 저를 한 문장으로 요약하면 "막막한 상황에서도 결국 해내는 개발자" 입니다. 해결할 때 까지 웬만하면 `포기하지 않는` 성격을 가지고 있습니다.
- 저는 시키지 않아도 `주도적`으로 `어려운 일에 도전`합니다. 막막하고 어렵더라도 교육 기관 및 강사에 의지하지 않고 공부할 것들을 `스스로` 찾아서 해왔으며, github에 기록해서 습득한 내용을 잊지 않도록 했습니다.
- 모르면 공부해서 해내고, 부족한 점이 있으면 고치려고 하는 `열린 자세`가 중요하다고 생각합니다.
- 좋은 소프트웨어를 만들기 위해선 개인의 능력 뿐만 아니라 `팀의 화합`이 중요하다고 믿고 있습니다. 혼자서 할 수 없는 일도 함께한다면 해결할 수 있기 때문입니다.

# 🌠Tech skills
### Database
- [정규화](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Database/Normalization) 및 [인덱싱](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Database/Indexing)을 고려해 DB 테이블 설계를 해봤습니다.
- [트랜잭션](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Database/Transaction)을 사용해서 데이터의 일관성을 지켜봤으며, 마이크로서비스들 간의 [분산 트랜잭션](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Server-side/Microservices%20architecture/Saga%20pattern)을 구현해봤습니다.
- WHERE, GROUP BY, HAVING, subquery 등 [SQL](https://github.com/vacu9708/Algorithm/tree/main/Algorithm%20traning/SQL%20training)을 활용해오고 있습니다.
- [UUID와 자동 증가 key의 장단점](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Database/UUID%20VS%20Sequential%20as%20a%20primary%20key)에 관해 고민했고 활용해봤습니다.
### Server-side
- [JWT와 Session 로그인 이론, 장단점, 사용법 등](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Auth/JWT%2C%20session)을 공부했고 로그인 구현에 활용했습니다.
- [OAuth](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Auth/OAuth) API 공식 문서를 읽고 네이버로 로그인, 구글로 로그인을 구현해봤습니다.
- [운영체제 소켓과 웹소켓](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Socket%20(websocket))을 활용해 프로세스간 통신, [영상 회의](https://github.com/vacu9708/video-conference)등을 개발했습니다.
- [Redis](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Database/Redis)을 활용해 JWT 폐기, 대규모 트래픽에 대응하기 위한 초당 요청횟수 제한([token bucket 알고리즘](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Server-side/Rate%20limiting)) 등을 개발했습니다.
- [Kafka](https://github.com/vacu9708/Tools-etc/tree/main/Messaging%20system(Kafka))를 활용해 대규모 트래픽에서 decoupled 처리로 서버 부하를 분산하기 위해 이메일 담당 마이크로서비스를 개발해봤습니다. partition을 나누고 consumer group을 설정해 [로드밸런싱](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Server-side/Service%20discovery%2C%20Load%20balancing)을 적용했습니다.
- [마이크로서비스의 이론, 장단점 등](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Server-side/Microservices%20architecture/Concepts)을 공부했고 구현해봤으며 Circuit breaker로 서버 장애의 전파를 방지해봤습니다.
- http의 문제점을 이해하고 [https](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Security/Encryption) 서버를 구축해봤습니다.
### Development methodology and paradigm
- [Object Oriented Programming의 개념 및 설계 원칙](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Development%20methodology%20and%20paradigm/Object%20Oriented%20Programming)에 관해 공부했고 이해하기 쉽고 좋은 설계를 하기 위해 노력합니다.
- [Aspect Oriented Programming](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Development%20methodology%20and%20paradigm/Aspect%20Orient%20Programming)가 필요한 상황에 대해 공부했고 활용해봤습니다.
- [동시성 프로그래밍](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Development%20methodology%20and%20paradigm/Concurrent%20programming) 및 [공유 메모리의 동기화](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Operating%20system/Process%20synchronization)에 대해 공부했고 중요성을 인식하고 있으며 Spring Webflux와 자바스크립트 async-await를 활용해서 비동기 프로그래밍을 해봤습니다. 동시 이메일 전송에 thread pool을 사용해 thread overhead를 줄여봤습니다.
- [테스트 코드](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Development%20methodology%20and%20paradigm/DevOps/Testing)에 관해 공부했고 junit을 이용해 테스트코드를 작성해봤습니다.
- 개발하기 전에 구성 요소 간의 관계를 그려서 아키텍처를 시각화하려고 노력합니다.
### DevOps, etc
- AWS EC2로 [Cloud](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Server-side/Cloud) linux 서버를 구축해봤으며 AWS S3를 이용한 파일 업로드, 다운로드를 구현해봤습니다.
- [Docker와 docker-compose](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Development%20methodology%20and%20paradigm/DevOps/Containerization)를 활용해봤습니다
- AWS EC2 + Jenkins + Docker를 활용해 [CI/CD](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Development%20methodology%20and%20paradigm/DevOps/CI%2CCD)를 구축해봤습니다.
- clone, pull, push, reset 등 [Git](https://github.com/vacu9708/Tools-etc/tree/main/Git)을 활용해봤고 branch를 나누고 pull request로 merge하는 개발을 해봤습니다.
### Java
- Spring을 활용해서 [마이크로서비스로 구성된 쇼핑몰 서버](https://github.com/vacu9708/Shopping-mall)를 개발했습니다.
### Python
- Python으로 [알고리즘 문제 푸는 것](https://github.com/vacu9708/Algorithm/tree/main)을 좋아합니다.
- Python, Arduino, Raspberry Pi, 인공지능 등을 활용해서 [차를 추적하고 주차정보를 LED로 보여주는 임베디드 시스템](https://github.com/vacu9708/Smart-CCTV)을 개발했습니다.
- Selenium과 C#을 활용해 지정한 웹 페이지의 업데이트 내용을 알려주는 [새 정보 알리미](https://github.com/vacu9708/Information_notifier)를 개발했습니다.
### Javascript
- Typescript, React, expressJS 및 다른 기술들을 활용해 [To-do list](https://github.com/vacu9708/To-do-list), 영상 회의 등을 개발했습니다.
- nestJS를 이용해 [과제](https://github.com/vacu9708/nestjs_assignment_before_interview)를 수행했습니다.
### C/C++
- [자동 메모리 관리](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Etc/Automatic%20memory%20management)가 아닌 수동 메모리 관리 언어라는 특징을 이용해 winAPI로 [게임 메모리를 해킹](https://github.com/vacu9708/hacking)해봤고 [간단한](https://github.com/vacu9708/Red-light-green-light) [게임](https://github.com/vacu9708/Dodge-pieces-of-poop)들을 개발해봤습니다.
- [자료구조들](https://github.com/vacu9708/Data-structure)을 구현해봤습니다.

# 🧑‍🏭Projects
### `2023-06` [마이크로서비스로 구성된 쇼핑몰 서버](https://github.com/vacu9708/Shopping-mall)
<img src="https://github.com/vacu9708/WHO-AM-I/assets/67142421/b388707e-59d4-4d83-b6cf-bf83fbab1d02" width="80%"><br>
- Spring을 기반으로 쇼핑몰에 필요한 API 개발
- 개인 프로젝트지만 팀 프로젝트처럼 하기 위해 브랜치를 나눠서 개발
- 코드 작성 전에 아키텍처를 시각화
- 분산 시스템, 로드밸런싱, Message queue, 비동기 처리, Redis, JWT 등 대규모 트래픽을 처리하기 위해 노력
---

### `2022-09` [영상 회의](https://github.com/vacu9708/video-conference)
<img src="https://github.com/vacu9708/WHO-AM-I/assets/67142421/17c4c315-af24-4067-8def-6413399343e0" width="80%"><br>
- Javascript 내장 API webRTC를 이용해 3명 이상 인원이 채팅 및 영상 통화를 할 수 있는 웹 페이지 개발
- 영상통화의 보안을 위해 https 적용
---

### `2022-05` [주차 정보 알림이](https://github.com/vacu9708/Smart-CCTV)
![image](https://github.com/vacu9708/WHO-AM-I/assets/67142421/9a6fa318-5d00-458c-bb5e-03a3105114cf)
- Python, Arduino, Raspberry pi, 인공지능 등을 이용해 차를 추적하고 주차정보를 LED 로 보여주는 임베디드 시스템 개발.
- 주차공간을 찾을 때 낭비되는 시간을 줄이는 것이 목표
---

### `2020-04` [기타 튜닝기](https://github.com/vacu9708/Guitar-tuner)
![image](https://github.com/vacu9708/WHO-AM-I/assets/67142421/343937f2-4515-4fd1-91eb-ee834690f735)<img src="https://github.com/vacu9708/WHO-AM-I/assets/67142421/aaaaeb42-a92b-4782-b215-1a6c50a5c0ce" width="45%">
- 소리 분석기가 어떻게 작동하는지 연구했고 악기의 튜닝을 도와주는 임베디드 시스템 개발
- [고속 푸리에변환](https://github.com/vacu9708/Signal-processing/tree/main/Fourier%20transform)을 공부하면서 신호처리의 수학이 실생활에서 어떻게 적용되는지 이해를 얻게됨
---

# 🥇Achievements
- `2022.12.14` 인천대학교 LINC 3.0 사업단 [2022 LINC3.0 캡스톤디자인 경진대회]
  - "옥내 주차장 주차면 입출차 예측 알림등 시스템", **1위**
<br>![image](https://github.com/vacu9708/WHO-AM-I/assets/67142421/26245bd0-e14d-4eeb-97d2-382cf17eaf04)

# 😃Languages
한국어 원어민이고 외국어 공부를 즐깁니다.
- **English**: 자유로운 회화 가능
- **Español**: 일상 회화 가능
