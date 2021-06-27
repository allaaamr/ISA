# ISA
Harvard Architecture is the digital computer architecture whose design is based on the concept where there are separate storage and separate buses (signal path) for instruction and data. It was basically developed to overcome the bottleneck of Von Neumann Architecture.

Possible Operations on this Instruction Set Architecture


R1 = R1 + R2 R1 = R1 - R2
R1 = R1 * R2
R1 = IMM
IF(R1 == 0) { PC = PC+IMM } R1 = R1 & R2 R1 = R1 | R2
PC = R1 || R2
R1 = R1 << IMM | R1 >> 32 - IMM R1 = R1 >> IMM | R1 << 32 - IMM R1 = MEM[ADDRESS] MEM[ADDRESS] = R1
