# Task Control Block (TCB)

To schedule a task, three techniques are adapted.

Co-operative scheduling :  In this scheme, a task runs, until it completes its execution.

Round Robin Scheduling : Each task is assigned a fixed time slot in this scheme. The task needs to complete its execution. Otherwise, the task may lose its flow, and data generated or it would have to wait for its next turn.

Preemptive Scheduling : This scheduling scheme includes priority-dependent time allocation. Usually, in programs, 256 priority level is generally used. Each task is assigned a unique priority level. While some systems may support more priority levels, and multiple tasks may have the same priorities.

## What is Race Condition?

Occurs when the result of two or more tasks are mutually inclusive.

## Semaphore :

A semaphore (sometimes called a semaphore token) is a kernel object that one or more threads of execution can acquire or release for the purposes of synchronization or mutual exclusion.

A kernel can support many different types of semaphores, including
* Binary Semaphore
* Counting Semaphore
* Mutual‐exclusion (Mutex) semaphores.

## Mutexes :

Are powerful tools for synchronizing access to shared resources
A mutual exclusion (mutex) semaphore is a special binary semaphore that supports
ownership,
recursive access,
task deletion safety, and
one or more protocols for avoiding problems inherent to mutual exclusion.

Problems that may arise with mutexes

Deadlock

priority Inversion

