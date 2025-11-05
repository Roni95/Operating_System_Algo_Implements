# 🖥️ Operating System Algorithms (C Implementation)

Welcome to my **Operating System Algorithms Repository**!  
This repository contains **C implementations** of core concepts taught in Operating System (OS) courses — including **process scheduling**, **deadlock avoidance**, and **process synchronization**.  

These programs are designed for students, researchers, and enthusiasts aiming to understand how an OS manages processes, memory, and concurrent execution at the algorithmic level.

---

## ⚙️ Topics Covered

### 🧩 Process Scheduling Algorithms

1. **First Come First Serve (FCFS)**  
   📄 `first_come_first_out.c`  
   ➤ The simplest CPU scheduling algorithm that executes processes in the order they arrive.

2. **Shortest Job First (SJF)**  
   📄 `shortest_job_first.c`  
   ➤ Selects the process with the smallest burst time to minimize average waiting time.

3. **Priority Scheduling**  
   📄 `priority_scheduling.c`  
   ➤ Executes processes based on priority levels assigned to them.

4. **Round Robin (RR) Scheduling**  
   📄 `round_robin.c`  
   ➤ Allocates equal CPU time slices to each process in a cyclic order, ensuring fairness.

---

### 🔒 Process Synchronization Problems

1. **Producer–Consumer Problem (Bounded Buffer)**  
   📄 `producer_consumer.c` and `bounded_buffer.c`  
   ➤ Demonstrates inter-process communication and synchronization using semaphores.

2. **Readers–Writers Problem**  
   📄 `readers_and_writers.c`  
   ➤ Ensures concurrent read access while preventing write conflicts.

3. **Dining Philosophers Problem**  
   📄 `dining_philosopher.c`  
   ➤ Classic synchronization problem illustrating deadlock and resource sharing control.

4. **Sleeping Barber Problem**  
   📄 `sleeping_barber.c`  
   ➤ Simulates customer–barber synchronization using semaphores and waiting queues.

---

### 🧮 Deadlock Detection and Avoidance

1. **Banker’s Algorithm**  
   📄 `bankers.c`  
   ➤ Implements Dijkstra’s Banker's Algorithm to detect and avoid deadlocks through resource allocation checks.

2. **Resource Allocation Graph (RAG)**  
   📄 `resource_allocation_graph.c`  
   ➤ Models processes and resources in a directed graph to detect potential deadlocks.

---

## 🧠 Learning Objectives

- Understand the **core mechanisms** of an operating system.  
- Implement and simulate **CPU scheduling** and **synchronization algorithms**.  
- Analyze **deadlock conditions**, **race conditions**, and **resource allocation safety**.  
- Strengthen understanding of **semaphores**, **mutual exclusion**, and **process management**.

---

## 🧰 Technologies Used

- **Language:** C  
- **Concepts Covered:**  
  - Process Scheduling  
  - Deadlock Avoidance  
  - Synchronization (Semaphores & Mutexes)  
  - Inter-Process Communication (IPC)

---

## 🚀 How to Run

1. Clone or download the repository.  
2. Open a terminal and navigate to the folder containing the source files.  
3. Compile any file using GCC:  
   ```bash
   gcc filename.c -o output
   ./output
