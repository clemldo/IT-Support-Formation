# [The Modern Computer] - [2025-07-30]

🎯 In IT, **hardware** is an essential topic to understand.
📚 The objective of this course is to describe all the physical parts of a computer and how they work together.

---

- [\[The Modern Computer\] - \[2025-07-30\]](#the-modern-computer---2025-07-30)
    - [Introduction to Hardware](#introduction-to-hardware)
    - [Programs, CPU, and Memory](#programs-cpu-and-memory)
    - [Notions](#notions)

---

### Introduction to Hardware

🖥️ A typical **desktop** setup includes:
- A monitor
- A keyboard
- A mouse
- The desktop tower

🖨️ We can also include:
- Printer
- Speakers
- Webcam

🔌 At the back of the computer, you will find:
- Display ports (HDMI, etc.)
- Audio ports
- USB ports
- Network connection port

⚙️ Components inside the computer:
- CPU (Central Processing Unit)
- RAM (Random Access Memory)
- Hard drive
- Motherboard

---

### Programs, CPU, and Memory

🧠 A CPU constantly receives instructions and executes them.
⚡ It calculates very fast. *For example, an Intel Core i7 can perform 177,730 **MIPS** (Millions of Instructions Per Second) at a **clock speed** of 3.33 **GHz**.*
💾 All instructions are written in binary.

🔗 This information travels around the computer using the **external data bus (EDB)**, which is made up of wires that carry "on-off" (binary voltage) signals.
📏 It comes in different sizes (8-bit, 16-bit, 32-bit, even 64-bit).

📦 Inside the CPU are components known as **registers**, which allow it to store the data it is working with.
➕ *For example, to add two numbers, a CPU needs to store each number, the result, and the operator in different registers.*

🗃️ Our programs are copied into RAM for the CPU to read. RAM represents a large amount (sometimes billions) of data, and the CPU needs to read RAM data as quickly as possible.
🛣️ Therefore, we use the **memory controller chip (MCC)** instead of the EDB.
🗺️ Also, the CPU and MCC use what is called the **address bus** to store the location of the data.

![How request and data move around components](data-request-circulation.png)

⚡ For processing, the CPU also uses **cache memory**, which is smaller than RAM but stores data that is used often.
🔢 There are 3 cache levels in a CPU: L1 (smallest and fastest), L2, and L3.

⏰ The CPU has an internal clock that keeps operations in sync. It connects to a **clock wire**.

---

### Notions

🧠 **CPU (Central Processing Unit):** The brain of the computer; it does all the calculations and data processing.

💾 **RAM (Random Access Memory):** The computer's short-term memory.

🗄️ **Hard drive:** Stores all of our data, including files, pictures, applications, etc.

🧩 **Motherboard:** The body or circulatory system of the computer that connects all the components together.

📜 **Programs:** Instructions that tell the computer what to do.

🔗 **External data bus (EDB):** A row of wires that interconnects the parts of the computer.

🛣️ **Memory controller chip (MCC):** The bridge between the CPU and RAM.

⚡ **Cache memory:** A small amount of memory that stores data we use often.

⏱️ **Clock speed:** The maximum number of clock cycles the CPU can handle in a certain time period. Measured in hertz (Hz); for example, 3.40 gigahertz = 3.4 billion cycles per second.

