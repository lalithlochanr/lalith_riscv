Refer to the manual for any queries - https://github.com/stevehoover/RISC-V_MYTH_Workshop

## Day 1 - Digital Logic with TL-Verliog and Makerchip   

<details>
  <summary> Combinational Logic in TL-Verilog using Makerchip </summary>

  ### Introduction to Logic Gates

 - Logic gates are fundamental building blocks of digital electronic circuits. They are simple devices or components that perform basic logical operations on binary data, which is composed of ones and zeros.  

    ![Screenshot 2023-10-15 174019](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/245b567c-c7ea-4c13-bb7c-e7af2de2a2c9)

- Combinational Circuit
  - A combinational circuit is a type of digital electronic circuit that produces an output based solely on the current values of its input signals, without any regard for previous inputs or a feedback mechanism.
![Screenshot 2023-10-15 174426](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/c4a30996-f181-45d2-a199-b35590e99f93)

- Adder
  - An adder block in digital circuits is a specific combinational circuit designed to perform the arithmetic operation of addition and give the ouput of sum and carry on summing various input bits.
![Screenshot 2023-10-15 174716](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/b6815708-4b5b-405c-8dfc-d80e9ceb671f)

- Boolean Opertaors
 - Operators are used to perform logical operations on two or more Boolean values.
![Screenshot 2023-10-15 174732](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/63b34e3b-260c-4335-a5f0-11c523e704ba)


### Basic MUX implementation and Introduction to Makerchip
  
- MUX
   - A multiplexer is a digital electronic device or combinational circuit that selects one of several input data lines and forwards it to a single output line.
 ![Screenshot 2023-10-15 175225](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/c2ebd8fb-61dc-4837-b9b8-d7e296a5dcca)

- Chaining ternary operator
  - A ternary operator, also known as the conditional operator, is a concise way to express conditional statements in programming. Using multiple ternary operators making it a chaining ternary operator.
![Screenshot 2023-10-15 175315](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/2e91898c-3800-4c0e-8c08-03971669e36c)

- Makerchip
![Screenshot 2023-10-15 180103](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/2dc0e55d-c565-4c7e-920a-7781beebb0d2)

### Labs for Combinational Logic

- Inverter
  ![Screenshot 2023-10-15 181638](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/565d056f-0a95-48a4-a19c-2013a96e8925)

- Arithmetic Operators on Vectors
  ![Screenshot 2023-10-15 182145](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/2b14d1d4-4c0b-4f13-9556-8db9996f8f13)

- MUX
  ![Screenshot 2023-10-15 183231](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/3ac1bb32-518a-4b65-89ab-c09fb7193421)

- MUX Operator on Vectors
  ![Screenshot 2023-10-15 183445](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/e180a302-b1a4-4db2-8582-0448aeaef57f)

- Combinational Calculator
  ![Screenshot 2023-10-18 074517](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/8a4b112c-6287-4acd-9d70-2c6bee9fecc8)

   
</details>

<details>
  <summary> Sequential Logic </summary>

  ### Introduction to Sequential Logic and Counter Lab

  * Sequential Logic
    - Sequential logic refers to a type of digital logic circuit in which the output not only depends on the current input but also on the previous state of the circuit, using memory elements like flip-flops. It is used for designing circuits that store and process data over time, enabling tasks such as memory storage and sequential decision-making.
   
    - A D flip-flop is a type of digital logic circuit that stores and outputs a single-bit binary value. It samples and holds the value of its data (D) input on the rising or falling edge of a clock signal, depending on its configuration, and presents that value at the output (Q).
   
![Screenshot 2023-10-18 074027](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/2ea534cf-16be-4843-baa4-5106e85b57ba)

![Screenshot 2023-10-18 074200](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/2e558cd4-facf-476c-935f-57bddc63e790)

* Fibonacci Sequence
  ![Screenshot 2023-10-18 074847](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/a2ece76b-4477-44cb-9fab-36e3ce1a6676)

  ![Screenshot 2023-10-18 112047](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/9149d8d7-9a6f-4b98-9bd4-f334440f18a2)


* Counter
  ![Screenshot 2023-10-18 111450](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/ad36133f-3ded-490b-85f4-4f4381b901c3)


### Sequential Calculator Lab

![Screenshot 2023-10-18 112250](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/cb8a6827-4092-45bf-b51d-e4e973f3e48e)

* Our simulator configuration:
- will zero-extend or truncate when widths are mismatched (without warning)
- uses 2-state simulation (no X's)

![Screenshot 2023-10-18 112705](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/f3e409f9-514c-4f4e-80f7-268cdfe13d4d)

</details>


<details>
  <summary> Pipelined Logic</summary>

  ### Pipeline Logic and Re-Timing 
  - Timing abstraction refers to simplifying the representation of digital circuits by focusing on signal delays and ignoring the internal behavior of logic gates, enabling designers to analyze and optimize circuits based on signal propagation times and clocking constraints


![Screenshot 2023-10-18 113823](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/8dc4d793-3224-45b3-95b8-eaf573d78a17)

![Screenshot 2023-10-18 114045](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/fb58bb1d-43dd-4940-8d1d-92ba129a4fdd)

- Using of TL-Verilog compared to System Verilog reduces code by 3.5 times.

 ![Screenshot 2023-10-18 114223](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/2c75f3f6-1c93-438c-87a7-e2ecf58c4bb5)

- whereas Re-Timing in System Verilog is very bug-prone!

### Pipeline Logic Advantages and Demo in Platform

* Pythagoras's Theorom
* without Pipeline
  ![Screenshot 2023-10-18 115524](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/2482a8a8-5f31-4813-a1fd-f98d92c631b1)
* with Pipeline
  ![Screenshot 2023-10-18 115612](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/be87a049-e1f9-48b6-a27c-82a629afd93e)
  ![Screenshot 2023-10-18 115726](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/ba25c2bf-acf7-4af9-bf2d-a58bae45f19c)

- aa_sq 12 transactions ahead in the sense it has gone through 12 stages of flip-flops
  ![Screenshot 2023-10-18 115950](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/7a8f3f2f-5ba3-4e8a-90e5-742766167022)

### Lab on Error Computations Within Computation Pipeline

![Screenshot 2023-10-18 120421](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/edc487f9-39f6-422e-948e-1b1ce136f5c9)

- Everything is in Pipeline in TL-Verilog even though it is not explicitly mentioned

![Screenshot 2023-10-18 122007](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/66af786d-f42a-4e35-91c9-844cebf7ce7e)

![Screenshot 2023-10-18 121814](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/c74786d0-01d0-4052-aed4-a0c6ff9d47eb)

### Lab on 2-Cycle Calculator

![Screenshot 2023-10-18 122345](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/93011181-6caa-4b1f-b1de-bfc985fc3dd7)

![Screenshot 2023-10-18 122719](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/c43c4751-4a7f-4448-a4fe-91daed81bbc4)

![Screenshot 2023-10-18 123238](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/1743108d-8d33-4925-b006-69b44a69b611)

![Screenshot 2023-10-18 123252](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/7dea2789-39c0-4c91-b1c9-19613806e744)

</details>


<details>
  <summary> Validity </summary>
  
### Introduction to Vaalidity and its Advantages 

* Validity provides
  - Easier Debug
  - Cleaner Design
  - Better Error Checking
  - Automated clock gating

* Clock Gating
  
![Screenshot 2023-10-18 123726](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/8d7ef634-1d09-40a1-992e-281be0786129)

### Lab on Validity and Valid when Condition and  To compute Total Distance

![Screenshot 2023-10-18 125321](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/4f61cc64-1012-4c62-a6e0-ca3c80b0daa1)

### Lab on 2-Cycle Calculator with Validity

![Screenshot 2023-10-18 133650](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/c1f2e2ff-deff-4176-b409-4065f39e02a8)

![Screenshot 2023-10-18 130342](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/ebc1b5a1-b495-49a9-ad11-3dcc5fb3627a)

![Screenshot 2023-10-18 140957](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/ad83088a-6c9a-4f05-8544-83727c4d677a)


### Lab on Calculator with Single Value Memory

![Screenshot 2023-10-18 133701](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/77385c19-7680-4b88-b988-c51b550b0129)

![Screenshot 2023-10-18 133108](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/ccf0841e-fb89-414f-8476-776a39b7b191)

![Screenshot 2023-10-18 141049](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/c0868d06-b759-4a14-b15f-13d8d45ea61b)

  
</details>


<details>
  <summary> Wrap-Up </summary>
 
  * Heirarchy
  
  ![Screenshot 2023-10-18 133838](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/d72002e9-f6d3-4f26-95fa-8620f507ca5f)
-Lexical re-entrance refers to a programming or parsing concept where a function or module can be safely reinvoked, even while a prior call is still in progress, without causing conflicts or interference in the program's execution, allowing for efficient multitasking and recursion.

   
</details>


## Day 2 - Basic RISC-V CPU micro-architecture

<details> 
  <summary>Introduction to RISC-V Micro-architecture</summary> 

* A single-cycle RISC-V processor is a simplified version of a RISC-V microprocessor where each instruction is executed within a single clock cycle. While this approach offers simplicity, it often results in slow performance. Nevertheless, it serves as a fundamental building block for understanding processor design. Here are the stages and key components of a single-cycle RISC-V processor:  

1. Instruction Fetch (IF):  

- The instruction fetch stage is the first stage in the processor's pipeline.  
- The program counter (PC) holds the address of the current instruction to fetch.  
- The PC is sent to the instruction memory, and the instruction at that address is fetched and placed into the instruction register (IR).  
- The PC is incremented by 4 (since RISC-V instructions are typically 4 bytes in length) to prepare for the next instruction fetch.    

2. Instruction Decode (ID):    

-In this stage, the instruction in the IR is decoded.  
- The opcode and other fields of the instruction are used to determine the operation to be performed.  
- Register numbers and immediate values are extracted from the instruction.  

3. Execution (EX):  

- The execution stage performs the actual operation specified by the instruction.   
- For R-type instructions (e.g., add, subtract), arithmetic and logical operations are performed using the values from the registers.  
- For I-type instructions (e.g., load, store), address calculations are made.  
- Control signals for the ALU (Arithmetic Logic Unit) are generated based on the instruction type.  

4. Memory Access (MEM):    

- This stage is responsible for reading from or writing to memory (e.g., data cache or RAM) in load and store instructions.  
- For loads, the address calculated in the execution stage is used to read data from memory.  
- For stores, the data to be written is placed in memory at the address calculated earlier.  
- Other instructions typically perform no memory access.  

5. Write-Back (WB):  

- In the final stage, the results of the execution stage are written back to the register file.  
- The destination register (specified in the instruction) is updated with the result.  
- If the instruction is a load, the value read from memory is written to a register.  
- The PC is updated with the next instruction address to prepare for the next cycle.  

* In a single-cycle processor, each instruction goes through all of these stages within a single clock cycle.   

![Screenshot 2023-10-18 155219](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/8adc4ec3-3c64-4abb-9762-3212297a05fb)  

![Screenshot 2023-10-18 155622](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/8b53fa49-4b21-492f-90e1-ea2ece42cf75)

![Screenshot 2023-10-18 160950](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/5949b52a-30b6-440e-8cb2-88ba417c4da9)

</details>

<details>
  <summary> Fetch and Decode </summary>

### Implementation and Lab for PC  

````
  |cpu
      @0
         $reset = *reset;
         $pc[31:0] = >>1$reset ? 32'b0 :
                                 >>1$pc + 32'd4;
````

![Screenshot 2023-10-18 161830](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/97852378-3619-4f8f-b7d1-a35a0778fed8)

![Screenshot 2023-10-18 162202](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/d1032b67-a973-4a03-87d5-15f0d8de61a5)

![Screenshot 2023-10-18 164521](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/bb6bbbbc-e229-40a7-a41a-89dc41dfd384)

### Lab for Instruction Fetch Logic  

````
  |cpu
      @0
         $reset = *reset;
         $pc[31:0] = >>1$reset ? 32'b0 :
                                 >>1$pc + 32'd4;
         $imem_rd_addr[M4_IMEM_INDEX_CNT-1:0] = $pc[M4_IMEM_INDEX_CNT+1:2];
         $imem_rd_en = !$reset;
      /imem[7:0]
         @1
            $instr[31:0] = *instrs\[#imem\];
      ?$imem_rd_en
         @1
            $imem_rd_data[31:0] = /imem[$imem_rd_addr]$instr;
      @1   
         $instr[31:0] = $imem_rd_data[31:0];
|cpu
      m4+imem(@1)    // Args: (read stage)
      m4+rf(@1, @1)  // Args: (read stage, write stage) - if equal, no register bypass is required
````

![Screenshot 2023-10-18 162407](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/12f9a372-0f1b-49c7-a4d3-1e62f42b6de2)

![Screenshot 2023-10-18 163518](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/06227861-911f-4d02-92a7-c52df8cf8ca8)

![Screenshot 2023-10-18 164654](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/817d370e-7625-4790-a9de-ba156c183f96)  

### RV Instruction Types IRSJBU and Decode Logic

![Screenshot 2023-10-18 164746](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/ec3e8e20-50f1-45af-ab36-0c07dde9a762)

![Screenshot 2023-10-18 164758](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/1ef7496e-c324-4a2b-aa7b-1c4fdf4d74ba)

![Screenshot 2023-10-18 164848](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/cbe0504c-b91f-48fa-b114-eb7f982aab1f)

- beq (Branch Equal):  

Opcode: 1100011 (I-type)  
Func3: 000  

- bne (Branch Not Equal):  

Opcode: 1100011 (I-type)  
Func3: 001  

-blt (Branch Less Than):  
Opcode: 1100011 (I-type)  
Func3: 100  

-bge (Branch Greater Than or Equal):  
Opcode: 1100011 (I-type)  
Func3: 101  

-bltu (Branch Less Than, Unsigned):  
Opcode: 1100011 (I-type)  
Func3: 110  

-bgeu (Branch Greater Than or Equal, Unsigned):  
Opcode: 1100011 (I-type)  
Func3: 111  

-add (Addition):  
Opcode: 0110011 (R-type)  
Func3: 000  

-addi (Add Immediate):  
Opcode: 0010011 (I-type)  
Func3: 000  

````
|cpu
      @0
         $reset = *reset;
         $pc[31:0] = >>1$reset ? 32'b0 :
                                 >>1$pc + 32'd4;
         $imem_rd_addr[M4_IMEM_INDEX_CNT-1:0] = $pc[M4_IMEM_INDEX_CNT+1:2];
         $imem_rd_en = !$reset;
      /imem[7:0]
         @1
            $instr[31:0] = *instrs\[#imem\];
      ?$imem_rd_en
         @1
            $imem_rd_data[31:0] = /imem[$imem_rd_addr]$instr;
      @1   
         $instr[31:0] = $imem_rd_data[31:0];
         $is_b_instr = $instr[6:2] ==? 5'b11000;
         $is_r_instr = $instr[6:2] ==? 5'b01011 ||
                          $instr[6:2] ==? 5'b011x0 ||
                          $instr[6:2] ==? 5'b10100;
         $is_j_instr = $instr[6:2] ==? 5'b11011;
         $is_i_instr = $instr[6:2] ==? 5'b0000x ||
                            $instr[6:2] ==? 5'b001x0 ||
                            $instr[6:2] ==? 5'b11001;
         $is_u_instr = $instr[6:2] ==? 5'b0x101;
         $is_s_instr = $instr[6:2] ==? 5'b0100x;
         $rs1[4:0] = $instr[19:15];
         $rs2[4:0] = $instr[24:20];
         $rd[4:0] = $instr[11:7];
         $opcode[6:0] = $instr[6:0];
         $funct7[6:0] = $instr[31:25];
         $funct3[2:0] = $instr[14:12];
         $imm[31:0] = $is_i_instr ? {{21{$instr[31]}}, $instr[30:20]} :
                         $is_s_instr ? {{21{$instr[31]}}, $instr[30:25], $instr[11:7]} :
                         $is_b_instr ? {{20{$instr[31]}}, $instr[7], $instr[30:25], $instr[11:8], 1'b0} :
                         $is_u_instr ? {$instr[31:12], 12'b0} :
                         $is_j_instr ? {{12{$instr[31]}}, $instr[19:12], $instr[20], $instr[30:21], 1'b0} :
                                     32'b0;
|cpu
      m4+imem(@1)    // Args: (read stage)
      m4+rf(@1, @1)  // Args: (read stage, write stage) - if equal, no register bypass is required
````

![Screenshot 2023-10-18 174947](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/755f5f79-e970-42c6-a247-91955df38cbb)

![Screenshot 2023-10-18 175102](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/75357a5c-7fce-4754-9ae0-2c6078c1173c)

* Decode with Validity
````
|cpu
      @0
         $reset = *reset;
         $pc[31:0] = >>1$reset ? 32'b0 :
                                 >>1$pc + 32'd4;
         $imem_rd_addr[M4_IMEM_INDEX_CNT-1:0] = $pc[M4_IMEM_INDEX_CNT+1:2];
         $imem_rd_en = !$reset;
      /imem[7:0]
         @1
            $instr[31:0] = *instrs\[#imem\];
      ?$imem_rd_en
         @1
            $imem_rd_data[31:0] = /imem[$imem_rd_addr]$instr;
      @1   
         $instr[31:0] = $imem_rd_data[31:0];
         $is_b_instr = $instr[6:2] ==? 5'b11000;
         $is_r_instr = $instr[6:2] ==? 5'b01011 ||
                          $instr[6:2] ==? 5'b011x0 ||
                          $instr[6:2] ==? 5'b10100;
         $is_j_instr = $instr[6:2] ==? 5'b11011;
         $is_i_instr = $instr[6:2] ==? 5'b0000x ||
                            $instr[6:2] ==? 5'b001x0 ||
                            $instr[6:2] ==? 5'b11001;
         $is_u_instr = $instr[6:2] ==? 5'b0x101;
         $is_s_instr = $instr[6:2] ==? 5'b0100x;
         $rs1_valid = $is_r_instr || $is_i_instr || $is_s_instr || $is_b_instr;
         $rs2_valid = $is_r_instr || $is_s_instr || $is_b_instr;
         $rd_valid = $is_r_instr || $is_i_instr || $is_u_instr || $is_j_instr;
         $funct3_valid = $is_r_instr || $is_i_instr || $is_s_instr || $is_b_instr;
         $funct7_valid = $is_r_instr;
         $imm[31:0] = $is_i_instr ? {{21{$instr[31]}}, $instr[30:20]} :
                         $is_s_instr ? {{21{$instr[31]}}, $instr[30:25], $instr[11:7]} :
                         $is_b_instr ? {{20{$instr[31]}}, $instr[7], $instr[30:25], $instr[11:8], 1'b0} :
                         $is_u_instr ? {$instr[31:12], 12'b0} :
                         $is_j_instr ? {{12{$instr[31]}}, $instr[19:12], $instr[20], $instr[30:21], 1'b0} :
                                     32'b0;
         ?$rs1_valid
            $rs1[4:0] = $instr[19:15];
         ?$rs2_valid
            $rs2[4:0] = $instr[24:20];
         ?$rd_valid
            $rd[4:0] = $instr[11:7];
         ?$funct3_valid
            $funct3[2:0] = $instr[14:12];
         ?$funct7_valid
            $funct7[6:0] = $instr[31:25];
         $opcode[6:0] = $instr[6:0];
|cpu
      m4+imem(@1)    // Args: (read stage)
      m4+rf(@1, @1)  // Args: (read stage, write stage) - if equal, no register bypass is required
````

![Screenshot 2023-10-18 175243](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/842a86d4-9201-4558-85b9-864d492833c9)

![Screenshot 2023-10-18 175928](https://github.com/lalithlochanr/lalith_riscv/assets/108328466/6817ecbb-44fc-41bf-9dc4-405f48693924)












### Lab for Register File Read










</details>















