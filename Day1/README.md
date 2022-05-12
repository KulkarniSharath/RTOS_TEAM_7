## What is an RTOS?

A real-time operating system (RTOS) is an operating system (OS) that runs multi-threaded applications and can meet real-time deadlines.

Most RTOS include a scheduler, resource management, and device drivers.

There are 2 types of OS i.e General Purpose Operating System(GPOS) and Real-Time Operating System(RTOS)

* A *task* is a set of instructions loaded into memory. It can also mean some unit of work or goal that needs to be accomplished.
* A *thread* is a unit of central processor (CPU) utilization with its own program counter and stack memory.
* A *process* is an instance of a computer program. A process may have multiple threads.

Most RTOS are designed to run on microcontrollers and the microcontroller which we are using is the STM32F407G.

![IMG20220506153547](https://user-images.githubusercontent.com/98825618/168006561-246ee319-f9e6-4ee9-8120-895ebb42c1b7.jpg)

Advantage of using RTOS :
* RTOS can run multiple independent activities.
* Support Complex communication Protocols (TCP/TI. I2c, CAN, USB, etc). These protocols come with RTOS as a library provided by the RTOS vendors.
* File System.
* GUI (Graphical User Interface).

Basic elements of RTOS :
* Scheduler
* Scheduling Points
* Context Switch Routine
* Definition of a Task
* Synchronization
* The mechanism for inter-task communication
