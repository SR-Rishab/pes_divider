# 32-bit unsigned divider
## Introduction
A 32-bit unsigned divider is a computational unit or algorithm designed to perform division operations on 32-bit binary numbers without considering their signs. In computer architecture and digital systems, division is a fundamental arithmetic operation that involves finding out how many times one number (the divisor) can be subtracted from another number (the dividend) while ensuring that the result is a whole number or an integer. The "32-bit" in the term refers to the size of the numbers being operated on, specifically 32-bit binary numbers, which consist of 32 binary digits (bits).

Key charecteristics include

1. **Operand**-It operates on 32-bit unsigned binary numbers, which means that both the dividend and the divisor are non-negative integers represented in binary form. The result of the division operation will also be a non-negative integer.
2. **Unsigned division**-It performs division without considering the sign of the numbers. In other words, it treats both the dividend and divisor as positive values.
3. **Performance**-Division operations can be relatively slow compared to addition and multiplication. Therefore, hardware dividers often employ optimization techniques to improve speed and efficiency.

## Modules used 

1. **D Flip-flop**
2. **1-bit register**
3. **5-bit register**
4. **32-bit register**

## Synthesis
<details>

  ![Screenshot from 2023-10-24 12-23-48](https://github.com/SR-Rishab/pes_divider/assets/107171044/17ccb39b-bfe0-4ebb-984d-21d423f196f7)

</details>

## Simulation and GLS
<details>
  
  **Simulation**

  ![Screenshot from 2023-10-24 12-40-39](https://github.com/SR-Rishab/pes_divider/assets/107171044/a202844f-dca5-43c0-ae03-c3d42ad90a94)

  ![Screenshot from 2023-10-24 12-40-12](https://github.com/SR-Rishab/pes_divider/assets/107171044/0221f002-56a5-4f44-b571-eefd5677d931)

  **GLS**

  ![Screenshot from 2023-10-24 12-43-20](https://github.com/SR-Rishab/pes_divider/assets/107171044/4c79184f-4e66-4c50-8161-cdedf8fc1229)

</details>
