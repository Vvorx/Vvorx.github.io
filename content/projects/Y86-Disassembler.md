---
title: "Y86 Disassembler"
date: 2024-10-09T13:24:40+01:00
draft: false
---

## THIS IS A PROJECT FROM 2023 (First study year)

<https://github.com/Vvorx/Y86-Disassembler>

### Project Overview

This project marks the first "big" coding assignment in our course, aimed at developing a disassembler for the y86 Instruction Set Architecture (ISA). Understanding machine language and processor design is key, as the y86 ISA serves as the interface between high-level programming languages and hardware. The project is structured into three tasks that progressively build the program.

*Learning Objectives:*
- Data Representation in Computers: Gain insights into how computers represent and execute instructions
- Building a Simple Computer: Simulate a basic computer system with few instruction sets
- Improve Problem-Solving: Strengthen problem-solving skills by working bit by bit throught the tasks

*Tasks Breakdown:*
- Task 1: Decoding y86 Opcodes (20 pts)
Decode the opcodes from a list of given instructions, translating them into corresponding assembly mnemonics (e.g., 0x00 → "halt").

- Task 2: Decoding y86 Instruction Operands (40 pts)
Building on Task 1, decode the operands associated with each instruction. Instructions like "nop," "halt," and "ret" do not require operands.

- Task 3: Disassembling y86 Binary Machine Code (30 pts)
A more challenging task that involves disassembling programs presented in y86 bytecode (machine code) and converting them into y86 assembly. Using a program counter (PC), the bytecode is disassembled into assembly code. Test programs are provided to validate results, and the data region does not need to be decoded.
