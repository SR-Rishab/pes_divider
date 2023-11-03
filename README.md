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
  
![Screenshot from 2023-09-15 10-38-02](https://github.com/SR-Rishab/pes_divider/assets/107171044/36b29301-41a2-4594-a051-8e1cda28a8b4)
![Screenshot from 2023-09-15 10-37-46](https://github.com/SR-Rishab/pes_divider/assets/107171044/277b6601-66fc-467d-8caa-3222732a377f)
![Screenshot from 2023-09-15 10-37-35](https://github.com/SR-Rishab/pes_divider/assets/107171044/e71d2e40-c1bd-4234-8fc0-e26ab3345b0d)
![Screenshot from 2023-09-15 10-37-06](https://github.com/SR-Rishab/pes_divider/assets/107171044/92a35b4f-7947-48fc-9ded-a38e438240f1)
![Screenshot from 2023-09-15 10-36-52](https://github.com/SR-Rishab/pes_divider/assets/107171044/687e90d6-3160-49a2-8130-9f12018bcdab)

</details>

## Simulation and GLS
<details>
  
  **Pre-synthesis simulation**

  ![Screenshot from 2023-10-24 12-40-39](https://github.com/SR-Rishab/pes_divider/assets/107171044/a202844f-dca5-43c0-ae03-c3d42ad90a94)

  ![Screenshot from 2023-10-24 12-40-12](https://github.com/SR-Rishab/pes_divider/assets/107171044/0221f002-56a5-4f44-b571-eefd5677d931)

  **Post synthesis simulation**

  ![Screenshot from 2023-10-24 12-43-20](https://github.com/SR-Rishab/pes_divider/assets/107171044/4c79184f-4e66-4c50-8161-cdedf8fc1229)

Pre and Post simulation waveforms match 
</details>

Physical design

<details>
  <summary>Automated design flow</summary>
  
  ![automated_1](https://github.com/SR-Rishab/pes_divider/assets/107171044/37a0d9a6-5c60-4050-b9eb-8fe7ef997151)
![automated_2](https://github.com/SR-Rishab/pes_divider/assets/107171044/9097972d-780e-4a7e-9189-884210adfdd2)
![automated_3](https://github.com/SR-Rishab/pes_divider/assets/107171044/4243e7ba-aab8-4bfc-b8f7-942620beccc5)
![automated_4](https://github.com/SR-Rishab/pes_divider/assets/107171044/3d7c9454-8579-4e9a-80a1-bf814d868d6e)
![automated_5](https://github.com/SR-Rishab/pes_divider/assets/107171044/dc82f502-28d0-42d6-a782-4f9db63f34b5)
![automated_6](https://github.com/SR-Rishab/pes_divider/assets/107171044/062c42fb-5c3e-4571-bd36-09d25396b4eb)

</details>
<destail>
  <summary>Interactive design flow</summary>
<details>
  <summary>Adding design</summary>
  
  ![Design_init](https://github.com/SR-Rishab/pes_divider/assets/107171044/83506332-61e7-4ca8-aab6-a67d428cc2bb)

</details>
<details>
  <summary>Preping design</summary>
  
  ![design_prep](https://github.com/SR-Rishab/pes_divider/assets/107171044/8993f11e-702b-4e13-bfe2-aa9fc240e141)

</details>
<details>
  <summary>Synthesis</summary>
  
  ![run_synthesis](https://github.com/SR-Rishab/pes_divider/assets/107171044/a4b096f3-0cf9-452a-8419-1f4ea890c1de)

</details>
<details>
  <summary>Floorplan</summary>
  
  ![floorplan_2](https://github.com/SR-Rishab/pes_divider/assets/107171044/f6ed4e3b-9cd8-4f20-b2b4-d4d356d7db20)
![floorplan_1](https://github.com/SR-Rishab/pes_divider/assets/107171044/fe36df97-20c1-4f80-aadd-316767aba2e7)
</details>
<details>
  <summary>Placement</summary>
  
  ![run_placement](https://github.com/SR-Rishab/pes_divider/assets/107171044/eab35666-45a3-410d-abb5-8b13e7d55572)
</details>
<details>
  <summary>Clock tree synthesis</summary>
  
  ![run_cts](https://github.com/SR-Rishab/pes_divider/assets/107171044/0290098e-34a2-497a-863e-9b841762e221)

</details>
<details>
  
  ![run_routing](https://github.com/SR-Rishab/pes_divider/assets/107171044/4302ea8c-b059-4eec-b4a7-325a7570167a)
<summary>Routing</summary>
  
</details>
</destail>
