## Hi there 👋


Hi I'm Tilak, a software engineer. I enjoy learning the whole spectrum of topics relating to how computers and programs work, which is why you will find that I've worked as "low-level" as building my own CPU from simple logic gates and as "high-level" as building out web applications.

🔭🌱 I’m currently working on learning writing parts of my own OS 💻                                   <br/>
👯👯 I'm open to collaborate on cool C++ projects dealing with high performance/time critical systems  <br/>
⚡🥳 Fun fact: I'm also super into running and will occasionally leetcode in my head as I run (joking) <br/>


Find some of my side projects that I've worked on below!

### C++ Multithreaded Chat Server
This one is not public, but I'm working on making it public. It is a client server model chat app which allows you to chat with others. 
How novel. The cool part about this was learning how the BSD style socket API works and building my own CHAT messaging protocol and presentation layers on
top of the networking layer!

### [Console](https://github.com/tilakG7/console)
Ah Console. A cool little sidequest I did as part of the multithreaded chat server. I was frusterated to learn that there wasn't
already a simple library which allowed for 2 threads to write to console "simultaneously" without jumbling up the output.
I'll let you read the README for more info!

### [Drivers](https://github.com/tilakG7/stm32l4_communication_drivers)
Using an ARM based MCU, I wrote low level drivers for most critical embedded communication protocols: I2C, SPI, UART. Also wrote GPIO and ADC drivers, cause why not!

### [Round Robin Scheduler on a STM32 MCU](https://github.com/tilakG7/stm32_round_robin_scheduler/tree/main)
Here, I implemented a Round Robin schduler for an RTOS using an ARM-based microcontroller. I wrote this code in ARM assembly and C. 
By setting up a periodic interrupt from SysTick timer, different tasks or threads are given control of the CPU. 
The PendSV interrupt handler is what performs the context switch by saving critical registers in the TCB and setting up the next task to run.




<!--
**tilakG7/tilakg7** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
