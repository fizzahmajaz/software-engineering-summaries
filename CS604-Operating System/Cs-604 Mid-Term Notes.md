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

## 📘 Group 1: OS Basics & UNIX

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

Operating System (CS604) Midterm
├── Group 1: OS Basics & UNIX
│ ├── Definition of OS
│ ├── Types: Batch, Time-sharing, Real-time
│ ├── Components: Kernel, Shell, System Calls
│ ├── Traps, Interrupts
│ └── UNIX Commands: ls, cd, pwd, mkdir, etc.
├── Group 2: Processes
│ ├── What is a Process
│ ├── Process States
│ ├── PCB & Context Switching
│ ├── Process Creation & Termination
│ └── Commands: fork, ps, kill
├── Group 3: Threads & Scheduling
│ ├── Threads vs Processes
│ ├── Thread Models
│ ├── Scheduling Types
│ └── Scheduling Algorithms: FCFS, SJF, SRTF, RR, Priority
├── Group 4: Synchronization
│ ├── Critical Section
│ ├── Peterson’s Algorithm
│ ├── Semaphores
│ └── Problems: Producer-Consumer, Readers-Writers, Philosophers
└── Group 5: Deadlocks
├── Conditions for Deadlock
├── Resource Allocation Graph
├── Prevention & Avoidance
└── Banker’s Algorithm, Detection & Recovery

![image](https://github.com/user-attachments/assets/6978b56f-724d-4e89-9e66-44f2c7cdcb23)
