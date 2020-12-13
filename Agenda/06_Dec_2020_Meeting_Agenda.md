* Date: 06/12/2020
* Time: 19:00-20:00

# Agenda

| Title | Proposed by | Discussion Length | Issues       |
|----------|-------------|-------------|----------------|
| Executors Naming |   | 60 minutes   | Discuss R1 Of executors naming   |
|           |   | ~1h     |          |

## Documents

* Notice: 
  * We will focus on a paper suggests naming suggestions for executors. Everyone are welcome.   
  * Review on github issue of the paper: https://github.com/cplusplus/papers/issues/914
  * Please go over: [https://wg21.link/P2238R0], [https://wg21.link/P0330R8], [https://wg21.link/P2096R2], [https://wg21.link/P2029R4], [https://wg21.link/P1787R6]


* References for facilites discussed in 'Executors Naming':
  * operation_state (concept): [https://wg21.link/P0443] section 2.2.5
  * sender and reciever: [https://wg21.link/P0443] sections 1.4, 1.6, 2.2.10 (traits)
  * set_done: [https://wg21.link/P0443] section 2.2.3.2
  * scheduler (concept): [https://wg21.link/P0443] section 2.2.8
  * schedule (function / method): [https://wg21.link/P0443] section 2.2.3.8
  * thread_pool::scheduler (implementation in static_thread_pool): [https://wg21.link/P0443] section Thread Pool 2.5
  * thread_pool::attach (implementation in static_thread_pool): [https://wg21.link/P0443] section 2.5.2.3
  
* [Executors' naming issues (draft)](https://docs.google.com/document/d/1z0FMCi1oW_xM-MbY75-xfJmgaNssumZgyg40jnwCHyo/edit).
* Executors Design document, contains reasoning for the facilities in 'Executors': http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2018/p0761r2.pdf
* [Executors](wg21.link/p0443), take a look at _2.7 Appendix: Executors Bibilography_ for many more references.

# Meeting summary: 
"Executors Naming" paper R1

### Attendees:
-  Inbal Levi
-  Ran Regev
-  Andrei Zissu
-  Dan Raviv
-  Amir Kirsh
-  Dvir Yitachaki

### Minutes:
We've discussed some changes and fixes. We will consider if R1 is ready for the ML on next meeting. (13 Dec)

<br/>
