# Introduction to Hyper-V on Windows 10
- Hyper-V specifically provides hardware virtualization. That means each virtual machine runs on virtual hardware. Hyper-V lets you create virtual hard drives, virtual switches, and a number of other virtual devices all of which can be added to virtual machines.
# Reasons to use virtualization
Virtualization allows you to:

- Run software that requires an older versions of Windows or non-Windows operating systems.

- Experiment with other operating systems. Hyper-V makes it very easy to create and remove different operating systems.

- Test software on multiple operating systems using multiple virtual machines. With Hyper-V, you can run them all on a single desktop or laptop computer. These virtual machines can be exported and then imported into any other Hyper-V system, including Azure.

# System requirements
- Hyper-V is available on 64-bit versions of Windows 10 Pro, Enterprise, and Education. It is not available on the Home edition.
# Differences between Hyper-V on Windows and Hyper-V on Windows Server
Hyper-V features only available on Windows Server:

- Live migration of virtual machines from one host to another
- Hyper-V Replica
- Virtual Fiber Channel
- SR-IOV networking
- Shared .VHDX

Hyper-V features only available on Windows 10:
- Quick Create and the VM Gallery
- Default network (NAT switch)
