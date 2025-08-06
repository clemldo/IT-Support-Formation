# [Digital Logic] - [2025-07-25]

**🧠 Objectives: Understand what a computer calculates and how.**

- [\[Digital Logic\] - \[2025-07-25\]](#digital-logic---2025-07-25)
    - [1. Computer Language](#1-computer-language)
    - [2. Character Encoding](#2-character-encoding)
    - [3. Binary System](#3-binary-system)
    - [4. Convert Between Binary and Decimal](#4-convert-between-binary-and-decimal)
    - [External Resources](#external-resources)

### 1. Computer Language

Computers use **binary** to perform calculations, with only two values: 0 and 1. In computing, we group binary digits into sets of 8, called **bits**.
Technically, a bit is a binary digit.

**e.g.**: The "On-Off" state of a switch → 0️⃣ or 1️⃣ → a bit

A group of 8 bits is referred to as a **byte**.
Each byte can store one character, and we can have **256 possible values** thanks to the **base-2 system** (2⁸).

**e.g.**: 0️⃣1️⃣1️⃣0️⃣0️⃣0️⃣1️⃣1️⃣ → a byte

---

### 2. Character Encoding

Character encoding assigns binary values to characters so that humans can read them.

Bytes can be translated into characters using, for example, the [ASCII - Binary Character Table](https://www.ascii-code.com/). It could be a letter, a digit, or even a control character.

There are more character encoding tables. [UTF-8](https://www.charset.org/utf-8) allows emojis 😄 and is considered the **Unicode** standard.

We can also represent colors with bytes, using the [RGB model](https://www.rapidtables.com/web/color/RGB_Color.html) or [Hexadecimal color codes](https://www.color-hex.com/).

**e.g.**: 1️⃣1️⃣1️⃣1️⃣0️⃣0️⃣0️⃣0️⃣ 1️⃣0️⃣0️⃣1️⃣1️⃣1️⃣1️⃣1️⃣ 1️⃣0️⃣0️⃣1️⃣1️⃣0️⃣0️⃣0️⃣ 1️⃣0️⃣0️⃣0️⃣1️⃣0️⃣1️⃣0️⃣ → 😄 emoji in UTF-8.

---

### 3. Binary System

You might wonder how computers get these ones and zeros.

Binary is an "on-off" state. Today, computers use electricity via transistors to allow electrical signals to pass through.
If there is an electric voltage, we denote it as one; if there isn't, we denote it as zero.

Modern computing is more complex than just the "on-off" state of a light, so it uses **logic gates**.

**Logic gates** allow transistors to perform more complex tasks, like deciding where to send electrical signals depending on logical conditions.

---

### 4. Convert Between Binary and Decimal

Use a table to convert between decimal and binary:

|           | 1st bit | 2nd bit | 3rd bit | 4th bit | 5th bit | 6th bit | 7th bit | 8th bit |
|-----------|---------|---------|---------|---------|---------|---------|---------|---------|
| Power of  | 128     | 64      | 32      | 16      | 8       | 4       | 2       | 1       |
| On or Off | 1       | 0       | 1       | 0       | 1       | 0       | 1       | 1       |

To convert binary into decimal:

<pre><code>128 + 32 + 8 + 2 + 1 = 171</code></pre>

To convert decimal into binary:

<pre><code>
171 - 128 ? yes -> 1
remain 43
43 - 64 ? no -> 0
43 - 32 ? yes -> 1
remain 11
11 - 16 ? no -> 0
11 - 8 ? yes -> 1
remain 3
3 - 4 ? no -> 0
3 - 2 ? yes -> 1
remain 1
1 - 1 ? yes -> 1
Result: 10101011
</code></pre>

---

### External Resources

- [How Transistors Work (YouTube)](https://www.youtube.com/watch?v=YtM_MnM0qT4)
- [Understanding Logic Gates (YouTube)](https://www.youtube.com/watch?v=INEtYZqtjTo)
- [How to Count in Binary (YouTube)](https://www.youtube.com/watch?v=r1b8XAFuwmQ)
