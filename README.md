# OPERATING SYSTEMS – ASSIGNMENT 1

## Evaluation and Design of Operating Systems for a Smart Hospital

### Student Details
- Name: Ram Charan
- course: Operating Systems
- course code: csa0412
- reg no: 192425198

## Project Overview

This repository contains the complete work for Operating Systems Assignment 1.

The assignment focuses on operating system concepts, system calls, process management, memory management, thread management and performance evaluation in a Smart Hospital environment.

All practical experiments were performed using Kali Linux running in Oracle VirtualBox on a Windows 11 laptop.

## Software and Tools Used

| Tool | Version |
|---|---|
| Operating System | Kali Linux |
| Host OS | Windows 11 |
| Virtualization | Oracle VirtualBox |
| GCC Compiler | 15.2.0 |
| strace | 7.2 |
| Git | 2.53.0 |
| Programming Language | C |

## Assignment Tasks

| Task | Description |
|---|---|
| Task 01 | Operating System Requirements |
| Task 02 | Types of Operating Systems |
| Task 03 | Operating System Structures |
| Task 04 | Operating System Services |
| Task 05 | Examination of System Calls |
| Task 06 | Evaluation of System Call Costs |
| Task 07 | Process Control System Calls |
| Task 08 | CPU States and Protection |
| Task 09 | Memory Hierarchy and I/O Systems |
| Task 10 | Performance Measurement and Comparison |
| Task 11 | Operating System Plan and Recommendation |
| Task 12 | Re-evaluation and Design Challenge |

## Practical Work

### Task 05 – System Calls
- Implemented file creation, reading and writing.
- Used open(), read(), write() and close().
- Observed system calls using strace.

### Task 06 – System Call Costs
- Compared different buffer sizes.
- Measured read() system-call frequency.
- Used strace and time utilities.

### Task 07 – Process Control
- Implemented process creation using fork().
- Used execvp() and waitpid().
- Traced process-related system calls.

### Task 10 – Performance Measurement
- Created 1,000 processes.
- Created 1,000 threads.
- Measured execution time and memory consumption.
- Compared process and thread performance.

## Experimental Results

### Buffer Size Comparison

| Buffer Size | read() Calls |
|---|---:|
| 1 Byte | 10,000 |
| 512 Bytes | 20 |
| 4096 Bytes | 3 |

### Process and Thread Comparison

| Measurement | Processes | Threads |
|---|---:|---:|
| Total Count | 1,000 | 1,000 |
| Execution Time | 0.312232 sec | 0.123622 sec |
| Average Time | 312.232 µs | 123.622 µs |
| Exit Status | 0 | 0 |

## Repository Contents

This repository includes:

- Task 1 to Task 12 assignment reports.
- C programs and practical implementations.
- Program execution outputs.
- Practical screenshots and experimental results.

## Learning Outcomes

- Understanding operating system architecture.
- Working with Linux system calls.
- Process creation and management.
- Thread creation and synchronization.
- Memory management concepts.
- System-call tracing using strace.
- Performance analysis using Linux utilities.

## Conclusion

This assignment provided practical knowledge of operating system concepts and their implementation using C programming in Kali Linux.

The experiments helped understand system calls, process management, thread management and performance measurement.

