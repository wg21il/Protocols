* Date: 29/11/2020
* Time: 19:00-20:00
* Coordinator: Inbal

# Agenda

| Title | Proposed by | Discussion Length | Issues       |
|----------|-------------|-------------|----------------|
| Executors Naming |   | 60 minutes   | Discuss R1 Of executors naming   |
|           |   | ~1h     |          |

## Documents

* Notice: 
  * The meeting will focus on the papers: "Executors Naming", "Algorithms Naming". Everyone are welcome.   
  * Review on github issue of the paper: https://github.com/cplusplus/papers/issues/914
  * Executors Design document, contains reasoning for the facilities in 'Executors': http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2018/p0761r2.pdf

* References for facilites discussed in 'Executors Naming':
  * connect: [https://wg21.link/P0443] section 2.2.3.5
  * submit: [https://wg21.link/P0443] section 2.2.3.7
  * operation_state (concept): [https://wg21.link/P0443] section 2.2.5
  * sender and reciever: [https://wg21.link/P0443] sections 1.4, 1.6, 2.2.10 (traits)
  * set_done: [https://wg21.link/P0443] section 2.2.3.2
  * scheduler (concept): [https://wg21.link/P0443] section 2.2.8
  * schedule (function / method): [https://wg21.link/P0443] section 2.2.3.8
  * scheduler (implementation in static_thread_pool): [https://wg21.link/P0443] section Thread Pool 2.5
  * attach (implementation in static_thread_pool): [https://wg21.link/P0443] section 2.5.2.3
  * just: [https://wg21.link/P1897] section 3.2
  * let_error: [https://wg21.link/P1897] section 3.9
  * let_value: [https://wg21.link/P1897] section 3.8
  
* [Executors' naming issues (draft)](https://docs.google.com/document/d/1AXgg3-sMhYFNv0UJ95K1XQiNBbk9wQ16t6lY5YVidtQ/edit?usp=sharing).
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

The name "async_operation" is misleading:

| F | A |
|-|-|
| 1 | 5 |

Conclusion: We'll add the name as an alternative proposed by the authors during the discussion, Andrei will add the rational for against (related to std::sync).
The name "execution_connection" is a bad name:

| F | A |
|-|-|
| 5 | 0 |

Conclusion: We'll add the name as an alternative proposed by the authors. We'll also add our caveats (execution doesn't add anything since it's the namespace, connection doesn't add information, etc.)

Andrei: set_done: will add the rational from libunfix. 

Dvir: Will add the streams use case + current streams status, if possible.

Amir: thread_pool::attach: will try to find the origin for the name, if possible.

Inbal: Will reorganize sections in the paper, and edit set_done additional data.
