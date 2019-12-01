# CS-Project
Tana 1983.2334
--Original Version, 5 NOP commands replacing call to malicious code at address 00401613

Tana 1983(1.1).exe
--First revision by Jojo
  -Changed malicious call at 00401613 to opcode E81F020000 (calling funkyfunc, which does nothing)

Tana 1983(1.2).exe
--Minor, experimental revisions by Sam
  -Changed instruction at 004015f8 from Sleep(100) (B9640000) to Sleep(50) (B9320000), doubling game cycle speed

Tana 1983(JJ).exe
--Initial Upload by Jojo on 11/26 (og w/malicious code)

Tana 1983(1.3).exe
--jedi1 now consists of entirely NOP commands (to use for our own purposes), called at 00401613

Tana 1983(1.3.2).exe
--Now speeds up on increasing score--moved commands from adressi 00401606 to 00401617, allowing room for SUB ECX,dword ptr[rbp+ -0x8], decreasing sleep cycle (default 100 in this version) by current score. 2 free bytes right after call

Tana 1983(1.4.6).exe
--Rewrote direction change check (where it reads arrow input, now 00401610-61d) to have snake always have '0' as head, allow room for check slowing down speed (more sleep) for vertical directions (from 004016a1-b2)

Tana 1983(1.4.7).exe
--'0' is now the default head of the snake
