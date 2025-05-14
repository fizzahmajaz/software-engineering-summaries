# 📘 Operating System (CS604) – Midterm Content Summary

This document contains the **complete midterm summary** of the course **Operating Systems (CS604)**.  
It is based on lectures **1 to 22**, grouped into logical sections, and designed to help students **understand and revise quickly** before exams.

---

## 📋 Table of Contents

1. [Group 1: OS Basics & UNIX](#group-1-os-basics--unix)
2. [Group 2: Process Concepts](#group-2-process-concepts)
3. [Group 3: Threads & CPU Scheduling](#group-3-threads--cpu-scheduling)
4. [Group 4: Synchronization](#group-4-synchronization)
5. [Group 5: Deadlocks](#group-5-deadlocks)
6. [🧠 Mind Map](#-mind-map)

---

## Group 1: OS Basics & UNIX

**Lectures 1–4**

- **What is OS? Why needed?**
- Types of OS: Batch, Time-Sharing, Real-Time.
- Concepts: Traps, Interrupts, Signals.
- Components: Kernel, Shell, System Calls.
- UNIX/Linux Structure: root, home, bin, etc.
- Commands: `ls`, `cd`, `pwd`, `mkdir`, `rmdir`, `man`.

---

## 📘 Group 2: Process Concepts

**Lectures 5–8**

- What is a Process?
- Process States: new, ready, running, waiting, terminated.
- PCB (Process Control Block)
- Context Switching
- Process Creation (`fork()`), Termination, Orphan, Zombie.
- `ps`, `kill`, `top`, `nice`.

---

## 📘 Group 3: Threads & CPU Scheduling

**Lectures 9–13**

- Thread vs Process
- Multithreading Benefits & Models
- Scheduling Concepts: CPU burst, IO burst, preemptive vs non-preemptive.
- Scheduling Algorithms:
  - FCFS
  - SJF
  - SRTF
  - Round Robin
  - Priority Scheduling

---

## 📘 Group 4: Synchronization

**Lectures 14–18**

- Critical Section Problem
- Peterson’s Algorithm
- Hardware Solutions: test-and-set, mutex locks
- Semaphores: Binary & Counting
- Classic Problems:
  - Bounded Buffer
  - Reader-Writer
  - Dining Philosophers

---

## 📘 Group 5: Deadlocks

**Lectures 19–22**

- What is a Deadlock?
- Four Conditions of Deadlock:
  1. Mutual Exclusion
  2. Hold and Wait
  3. No Preemption
  4. Circular Wait
- Resource Allocation Graph
- Methods:
  - Deadlock Prevention
  - Deadlock Avoidance (Banker’s Algorithm)
  - Deadlock Detection
  - Recovery

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

![image](https://github.com/user-attachments/assets/6978b56f-724d-4e89-9e66-44f2c7cdcb23)
