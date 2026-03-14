# Linux Experiments 🧪🐧

Hands-on experiments exploring Linux internals, system calls, process behavior, memory layout, and debugging tools.

This repository documents practical experiments performed while studying how user-space programs interact with the **Linux kernel**.

---

## Topics Covered

* Process management
* Signal handling
* System call tracing
* Process memory layout
* Filesystem behavior

---

## Repository Structure

process-management.md → Experiments exploring Linux process creation and management
signals.md → Experiments with Unix signals and process communication
strace-experiments.md → Tracing system calls using `strace`
memory-layout.md → Understanding the memory layout of running processes
filesystem-experiments.md → Exploring filesystem behavior and file operations

---

## Tools Used

Common Linux debugging and inspection tools used in these experiments:

* `strace`
* `ps`
* `top`
* `htop`
* `lsof`
* `procfs`
* `dmesg`

---

## Example Experiment

Tracing system calls of a program:

```bash
strace ls
```

Tracing only file-related system calls:

```bash
strace -e open ls
```

Counting system calls used by a program:

```bash
strace -c ls
```

---

## Goal

The goal of this repository is to understand:

* How programs interact with the Linux kernel
* How processes are created and managed
* How memory is organized inside a process
* How system calls operate internally

---

## Learning Path

This repository is part of a broader systems engineering learning journey:

* linux-lab → Linux fundamentals
* kernel-learning → Linux kernel internals
* embedded-lab → Embedded systems and hardware interfaces
* linux-experiments → Practical Linux experiments

Together, these repositories build a deeper understanding of Linux systems and low-level computing.
