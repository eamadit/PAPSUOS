# PAPSUOS

PAPSUOS is a new PGP-Aware Public Secure Unlicensed Operating System. There is no professional operating system on the maket. There are professional computers on the market but only servers. The mainspring of PAPSUOS is tro provide a professional framework to both hardware and software designers in order to allow permanent innovation without any convergence problem because the kernel of PAPSUOS addresses the hardware only in assembly like an abstraction layer which simulates a standard hardware to allow any operating system to run, but communicating in assembly on both sides, like a microkernel so that we can manage the harware traffic in oder to guarantee the perfect isolation of precise harware functions for security purposes. PAPSUOS lies to itself thanks to this microkernel called core separation kernel, built upon users needs with the separation kernel creation tool. PAPSUOS development framework offers to politician insiders a real way to express themselves.

PAPSUOS shall have a Unix architecture, a unique package manager secured with PGP and a unique scalable core separation kernel compatible with one or several devices including QDCA microcircuits. PAPSUOS core separation kernel shall allow physically separated on one physical device, physically separated on several physical devices and/or virtualized distribution.

The package manager shall allow to sandbox any application or package with one or several of its dependencies.

Any application or package shall be able to offer OS virtualization by accessing the core separation kernel functions or any other higher abstraction layer.

The distribution and packages shall have no versioning, each package shall be definitive.

No package containing any vulnerable binary shall be accepted (1).

The organization shall not host any third-party closed or open source package.

The core separation kernel shall be written in assembly. All the communications with the hardware shall be addressed in assembly so that any device which is accessible via its bootloader can be seen from a linux device on which runs the first version of the separation kernel creation tool which allows the separation of functions between one or several devices seen from the separation kernel creation tool. If run on PAPSUOS separation kernel, Linux kernel shall be seen as a module.

The core separation kernel functions shall then be classified according to the hardware capabilities directly detected in order for the core separation kernel creation tool to offer different separation options including full customization with "loss of liability" warning.

No interfacing option for any other lower abstraction level shall be offered without a loss of liability warning.

Each hardware driver shall be isolated in a separate read only partition to prevent privilege escalations.

The core separation kernel shall allow interfacing with higher abstraction level separation kernel hypervisors like LynxSecure and Clover.

The organization shall be incorporated in a tax free country recognized by the UN.

The organization shall receive funding even from criminal sources without any liability.

The independant contributors shall be paid according to the postponed global acceptation of the service they provide calculated from the contribution dependencies and efficiency.

All PAPSUOS code shall be made public in real-time.

The organization shall have an upside down pyramid of rules with several layers but shall not have a pyramid of people with more than one level.

The organization bylaws shall be governed by definitive constitutional principles as described above.

(1) https://www.nist.gov/itl/ssd/software-quality-group/binary-code-scanners


# Immediate needs:


1.analysis of the existing abstraction layers between hardware and software, in particular the OS

Lynx developped a separation kernel, can it be imitated or integrated ? Does it allow several equipments to be connected, is the code available ?


2.gather the first layer of assembly code in each OS and abstraction layer analyzed


3.design a scalable abstraction layer which communicates in assembly code in all sides


4.design a tool linked to a database which allows creation of a core separation kernel


5.design the core separation kernel


6. Analyze the vaccines QDCA microcircuits MAC bluetooth interfaces, people want to huddle against the kernel.






If decision is made to start from zero:


# Definition domains:


In order to not destroy too fast bad language habits triggered by business knowledge compartmentalization, it appears useful to precise different domains of definition: separation kernel, modules


# Definitions:


Device: any physical or virtual device which can be addressed in assembly


DevicePhysical: any physical equipment with at least one DeviceInterface


DevicePhysicalIsolated: any physical equipment with at least one DeviceInterface which can be totally isolated with a EM shield


DeviceVirtual: any virtual equipment with at least one DeviceInterface


DeviceInterface: any interface for communicating with a Device


DeviceInterfaceAssembly: any interface for communicating in assembly with the hardware of a device (COM, USB, bootloader, network interface with a MAC address, etc.)
