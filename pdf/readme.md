# 🙌소개
안녕하십니까! Firmware에 관심있는 개발자 양영식입니다.
- 저는 막막하더라도 웬만하면 포기하지 않습니다. 개발을 하면서 어려운 일에 막힌 적이 많았지만 해결할때까지 잠을 못잤던 경험이 먆습니다.
- 저는 진취적으로 모르는 것들을 공부해왔고 공부한 것들을 기록해 나중에 기억할 수 있도록 했습니다.
- 저는 부족한 점을 개선하기 위한 피드백 수용에 열려있습니다.
- 좋은 소프트웨어를 만들기 위해선 팀의 화합이 중요하고, 어떻게 협업을 잘 할 수 있을지 고민해야된다고 믿습니다.

# 🌠기술
### Database
- [정규화](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Database/Normalization) 및 [인덱싱](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Database/Indexing)을 고려해 DB 테이블 설계를 해봤습니다.
- [트랜잭션](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Database/Transaction)을 사용해서 데이터의 일관성을 지켜봤으며, 마이크로서비스들 간의 [분산 트랜잭션](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Server-side/Microservices%20architecture/Saga%20pattern)을 구현해봤습니다.
- [SQL](https://github.com/vacu9708/Algorithm/tree/main/Algorithm%20traning/SQL%20training)을 활용해오고 있습니다.
- [UUID와 자동 증가 key의 장단점](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Database/UUID%20VS%20Sequential%20as%20a%20primary%20key)에 관해 고민했고 활용해봤습니다.
### Server
- [JWT와 Session 로그인 이론, 장단점, 사용법 등](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Auth/JWT%2C%20session)을 공부했고 로그인 구현에 활용했습니다.
- [OAuth](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Auth/OAuth) API 공식 문서를 읽고 네이버로 로그인, 구글로 로그인을 구현해봤습니다.
- [운영체제 소켓과 웹소켓](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Socket%20(websocket))을 활용해 프로세스간 통신, [영상 회의](https://github.com/vacu9708/video-conference)등을 개발했습니다.
- [Redis](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Database/Redis)을 활용해서 JWT 폐기, [초당 요청횟수 제한](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Server-side/Rate%20limiting) 등을 개발했습니다.
- decoupled 처리로 서버 부하를 분산하기 위해 [Kafka](https://github.com/vacu9708/Tools-etc/tree/main/Messaging%20system(Kafka))를 활용해서 이메일 담당 마이크로서비스를 개발해봤습니다. partition을 나누고 consumer group을 설정해 [로드밸런싱](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Server-side/Service%20discovery%2C%20Load%20balancing)을 적용했습니다.
- [마이크로서비스의 이론, 장단점 등](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Server-side/Microservices%20architecture/Concepts)을 공부했고 구현해봤으며 Circuit breaker로 서버 장애의 전파를 방지해봤습니다.
- http의 문제점을 이해하고 [https](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Security/Encryption) 서버를 구축해봤습니다.
#
### 개발 방법론 및 패러다임
- [Object Oriented Programming의 개념 및 설계 원칙](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Development%20methodology%20and%20paradigm/Object%20Oriented%20Programming)에 관해 공부했고 이해하기 쉽고 좋은 설계를 하기 위해 노력합니다.
- [Aspect Oriented Programming](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Development%20methodology%20and%20paradigm/Aspect%20Orient%20Programming)가 필요한 상황에 대해 공부했고 활용해봤습니다.
- [동시성 프로그래밍](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Development%20methodology%20and%20paradigm/Concurrent%20programming) 및 [공유 메모리의 동기화](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Operating%20system/Process%20synchronization)에 대해 공부했고 중요성을 인식하고 있으며 Spring Webflux와 Javascript async-await를 활용해서 비동기 프로그래밍을 해봤습니다. 동시 이메일 전송에 thread pool을 사용해 thread overhead를 줄여봤습니다.
- [테스트 코드](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Development%20methodology%20and%20paradigm/DevOps/Testing)에 관해 공부했고 junit을 이용해 테스트코드를 작성해봤습니다.
### Etc
- AWS EC2로 [Cloud](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Server-side/Cloud) linux 서버를 구축해봤으며 AWS S3를 이용한 파일 업로드, 다운로드를 구현해봤습니다.
- [Docker와 docker-compose](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Development%20methodology%20and%20paradigm/DevOps/Containerization)를 활용해봤습니다
- AWS EC2 + Jenkins + Docker를 활용해 [CI/CD](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Development%20methodology%20and%20paradigm/DevOps/CI%2CCD)를 구축해봤습니다.
- clone, pull, push, reset 등 [Git](https://github.com/vacu9708/Tools-etc/tree/main/Git)을 활용해봤고 branch를 나누고 pull request로 merge하는 개발을 해봤습니다.
- [자료구조들](https://github.com/vacu9708/Data-structure)을 C++와 Python을 이용해서 구현해봤습니다.
- [공부 기록](https://github.com/vacu9708/Fundamental-knowledge)
### Firmware
- [신호처리](https://github.com/vacu9708/Signal-processing), C++, 마이크로컨트롤러, 전자회로, 리눅스, 디지털 논리회로, VHDL, 반도체공학, 제어공학 등의 수업 수강
#
#
#
#
#
#
#
#
#
#
#
# 🧑‍🏭프로젝트
### `2023-06~2023-07` [마이크로서비스로 구성된 쇼핑몰 서버](https://github.com/vacu9708/Shopping-mall) (개인 프로젝트)
<img src="https://github.com/vacu9708/WHO-AM-I/assets/67142421/b388707e-59d4-4d83-b6cf-bf83fbab1d02" width="65%"><br>
<img src="https://github.com/vacu9708/WHO-AM-I/assets/67142421/afd85c78-3db2-4f34-85b7-e2e04dbc0e4b" width="65%"><br>
- Spring을 기반으로 쇼핑몰에 필요한 API 개발
- 코드 작성 전에 아키텍처를 시각화
- 분산 시스템, Kafka(로드밸런싱), 비동기 처리, Redis, JWT 등 최대한 많은 트래픽을 처리하기 위해 노력
---

### `2022-09 ~ 2022-11` [영상 회의](https://github.com/vacu9708/video-conference) (개인 프로젝트)
<img src="https://github.com/vacu9708/WHO-AM-I/assets/67142421/17c4c315-af24-4067-8def-6413399343e0" width="70%"><br>
- React와 Javascript 내장 API webRTC를 이용해 3명 이상 인원이 채팅 및 영상 통화를 할 수 있는 웹 페이지 개발
- 브라우저의 보안정책을 지키기 위해 보안을 위해 https 적용
---

#
#
#
#
#
#
#
#
#
#
#
#
#
#
#
### `2022-05 ~ 2022-12` [주차 정보 알림이](https://github.com/vacu9708/Smart-CCTV) (대학교 팀 프로젝트)
<img src="https://github.com/vacu9708/WHO-AM-I/assets/67142421/9a6fa318-5d00-458c-bb5e-03a3105114cf" width="70%"><br>
- Python, Arduino, Raspberry pi 등을 이용해 차를 추적하고 주차정보를 LED 로 보여주는 임베디드 시스템 개발.
- 주차공간을 찾을 때 낭비되는 시간을 줄이는 것이 목표
---

### `2020-04` [기타 튜닝기](https://github.com/vacu9708/Guitar-tuner) (대학교 개인 프로젝트)
![image](https://github.com/vacu9708/WHO-AM-I/assets/67142421/343937f2-4515-4fd1-91eb-ee834690f735)<br>
<img src="https://github.com/vacu9708/WHO-AM-I/assets/67142421/5a4266c7-eaea-4b97-96ae-4e87b6524b30" width="60%"><br>
- (Arduino C언어, Python등 활용)악기의 튜닝을 도와주는 임베디드 시스템 개발
- 소리 분석기가 어떻게 작동하는지 연구했고 [고속 푸리에변환](https://github.com/vacu9708/Signal-processing/tree/main/Fourier%20transform)을 공부하면서 신호처리의 수학이 실생활에서 어떻게 적용되는지 이해를 얻게됨
---

### 기타 프로젝트
- (Python selenium, C# 등) : 친구의 요청과 피드백을 받아 지정한 웹 페이지의 업데이트 내용을 알려주는 [새 정보 알리미](https://github.com/vacu9708/Information_notifier) 개발
- (Typescript, React, nodeJS 등) : [To-do list](https://github.com/vacu9708/To-do-list), [nestJS 과제](https://github.com/vacu9708/nestjs_assignment_before_interview) 등 개발
- (C++, winAPI) : [메모리 관리](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Etc/Automatic%20memory%20management)가 수동이라는 특징을 활용해 [게임 메모리 해킹](https://github.com/vacu9708/hacking), [간단한](https://github.com/vacu9708/Red-light-green-light) [게임](https://github.com/vacu9708/Dodge-pieces-of-poop) 등 개발

---

#
# 🥇성취
- `2022.12.14` 인천대학교 LINC 3.0 사업단 [2022 LINC3.0 캡스톤디자인 경진대회]
  - "옥내 주차장 주차면 입출차 예측 알림등 시스템", **1위**
<br>![image](https://github.com/vacu9708/WHO-AM-I/assets/67142421/26245bd0-e14d-4eeb-97d2-382cf17eaf04)
