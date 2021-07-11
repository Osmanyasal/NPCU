[![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-blue.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)<br>
# NPCU
**N**ode based **P**arallel **C**omputing **U**nits(API)
![NPCU_first](https://user-images.githubusercontent.com/22853419/125204863-fb544b80-e287-11eb-9f81-7a90bd5c56ca.png)
NPCU is an api specification that can be implemented on any object oriented programming language.<br>
**With NPCU we intented to allow programmers to be able to write multithreaded applicaitons without knowing any parallel programming concepts.**

Tutorials
=============================
- [What is Actor](#what-is-actor)
- [What is a Node](#what-is-a-node)
    - [Basic Node](#basic-node)
    - [Router](#router)
    - [Gateway](#gateway)
    - [Cluster](#cluster)
- [Configuration Files](#configuration-files)
- [Messaging Protocols](#messaging-protocols)
- [Cancelation Protocols](#cancelation-protocols)
- [Termination Protocols](#termination-protocols)
- [Deamons](#deamons)
- [UML](#uml)
 ----------------------------------

### [What is Actor](#what-is-actor)
![Blank diagram](https://user-images.githubusercontent.com/22853419/125189347-53675f80-e240-11eb-94bd-a298174fdcf7.png)
The thing that you must remember is actors are closed systems so actor interections only happen via message passing. Because they're closed systems all Actors are <b>Thread safe </b> by their nature. We only need to synchronize the queue for input messsges and that's all. 
### [What is a Node](#what-is-a-node)
![Blank diagram](https://user-images.githubusercontent.com/22853419/125190243-d7bbe180-e244-11eb-901f-37f8782c9326.png)

### [Basic Node](#basic-node)
![NPCU](https://user-images.githubusercontent.com/22853419/125205520-4b80dd00-e28b-11eb-9ec6-833ffa57f7ec.png)

### [Router](#router)
![image](https://user-images.githubusercontent.com/22853419/125206362-93a1fe80-e28f-11eb-905f-772b3af23280.png)

### [Gateway](#gateway)
### [Cluster](#cluster) 
### [Configuration Files](#configuration-files)
### [Messaging Protocols](#messaging-protocols)
### [Cancelation Protocols](#cancelation-protocols)
### [Termination Protocols](#termination-protocols)
### [Deamons](#deamons)
### [UML](#uml)
