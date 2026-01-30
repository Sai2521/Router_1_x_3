# Router_1_x_3
Router 1 x 3 verilog implementation
<br>
<img width="1181" height="594" alt="image" src="https://github.com/user-attachments/assets/8f1799d4-762a-4545-b9ca-8b63a55a0081" />

//////////////////////////////////////////////////Architecture//////////////////////////////////////////////////////////////////////////
<img width="705" height="543" alt="image" src="https://github.com/user-attachments/assets/609301ea-64bb-43f2-963a-4db65f240625" />

////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

Routing is the process of moving a packet of data from source to destination and enables messages to pass from one computer to another and eventually reach the target machine. A router is a networking device that forwards data packets between computer networks. It is connected to two or more data lines from different networks (as opposed to a network switch, which connects data lines from one single network). This project, mainly emphasizes upon the study of router device, its top level architecture, and how various sub-modules of router i.e. Register, FIFO, FSM and Synchronizer are synthesized, and simulated and finally connected to its top module.

///////////////////////////////////////////////////////state diagram///////////////////////////////////////////////////////////////////////
<img width="601" height="484" alt="image" src="https://github.com/user-attachments/assets/23cef75b-5348-48d1-a5ae-b3f9a90c41c2" />
<img width="1465" height="663" alt="image" src="https://github.com/user-attachments/assets/9088b057-a08e-4d38-af71-84d8d7fdf47f" />

//////////////////////////////////////////////////////////////synthesis///////////////////////////////////////////////////////////
<br>
////////fifo/////////////
<br>
<img width="4631" height="2785" alt="image" src="https://github.com/user-attachments/assets/f3acd1e0-2e99-48a4-9060-55cc027ca97a" />

////////register/////////
<br>
<img width="4647" height="1533" alt="image" src="https://github.com/user-attachments/assets/16b2e1c5-89bb-467e-97dc-f3f77d113401" />

///////controller////////
<br>
<img width="4532" height="1739" alt="image" src="https://github.com/user-attachments/assets/79b9403f-9ffc-43fe-a2bc-c201caec070f" />

//////synchronizer///////
<br>
<img width="4606" height="2110" alt="image" src="https://github.com/user-attachments/assets/ae2c6c1c-9eba-4ab0-b117-3bdb0609dd0f" />

//////////top///////////
<br>
<img width="4623" height="2398" alt="image" src="https://github.com/user-attachments/assets/57411674-a8c8-4f94-b14f-aa142f7412c3" />
