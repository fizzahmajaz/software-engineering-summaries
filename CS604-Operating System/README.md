# 📘 Operating System (CS604) – Midterm Content Summary

This document contains the **complete midterm summary** of the course **Operating Systems (CS604)**.  
It is based on lectures **1 to 22**, grouped into logical sections, and designed to help students **understand and revise quickly** before exams.

---

## 🧠 Mind Map

<details>
<summary>Group 1: OS Basics & UNIX</summary>

- **Definition of OS**  
  A system software that manages hardware and software resources.

- **Types of OS**  
  - Batch: Executes jobs without user interaction.  
  - Time-sharing: Multiple users access at once (multitasking).  
  - Real-time: Responds to inputs instantly (used in embedded systems).

- **OS Components**  
  - Kernel: Core part; manages resources.  
  - Shell: Interface between user and kernel (CLI/GUI).  
  - System Calls: Used to interact with OS from programs.

- **Traps & Interrupts**  
  - Trap: Software-generated interrupt (e.g., error).  
  - Interrupt: Hardware-generated to gain CPU attention (e.g., I/O).

- **UNIX Commands**  
  ls, cd, pwd, mkdir, rmdir, man

</details>

<details>
<summary>Group 2: Processes</summary>

- **What is a Process**  
  A running instance of a program (active entity).

- **Process States**  
  New, Ready, Running, Waiting, Terminated

- **PCB & Context Switching**  
  - PCB: Stores info about a process (state, ID, PC).  
  - Context Switching: Switching CPU from one process to another.

- **Process Creation & Termination**  
  `fork()`: Create process | `exit()`: Terminate

- **Useful Commands**  
  fork, ps, kill

</details>

<details>
<summary>Group 3: Threads & Scheduling</summary>

- **Threads vs Processes**  
  Threads share resources of a process; lighter, faster.

- **Thread Models**  
  User-level threads, Kernel-level threads

- **Scheduling Types**  
  Preemptive and Non-preemptive

- **Scheduling Algorithms**  
  FCFS, SJF, SRTF, RR, Priority

</details>

<details>
<summary>Group 4: Synchronization</summary>

- **Critical Section**  
  Shared code that must not run by multiple threads at once.

- **Peterson’s Algorithm**  
  Software-based method for mutual exclusion.

- **Semaphores**  
  Binary or Counting, using `wait()` and `signal()`

- **Classic Problems**  
  Producer-Consumer, Readers-Writers, Dining Philosophers

</details>

<details>
<summary>Group 5: Deadlocks</summary>

- **Conditions for Deadlock**  
  Mutual Exclusion, Hold & Wait, No Preemption, Circular Wait

- **Resource Allocation Graph**  
  Visualizes processes and resource holding/waiting

- **Prevention & Avoidance**  
  - Prevention: Remove one condition  
  - Avoidance: Use safe state (e.g., Banker’s Algorithm)

- **Detection & Recovery**  
  Detect deadlock via RAG or wait-for graph  
  Recover by killing/restarting processes

</details>

<details>
<summary>Group 6: Critical Section & Synchronization (Lectures 18–22)</summary>

- Mutual exclusion, progress, bounded waiting  
- Peterson’s algorithm (2-process)  
- Bakery algorithm (n-process)  
- Hardware solutions and semaphores  
- `wait()`, `signal()`, binary and counting semaphores

</details>

![1](https://github.com/user-attachments/assets/98499e43-6aa3-4378-88e9-a1b4ad1626cf)
![2](https://github.com/user-attachments/assets/17eba1b8-107e-43f1-8539-6d23ff8970bd)
![3](https://github.com/user-attachments/assets/688b35f1-bc11-483b-8cfb-afa628d5d6f7)
![4](https://github.com/user-attachments/assets/2871808c-bac8-4ea7-9463-aa9c0b91e1fe)
![5](https://github.com/user-attachments/assets/bbbd8152-bd14-4f3d-95b5-298624e512ba)
![6](https://github.com/user-attachments/assets/6934fbb8-be99-4321-8774-08f42273aa6e)


📄 [Download CS604 Operating System Midterm Notes Mind Map (PDF)]( Operating System  (CS604) – Midterm.pdf)




