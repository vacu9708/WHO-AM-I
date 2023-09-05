# 🙌Introduction
- If I were to summarize myself in one sentence, I am a "developer who doesn't give up easily, even when things seem daunting".
- I take the initiative to "challenge difficult tasks" even without being told to. Even when things were daunting and difficult, I found things to study on my own without relying on educational institutions or instructors, and recorded them on GitHub to prevent forgetting what I learned.
- I believe having an "open attitude" to study what I don't know and try to fix what is lacking is important.
- I believe that "team harmony" is important to create good software, not just individual ability. This is because we can solve problems that cannot be solved alone if we work together.

# 🌠Tech skills
### Database
- I have designed DB tables considering [Normalization](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Database/Normalization) and [Indexing](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Database/Indexing).
- I have maintained data consistency using [Transactions](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Database/Transaction), and implemented [distributed transactions](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Server-side/Microservices%20architecture/Saga%20pattern) between microservices.
- I have been utilizing [SQL](https://github.com/vacu9708/Algorithm/tree/main/Algorithm%20traning/SQL%20training) with WHERE, GROUP BY, HAVING, subqueries, etc.
- I have considered and utilized the pros and cons of [UUID and auto-increment keys](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Database/UUID%20VS%20Sequential%20as%20a%20primary%20key).
### Server-side
- I have studied the theory, pros and cons, and usage of [JWT and Session login](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Auth/JWT%2C%20session), and applied them to login implementation.
- I read the official documents of [OAuth](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Auth/OAuth) API and implemented login with Naver and Google.
- I developed inter-process communication and [video conferences](https://github.com/vacu9708/video-conference) using [operating system sockets and websockets](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Socket%20(websocket)).
- I developed features such as JWT revocation and rate limiting for high traffic using [Redis](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Database/Redis).
- I developed a microservice responsible for emails using [Kafka](https://github.com/vacu9708/Tools-etc/tree/main/Messaging%20system(Kafka)) to distribute server load under high traffic through decoupled processing. I applied load balancing by setting up partitions and consumer groups.
- I studied the theory, pros and cons of [microservices](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Server-side/Microservices%20architecture/Concepts), implemented them, and prevented server failure propagation using a circuit breaker.
- I understood the problems of http and set up an [https](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Security/Encryption) server.
### Development methodology and paradigm
- I have studied the concepts and design principles of [Object Oriented Programming](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Development%20methodology%20and%20paradigm/Object%20Oriented%20Programming) and strive to make designs that are easy to understand and good.
- I have studied and applied [Aspect Oriented Programming](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Development%20methodology%20and%20paradigm/Aspect%20Orient%20Programming) in necessary situations.
- I have studied [concurrent programming](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Development%20methodology%20and%20paradigm/Concurrent%20programming) and [synchronization of shared memory](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Operating%20system/Process%20synchronization), and recognize their importance. I have done asynchronous programming using Spring Webflux and JavaScript async-await. I reduced thread overhead by using a thread pool for concurrent email sending.
- I have studied [test codes](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Development%20methodology%20and%20paradigm/DevOps/Testing) and written test codes using junit.
- I try to visualize the architecture by drawing the relationships between components before starting development.
### DevOps, etc
- I have set up a linux server on AWS EC2 for [Cloud](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Web%20development/Server-side/Cloud) and implemented file upload and download using AWS S3.
- I have utilized [Docker and docker-compose](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Development%20methodology%20and%20paradigm/DevOps/Containerization).
- I have set up [CI/CD](https://github.com/vacu9708/Fundamental-knowledge/tree/main/Development%20methodology%20and%20paradigm/DevOps/CI%2CCD) using AWS EC2 + Jenkins + Docker.
- I have used [Git](https://github.com/vacu9708/Tools-etc/tree/main/Git) with commands like clone, pull, push, reset, etc., and have done development by dividing branches and merging through pull requests.
### Java
- I developed a [shopping mall server composed of microservices](https://github.com/vacu9708/Shopping-mall) using Spring.
### Python
- I enjoy [solving algorithm problems](https://github.com/vacu9708/Algorithm/tree/main) with Python.
- I developed an [embedded system that tracks cars and displays parking information on LEDs](https://github.com/vacu9708/Smart-CCTV) using Python, Arduino, Raspberry Pi, etc.
- I developed a [new information notifier](https://github.com/vacu9708/Information_notifier) that notifies updates on specified web pages using Selenium and C#.
### Javascript
- I developed assignments, [To-do lists](https://github.com/vacu9708/To-do-list), video conferences, etc., using Typescript, React, expressJS, nestJS, etc.
### C/C++
- I utilized the characteristic of manual memory management language to [hack game memory](https://github.com/vacu9708/hacking) with winAPI and developed [simple games](https://github.com/vacu9708/Red-light-green-light) using C/C++.
- I have implemented [data structures](https://github.com/vacu9708/Data-structure).
- I developed embedded systems using Arduino.

# 🧑‍🏭Projects
### `2023-06` [Shopping Mall Server Composed of Microservices](https://github.com/vacu9708/Shopping-mall)
<img src="https://github.com/vacu9708/WHO-AM-I/assets/67142421/b388707e-59d4-4d83-b6cf-bf83fbab1d02" width="65%"><br>
<img src="https://github.com/vacu9708/WHO-AM-I/assets/67142421/afd85c78-3db2-4f34-85b7-e2e04dbc0e4b" width="65%"><br>
- Developed necessary APIs for a shopping mall based on Spring.
- Visualized the architecture before writing code.
- Strived to handle large-scale traffic with distributed systems, load balancing, message queues, asynchronous processing, Redis, JWT, etc.
---

### `2022-09` [Video Conference](https://github.com/vacu9708/video-conference)
<img src="https://github.com/vacu9708/WHO-AM-I/assets/67142421/17c4c315-af24-4067-8def-6413399343e0" width="70%"><br>
- Developed a web page where more than 3 people can chat and video call using React and the JavaScript built-in API webRTC.
- Applied https to comply with browser security policies.
---

### `2022-05` [Parking Information Notifier](https://github.com/vacu9708/Smart-CCTV)
<img src="https://github.com/vacu9708/WHO-AM-I/assets/67142421/9a6fa318-5d00-458c-bb5e-03a3105114cf" width="70%"><br>
- Developed an embedded system that tracks cars and displays parking information on LEDs using Python, Arduino, Raspberry Pi, etc.
- The goal is to reduce the time wasted when looking for a parking space.
---

### `2020-04` [Guitar Tuner](https://github.com/vacu9708/Guitar-tuner)
![image](https://github.com/vacu9708/WHO-AM-I/assets/67142421/343937f2-4515-4fd1-91eb-ee834690f735)<br>
<img src="https://github.com/vacu9708/WHO-AM-I/assets/67142421/5a4266c7-eaea-4b97-96ae-4e87b6524b30" width="60%"><br>
- Researched how sound analyzers work and developed an embedded system to assist in tuning instruments.
- Gained understanding of how the mathematics of signal processing is applied in real life while studying [Fast Fourier Transform](https://github.com/vacu9708/Signal-processing/tree/main/Fourier%20transform).
---

# 🥇Achievements
- `2022.12.14` Incheon National University LINC 3.0 Business Group [2022 LINC3.0 Capstone Design Competition]
  - "Indoor Parking Lot Parking Space Entry/Exit Prediction Notification Light System", **1st Place**
<br>![image](https://github.com/vacu9708/WHO-AM-I/assets/67142421/26245bd0-e14d-4eeb-97d2-382cf17eaf04)

# 😃Languages
I am a native Korean speaker and enjoy studying foreign languages.
- **English**: Business english
- **Español**: Capable of daily conversation

# Education
Incheon National University, Embedded Systems Engineering, Bachelor's Degree