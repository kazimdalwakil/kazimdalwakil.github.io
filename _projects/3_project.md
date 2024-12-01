---
layout: page
title: Design and Implementation of a 4-Bit ALU with Bit-Wise Operations Using Verilog
projectCategory: VLSI Design course project
authors: Kazi Md. Al-Wakil, Galib Hasan Mim, Sababa Rahman Meenm, Mashiat Hasana Rodoshi
description: A 4-bit ALU was designed in Verilog to perform four bit-wise operations (X-NOR, SUB, NAND, ADD) on two 4-bit inputs, A and B, based on a 3-bit opcode. The ALU produces a 4-bit output, C, and three flags- carry, zero, and sign, indicating the result of the operation. The project was implemented using Quartus.
year: 2022
img: assets/img/CSE460.gif
redirect: 
importance: 3
category: Academic
github: https://github.com/kazimdalwakil/CSE460-Project
show: true
---

In this project I had to build a 4-Bit Alu that can perform 4 operations(X-NOR, SUB, NAND, ADD). The constraint was to code the project in such a way that operations are done bit-wise. 

The ALU takes two four-bit inputs: A, B and Three-bit operation Code (opcode). Based on the opcode, it performs four different operations on A and B and produces a four-bit output, C. Depending on the result of a particular operation, the ALU also produces three flags: carry, zero and sign flag.

The whole project was done in the Quartus and used Verilog programming language.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cse460_3.jpg" title="Network Topology" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Block Diagram of the ALU
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cse460_4.jpg" title="Network Topology" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The details of the flags followed by an operation.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cse460_5.jpg" title="Network Topology" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Op Codes Description
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cse460_1.jpg" title="Network Topology" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    State Diagram
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cse460_2.jpg" title="Network Topology" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Timing diagram of the output (w0,w1,w2 represents 3-bit OP Code)
</div>

You can find more about the project <a href="https://github.com/kazimdalwakil/CSE460-Project">here.</a>
