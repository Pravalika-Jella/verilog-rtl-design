# Half Adder

## Overview

A half adder is a combinational circuit that adds two 1-bit binary inputs and produces a sum and carry output.

## Inputs

* `a` — 1-bit input
* `b` — 1-bit input

## Outputs

* `sum` — XOR of `a` and `b`
* `carry` — AND of `a` and `b`

## Logic

```text
sum   = a XOR b
carry = a AND b
```

## Verification

The design is verified using a Verilog testbench that applies all four possible input combinations.

## Tools

* Verilog HDL
* ModelSim / QuestaSim
