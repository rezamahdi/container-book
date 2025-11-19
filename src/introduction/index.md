# Introduction to Containers
Container is an approach in isolation of execution environment, for the applications that are going to be executed in
a shared manner. During the history, there were many tries to implement a shared environment for a _shared system_.

The early approach, was the _shared hosting_ where a system with multiuser support, like Unix, is shared between many
users simultanouslly, with the means of operating system itself. But beside the outside risks that thread the system,
internal risks caused by other users may thread users in a shared host. to eliminate this risks, almost every provider
limits the permissions of users, that in turn limits the ablity and freeedom of applications. Among all of this
limitations, preventing the use of root account, (i.e. privileged user), restricts many aspects of tasks that may be
required for a certain application.

An other approach is _virualization_. In this approach, a complete system, including the cpu is simulated by software
to provide an imagenary system, that is dedicated to the user.
