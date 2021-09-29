# **Introduction to Hypervisors**

Course: DevOps

Mod: Week 1

Topic: Virtualization and Hypervisors

Amount of time: 1.5 hours

Author: Thomas Fowler

## **Lesson Objectives**

* Understand the different types of Hypervisors

* Describe the advantages and disadvantages of each
type of Hypervisor

--------------------------------------------

## **What is a Hypervisor?**

A hypervisor is a software that creates, manages, runs, and
allows for communication between virtual machines. A hypervisor
may be thought of as a control plane for managing, grouping, and
sharing virtual machines for purposes of deploying
infrastructure, applications, services, and platforms.

One such hypervisor is VirtualBox and the software used
for the assignments, labs, and projects in this course.
VirtualBox is owned and maintained by Oracle Corporation and is
open source and free to use.

[Screen shot of VirtualBox]

VirtualBox allows for extensive configuration and customization
of virtual machines. It supports serveral different guest
operating systems and allows for virtual storage, virtual
networks, and grouping of virtual machines for more complex
deployments.

## **Hypervisor Types**

There are two flavors of hypervisor in the world of
virtualization. Firstly, and perhaps counterintuitively,
the one most people are familiar with is the Type 2
hypervisor or "hosted" hypervisor. The hosted hypervisor type
sits atop the host operating system and functions as any other
application might, with the exception of emulating hardware,
such as CPUs, system memory, hard drives, network adapters,
etc.

It is important to note that hosted hypervisors also share
system resources with other applications and services running
on the host machine and are therefore constrained by resource
allocation managed by the host machine's operating system.

[Figures here]

The second, Type 1, is what is known as a native hypervisor.
The native hypervisor has the same set of functions and purpose
but is implemented, in practical terms, as its own sort of
operating system. The native hypervisor is installed on a
physical server and is the only interface on the machine with
which to interact. It manages virtual machines or guest
operating systems in the same way a hosted hypervisor does, but
guest operating systems exist at a higher level than the
hypervisor itself.
