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
