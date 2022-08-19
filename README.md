

<!--
**tobermory/tobermory** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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

## About Tobermory

I am a software engineer from [Brighton](https://en.wikipedia.org/wiki/Brighton). I studied at [Southampton](https://www.southampton.ac.uk). I now live and work in [Seattle](https://www.seattletimes.com/). For my day job, I design, test and deploy code for what you might call underwater drones. Oh, and I support the [Albion](https://www.brightonandhovealbion.com/).

## Systems I Build

Oceanographic instruments, such as gliders and floats (we don't actually call them drones), have to
- move up and down in the world's oceans
- collect data from various sensors
- at the surface, beam data home using Iridium sat comms
- download further commands for continued operation
- do all the above for years on a single battery pack

## Programming Skills I Have

- Embedded Systems Programming, aka Bare-Metal
- Real-time Operating Systems
- Iridium Sat Comms (SBD and Dial-up)
- Underwater Acoustic Communications
- Cryptography (AES, RSA, Stream ciphers, One-time pads)
- Data compression 
- Data visualization (JFreeChart)
- Simulations/Models
- Geospatial (Maps, Projections)
- Network Programming (sockets)

## Programming Idioms I Have Invented Or Applied

### Executive
A time-ordered event queue, enabling time to be used as a file descriptor. Realizes a single-threaded concurrent programming model where a simple main loop can listen to I/O from many devices simultaneously while also servicing timed (esp I/O timeout) actions. Multi-threaded programming, just say no.

### State Machines
An API for structured conversations with (mostly serial/rs232) devices. Builds upon the Executive, adding regular expressions, resulting in a clean, powerful and verifiable method for device interfacing. We all draw state machines on the whiteboard. This API translates those diagrams directly into code.

### Fragmentation/Assembly
Applied the fragmentation/assembly technique in the IP protocol (OSI model layer 3) to both underwater data transfer using acoustic modems and to Iridium Short-Burst Data (SBD) data transfer. In both domains, the data to be sent (layers down to 4) is larger than can be handled by the data/physical layer (layer 2). 

### Cron
Used the crontab event scheduling syntax as the method by which pilots control data acquisition on remote, rarely-connected, systems. 

## Protocols I Have Used

- TCP/IP
- HTTP
- IMAP
- I2C
- RS232/485

## Technologies I Prefer
- Environment: Unix
- Languages: C, Java, bash
- Tools: regex
- Build: make, maven
- Versioning: git, [semver](https://semver.org/)

## Things I Have Also Dabbled With
- C++
- ARM Cortex M Assembler
- Reverse Engineering (HexRays, IDA)
- Parsers and Code Generation (Antlr, lex+yacc)
- cron

## On GitHub
I have managed to open source various bits and pieces over the years
- [Real-time Operating Systems - Building the RTX RTOS using make/gcc](https://github.com/tobermory/RTX-make-gcc)
- [Cryptography - A filesystem based on one-time pads](https://github.com/UW-APL-EIS/vernamfs) 
- [Networking - Observing TCP data flow](https://github.com/UW-APL-EIS/tcptee)
- [Embedded Systems - Capturing fault dumps on ARM Cortex M](https://github.com/tobermory/faultHandling-cortex-m)

## Elsewhere Online
I follow, and have contributed to, various products, blogs and forums.  These include

- [Embedded CPUs - Silicon Labs](https://silabs.com/community/mcu/32-bit/forum)
- [Embedded Systems - CMSIS](https://github.com/ARM-software/CMSIS_5/issues)
- [Real-time Operating Systems - Keil Forum](https://www.keil.com/forum/)
- [Embedded Systems - Memfault Blog](https://interrupt.memfault.com/blog/)
- [Software Engineering - Stack Overflow](https://stackoverflow.com/)

