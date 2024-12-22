
# Appended the gem5 repo to implement B1 Instruction

Repo: git clone https://github.com/royharshit/b1_instruction.git b1_instruction -b stable

1. Added B1 Data Port on CPU
2. Added Avg. and Max ROB Occupancy
3. Added Avg. and Max MSHR Occupancy
4. If the req = Data Prefetch, send the packet through B1 port

