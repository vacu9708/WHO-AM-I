# 🙌Introduction
- If I were to summarize myself in one sentence, I am a `developer who doesn't give up easily, even when my task seems daunting` I hardly gave up when I encountered challenging situations during development.
- I believe having an `open attitude` to study what I don't know and try to fix what is lacking is important. I am a `fast learner`. I have searched for what to study on my own without relying on educational institutions, and recorded what I studied on my GitHub to remember what I learned.
- I believe that `team harmony` is important to create good software and we should think about how to foster it since we can solve problems that cannot be solved alone if we work together.

# 🌠Tech skills
### Database
- have designed DB tables considering [Normalization](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Database/Normalization) and [Indexing](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Database/Indexing).
- have maintained data consistency using [Transactions](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Database/Transaction), and implemented [distributed transactions](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Server-side/Microservices%20architecture/Saga%20pattern) between microservices.
- have been utilizing [SQL](https://github.com/vacu9708/Algorithm/tree/main/Algorithm%20traning/SQL%20training)
- have considered and utilized the pros and cons of [UUID and auto-increment keys](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Database/UUID%20VS%20Sequential%20as%20a%20primary%20key).
### Server-side
- have studied the theory, pros and cons, and usage of [JWT and Session login](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Auth/JWT%2C%20session), and applied them to login implementation.
- read the official documents of [OAuth](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Auth/OAuth) API and implemented signin with Google(Also signin with naver).
- developed inter-process communication and [video conferences](https://github.com/vacu9708/video-conference) using [operating system sockets and websockets](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Socket%20(websocket)).
- developed features such as JWT revocation and rate limiting using [Redis](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Database/Redis).
- developed a microservice responsible for emails using [Kafka](https://github.com/vacu9708/Tools-etc/tree/main/Messaging%20system(Kafka)) to distribute server load through decoupled processing. I applied [load balancing](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Server-side/Service%20discovery%2C%20Load%20balancing) by setting up partitions and consumer groups.
- studied the theory, pros and cons of [microservices](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Server-side/Microservices%20architecture/Concepts), implemented them, and prevented server failure propagation using a circuit breaker.
- I understood the problems of http and set up an [https](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Security/Encryption) server.
### Development methodology and paradigm
- have studied the concepts and design principles of [Object Oriented Programming](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Development%20methodology%20and%20paradigm/Object%20Oriented%20Programming) and strive to make designs that are easy to understand and good.
- have studied and applied [Aspect Oriented Programming](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Development%20methodology%20and%20paradigm/Aspect%20Orient%20Programming) in necessary situations.
- have studied [concurrent programming](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Development%20methodology%20and%20paradigm/Concurrent%20programming) and [synchronization of shared memory](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Operating%20system/Process%20synchronization), and recognize their importance. I have done asynchronous programming using Spring Webflux and JavaScript async-await. I reduced thread overhead by using a thread pool for concurrent email sending.
- have studied [test codes](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Development%20methodology%20and%20paradigm/DevOps/Testing) and written test codes using junit.
### DevOps, etc
- have set up a linux server on AWS EC2 for [Cloud](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Server-side/Cloud) and implemented file upload and download using AWS S3.
- have utilized [Docker and docker-compose](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Development%20methodology%20and%20paradigm/DevOps/Containerization).
- have set up [CI/CD](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Development%20methodology%20and%20paradigm/DevOps/CI%2CCD) using AWS EC2 + Jenkins + Docker.
- have used [Git](https://github.com/vacu9708/Tools-etc/tree/main/Git) with commands like clone, pull, push, reset, etc., and have done development by dividing branches and merging through pull requests.
- implemented [data structures](https://github.com/vacu9708/Data-structure) using C++ and Python.
- [Study records](https://github.com/vacu9708/Fundamental-knowledge)

# 🧑‍🏭Projects
### `2023-06` [Shopping Mall Server Composed of Microservices](https://github.com/vacu9708/Shopping-mall) (Personal project)
<img src="https://github.com/vacu9708/WHO-AM-I/assets/67142421/b388707e-59d4-4d83-b6cf-bf83fbab1d02" width="65%"><br>
<img src="https://github.com/vacu9708/WHO-AM-I/assets/67142421/afd85c78-3db2-4f34-85b7-e2e04dbc0e4b" width="65%"><br>
- Developed necessary APIs for a shopping mall based on Spring.
- Visualized the architecture before writing code.
- Strived to handle as much traffic as possible with distributed systems, Kafka(load balancing), asynchronous processing, Redis, JWT, etc.
---

### `2022-09` [Video Conference](https://github.com/vacu9708/video-conference) (Personal project)
<img src="https://github.com/vacu9708/WHO-AM-I/assets/67142421/17c4c315-af24-4067-8def-6413399343e0" width="70%"><br>
- Developed a web page where more than 3 people can chat and video call using the JavaScript built-in API webRTC, React etc.
- Applied https to comply with browser security policies.
---

### `2022-05` [Parking Information Notifier](https://github.com/vacu9708/Smart-CCTV) (Academic team project)
<img src="https://github.com/vacu9708/WHO-AM-I/assets/67142421/9a6fa318-5d00-458c-bb5e-03a3105114cf" width="70%"><br>
- Developed an embedded system that tracks cars and displays parking information on LEDs using Python, Arduino, Raspberry Pi, etc.
- The goal is to reduce the time wasted when looking for a parking space.
---

### `2020-04` [Guitar Tuner](https://github.com/vacu9708/Guitar-tuner) (Academic personal project)
![image](https://github.com/vacu9708/WHO-AM-I/assets/67142421/343937f2-4515-4fd1-91eb-ee834690f735)<br>
<img src="https://github.com/vacu9708/WHO-AM-I/assets/67142421/5a4266c7-eaea-4b97-96ae-4e87b6524b30" width="60%"><br>
- Developed an embedded system to assist in tuning instruments using Arduino and python.
- Researched how sound analyzers work and gained understanding of how the mathematics of signal processing is applied in real life while studying [Fast Fourier Transform](https://github.com/vacu9708/Signal-processing/tree/main/Fourier%20transform).

### Side projects
- (Python selenium, C#, etc) : Developed [New information notifier](https://github.com/vacu9708/Information_notifier) that notifies updates on specified web pages using Selenium and C#.
- (Typescript, React, nodeJS, etc) : Developed [To-do list](https://github.com/vacu9708/To-do-list), [nestJS asssignment](https://github.com/vacu9708/nestjs_assignment_before_interview), etc
- (C++, winAPI) : Developed [Hack game memory](https://github.com/vacu9708/hacking) utilizing the characteristic of manual [memory management](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Etc/Automatic%20memory%20management) and [simple](https://github.com/vacu9708/Red-light-green-light) [games](https://github.com/vacu9708/Dodge-pieces-of-poop), etc
---

# 🥇Achievements
- `2022.12.14` 2022 LINC3.0 Capstone Design Competition
  - "Parking space entry/exit notification light system in indoor parking lot", **1st Place**
<br>![image](https://github.com/vacu9708/WHO-AM-I/assets/67142421/26245bd0-e14d-4eeb-97d2-382cf17eaf04)
