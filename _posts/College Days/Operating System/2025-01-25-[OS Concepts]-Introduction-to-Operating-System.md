---
title: "[OS Concepts] Introduction to Operating System"
date: 2025-01-25
categories:
    - Operating System
tags:
    - Operating System
toc: true
toc_sticky: true
toc_label: "Operating System"
---

## Goals of Operating System

An Operating System acts as an intermediary between the user and the hardware of a computer system.
It facilitates the management of hardware resources, such as the CPU and memory, to ensure efficient and convenient operation.


And the goals of an OS can be divided into three main categories:

### Execution of User Programs

The primary goal of an OS is to enable user programs to execute efficiently.
For a user program to run, it requires resources like CPU time and memory.
The OS assigns the appropriate amount of these resources to each program and manages them to ensure smooth execution.

### Convenience in Computer System Usage

The OS simplifies the operation of the computer system for users.
It handles complex tasks, allowing users to interact with the system through simple commands.
For example, a system call is a set of predefined instructions that a program uses to request services from the OS.
Operations like reading data from memory or writing data to storage are performed using system calls.
These abstract the complexity of low-level operations, such as specifying memory addresses in hexadecimal format, making the system more user-friendly.

### Efficient Management of Hardware Resources

Since hardware resources like the CPU, memory, and I/O devices are limited, the OS ensures their efficient allocation among competing processes.
It coordinates and distributes resources to maximize system utilization and avoid conflicts, enabling multiple processes to run concurrently on limited hardware.
