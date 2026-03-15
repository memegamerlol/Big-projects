⚠️ Educational / Research Repository

This repository contains several experimental malware and proof-of-concept programs created for learning, analysis, and security research purposes. The goal is to explore how malicious software behaves so that developers and security researchers can better understand detection, mitigation, and defensive programming.

These projects are NOT intended for real-world deployment or malicious use.



Even if a program in this repository is labeled "safe", you must always run it inside an isolated virtual machine (VM).

Running these programs directly on your main operating system can:

* Damage your system
* Corrupt files
* Cause unpredictable behavior
* Spread beyond your intended test environment
* Leak system information
  
Recommended precautions:

* Use a Virtual Machine (VM) such as VirtualBox or VMware
* Disable shared folders between host and VM
* Disable network access unless required for testing
* Take VM snapshots before running any sample

If you do not understand how to safely use a VM, do not run these programs.


## Projects

### mars.exe

Mars.exe (also referred to as mars1) is a horror-themed experimental malware project currently in development. It is inspired by the Mandela Virus created by Cyber Soldier, but this project is written entirely from scratch in C#with no reused or "skidded" code.

The goal of the project is to recreate the unsettling atmosphere and behavior of classic horror malware while experimenting with custom payloads and visual effects.

Capabilities currently include:

* Displaying the system IP address
* Displaying the computer name
* Experimental visual and system interaction payloads

This project is still unfinished and may change significantly over time.



### patient zero

Patient Zero is a horror-style experimental program written in C++. The program acts like a small interactive horror experience where different payload stages can be triggered over time.

New stages can be activated by reopening the executable multiple times or by using a batch file that is later created on the desktop.

Features include:

* Multiple payload stages
* Trigger-based progression
* Displaying the system IP address
* Displaying the computer name

If you plan to stream or record this program, be aware that it may reveal system information on screen.



### infinite red

Infinite Red (also known as infinite-blue2) is an experimental virus inspired by Infinite Blue–style malware concepts.

The project focuses on destructive system behavior and visual payload experimentation.

Current features include:

* Master Boot Record (MBR) overwrite
* GDI visual payloads
* A "Red Stream of Death" visual effect

This project is still very buggy and unstable. Running it on real hardware is strongly discouraged. It should only be tested inside a properly isolated virtual machine.

### Computer fuck melter edition 
  * This malware does..
  * Hardware melting
  * Overclocking
  * Not recommended for real hardware

## Purpose of This Repository

This repository exists for:

* Malware education
* Security research
* Demonstrations of malware behavior
* Testing antivirus and detection systems

It should never be used for illegal activity or unauthorized system access.

---

## Disclaimer

The author takes no responsibility for any damage or misuse caused by these programs.

By downloading or executing any file in this repository, you agree that:

* You will only use them in controlled environments
* You understand the risks of running malicious code
* You accept full responsibility for your actions



## Final Reminder

Always run these samples inside a virtual machine.

Never run them on your host system.

and 1 last rule

DO NOT SKID ANY CODE OR VIRUSES CUZ THAT WILL HAVE CONSEQUENCES
