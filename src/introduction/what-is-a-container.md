# What is a Container
A container is an isolated environemnt for execution of programs, that simulate a complete system that shares the
hardware and kernel. If you may be familiar with _Microkernel_[^microkernel] architecture, which separate the comonents
of OS to standalone programs, A container is an evironment that is formed by spawning a separate instances of OS
components, like Network stack, Mount points, PID set and so on. Beside this, kernel provides a means to limit the
resource usage of this environment.

[^microkernel]: [Microkernel on Wikipedia](https://en.wikipedia.org/wiki/Microkernel)
