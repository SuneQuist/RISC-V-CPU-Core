# RISC-V-CPU-Core
A basic logic-based CPU Core for the RISC-V ISA

This is a straightforward CPU core with basic functions.<br/> 
I did not bother to implement func7 or 30 syscalls.<br/>
Why, you might ask? Because it is simply more of the same work.<br/> 
The basic implementation atm, is equal but less work than a more<br/>
well-rounded CPU core.<br/>

The M4 Microchip handles the instructions passed, and the passed test<br/>
can be viewed in the logs.<br/>
To view the logs and the CPU core, go to [Makerchip and launch the IDE](https://makerchip.com/)<br/>
From there, you should be able to open the riscv_cpu_core.v file,<br/>
from this repository.<br/>

This was learnt over a day from the course [Building a RISC-V CPU Core](https://www.edx.org/learn/design/the-linux-foundation-building-a-risc-v-cpu-core?index=product&queryId=8751e218d79401e0f7e4c7155c877778&position=1)<br/>
by Steve Hoover, founder at Redwood EDA.<br/>

Here is the Logic Diagram of the CPU core.
![Logic Diagam](https://github.com/SuneQuist/RISC-V-CPU-Core/blob/main/cpu_core_logic.png)

Here is the Final Diagram in Makerchip.
![Makerchip Diagram](https://github.com/SuneQuist/RISC-V-CPU-Core/blob/main/cpu_core_diagram.png)

Have a wonderful day.
