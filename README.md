# An-OS-Kernel-from-scratch (x86)

How to create an simple OS Kernel from scratch

# Here is a message dedicated to you

"Constructing a comprehensive knowledge framework is of paramount importance."

## Table of contents:

* [Introduction](#introduction--table-of-contents): If you have an interest in the project's history, kindly read this section. I'd like to share that upon finishing this study project about a minimal operating system (OS/kernel). The most significant insight and genuine experience arise when revisiting similar concepts. It's no longer a matter of making various speculations; rather, a solid foundational model is now present in the mind. This feeling is incredibly gratifying, satisfying, truly remarkable and wonderful.

* [kOS-Notes](https://github.com/linuslau/kOS-Notes.git): A set of notes organized in book form, aimed at explaining the crucial steps and essential techniques involved in constructing an operating system kernel from the ground up.

* [kOS-Setup](https://github.com/linuslau/kOS-Setup.git): Comprehensive information on all necessary setups, configurations and environments for code building and operating system execution, encompassing tools, scripts, command usage, virtual machines, disk images, USB FDD, PCs, BIOS, and more.

* [kOS-Src](https://github.com/linuslau/kOS-Src.git): Reference code for a tiny, compact kernel with an integrated shell, featuring support for file systems, inter-process communication, process scheduling, memory management, and input-output system, etc. 

## Introduction <font size=2> [[Table of contents](#table-of-contents)]</font>

This project documents the creation of a basic operating system (kernel) from the ground up. The initial version of the command-line-based kernel has been operational for some time, functioning seamlessly on both virtual machines and real PCs. The purpose of this repository is to record and review the essential knowledge acquired over the past few months, serving as a foundational resource for myself and anyone interested in developing their own OS.

My intention here is to offer a straightforward and accessible approach for those who may feel hesitant to begin. I aim to guide individuals, step by step, without imposing any barriers, building confidence from start to finish. Numerous repositories on GitHub solely showcase the finalized code accompanied by a concise project explanation. For newcomers, preparing everything can be a challenge. I believe this can be a significant obstacle for many people in the initial stages. If you fall into that category, I believe this repository is well-suited for you.

## Background <font size=2> [[Table of contents](#table-of-contents)]</font>

During my academic journey, I delved into the learning of advanced OS features such as pagination, semaphores, and memory management. Also, post-graduation and throughout my professional experience in applications, framkework, services, drivers, BIOS, and hardware, I continued to expand my expertise in various aspects of computer systems. Despite my familiarity with domain-specific knowledge, the OS/System itsself remained a somewhat opaque aspect, leaving me discontent. This lack of understanding motivated me to delve into OS development, seeking a deeper understanding of the essence and nature of all facets in the programming world.

## Motivation <font size=2> [[Table of contents](#table-of-contents)]</font>

The curiosity to grasp the functioning of an OS kernel, comprehend system interfaces, and unveil the inner workings behind the OS has always intrigued me. The OS has perpetually been a black box, and I aimed to demystify it. While the initial concept of crafting an OS from scratch seemed daunting. however, the availability of information on the internet, coupled with inspiration from various documents, convinced me to create concise step-by-step READMEs and code samples accessible to anyone keen on the endeavor.

## Key Features <font size=2> [[Table of contents](#table-of-contents)]</font>

One notable aspect of this repository lies in the implementation on real PCs. While many OS-from-scratch projects are built and tested on virtual machines, running the OS on actual hardware introduces additional challenges. Successfully executing this code on a real PC brought a sense of accomplishment and underscores the practicality of the project.

## Acknowledgments <font size=2> [[Table of contents](#table-of-contents)]</font>

This repository is constructed based on existing code and literature that I thoroughly studied, gaining valuable insights. As I document my progress, the intention is to not only capture the current state of this basic OS but also to lay the foundation for future enhancements and development in line with my evolving understanding of OS architecture.

## Future Development Roadmap <font size=2> [[Table of contents](#table-of-contents)]</font>

As time progresses and new technologies emerge, the goal is to consistently enhance this OS, gradually incorporating new designs based on the latest architectures, such as transitioning from using `int 0x80` to leveraging `sysenter`. Additionally, the intention is to explore the possibility of extending the OS to other CPU architectures, such as ARM or MIPS. Moreover, envisioning the integration of a graphical user interface (GUI) similar to Explorer is part of the roadmap, aiming to provide a more refined user experience and transform the OS into a more comprehensive and user-friendly system.

# I hope you find it enjoyable.