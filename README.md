# firstfit
First fit Algorithm
Implementation:
1- Input memory blocks with size and processes with size.
2- Initialize all memory blocks as free.
3- Start by picking each process and check if it can
   be assigned to current block. 
4- If size-of-process <= size-of-block if yes then 
   assign and check for next process.
5- If not then keep checking the further blocks.
