You are free to bring your brick until rules are designed, I do not understand if I need to activate contributions somewhere or not


# Immediate needs:


1.analysis of the existing abstraction layers between hardware and software, in particular the OS

Lynx developped a separation kernel, can it be imitated or integrated ? Does it allow several equipments to be connected, is the code available ?


2.gather the first layer of assembly code in each OS and abstraction layer analyzed


3.design a scalable abstraction layer which communicates in assembly code in all sides


All the communications with the hardware shall be addressed in assembly so that any device which is accessible via its bootloader can be seen from a linux device on which runs the first version of the separation kernel creation tool which allows the separation of functions between one or several devices seen from the separation kernel creation tool.


4.design a tool linked to a database which allows creation of a core separation kernel


5.design the core separation kernel


Each hardware driver shall be isolated in a separate read only partition to prevent privilege escalations



If decision is made to start from zero:


# Definition domains:


In order to not destroy too fast bad language habits triggered by business knowledge compartmentalization, it appears useful to precise different domains of definition: separation kernel, modules


# Definitions:


Device: any physical or virtual equipment


DevicePhysical: any physical equipment with a DeviceInterface


DeviceVirtual: any virtual equipment with a DeviceInterface


DeviceInterface: any interface for communicating with a Device:


DeviceInterfaceAssembly: any interface for communicating in assembly with the hardware of a device (COM, USB, bootloader, etc.)

