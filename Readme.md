# M3DPSPST
The M3DPSPST instances includes three types of instance sets: C3, C2, and C4, with a total of 320 test cases. 

"Instances" folder provides all the example files, among which Ins1-1 to Ins11 are the C2 example set, Ins13 to Ins24 are the C3 example set, and the rest are the C4 example sets. Each TXT file sequentially describes information such as the number of nodes, machines, vehicles, and node coordinates. For example, 

node	machine	vehicle
2	3	1		==## number of nodes, machines and vehicle.==			
0	40	50     	       ==## index of node and node coordinates.==
1	23	60
jobs
8			         ==## number of jobs.==
1	1	3	3	8  ==## index of job, the job's customer node, processing time on machine 1, machine2,...==

setuptimes
0	3	1	15	3	9	6	2	10
0	0	7	4	9	7	7	13	11

"Solutions" folder shows a detailed scheduling plan for each instance, including the order of vehicle access and the order of workpiece processing.

The CSV files provide detailed results for each instance sets, including detailed parameters such as gap and runtime.