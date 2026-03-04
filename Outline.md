Pragma is a project encompassing a hardware optimization tool, a programming language, and an operating system.
The below is about the hardware optimization tool.  For information on the Pragma project, go here: 
--------------------------------------------------------------------------------------------------------------------

Metal is a tool to help system administrators and engineers optimize Intel and AMD platforms at the hardware level.
Admins use the coreboot build tool to make the firmware image, save the legacy UEFI image and flash the new image,
then use Metal to autonomously load system tools like memtest and others, poll for metrics over a specified period, 
and repeat this for several days or weeks depending on how many and how much they wish to toggle those parameters.  
When done, it performs Bayesian optimization using botorch to tune the parameters.

--------------------------------------------------------------------------------------------------------------------
GOALS:
- Organize documentation of hardware settings
- Build tool to collect data and then optimize hardware settings for a given target workload

--------------------------------------------------------------------------------------------------------------------
FROM WIKIPEDIA:

[coreboot]
coreboot is an open‑source project that provides lightweight firmware to initialize  hardware and then load an 
operating system. It is designed to replace proprietary firmware (traditional BIOS or UEFI implementations) by 
performing the minimal tasks required to start a modern 32-bit or 64-bit operating system.

[OCP]
Founded in 2011 by Facebook, Intel, Rackspace, and Goldman Sachs, the Open Compute Project (OCP) facilitates the 
sharing of data center product designs and industry best practices to redesign hardware technology for scalable 
computing, focusing on efficiency, openness, and sustainability. With over 400 member companies worldwide, 
OCP develops open-source hardware designs for cost-effective, energy-efficient infrastructure solutions, including 
servers and liquid-cooling technologies. 

--------------------------------------------------------------------------------------------------------------------
