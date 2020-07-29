question A:  
  
0000000000000790 T main  
0000000000000768 T _Z7averageif  
000000000000073a T _Z7averagePdRd  
-------------------------------------  
question B:  
  
output:  
  
    1 8  
    4 8  
    4 8  
    8 8  
  
why:  
  
    Each variable has its own data type, and each data type has its own memory.  
    EX:Character for 1 byte, Interger for 4 bytes, Float for 4 bytes, Double for 8 bytes, and pointer for 8 bytes.  
    In this program. though pa, pb, pc, pd had been annouced their data type like pa for char, but we added "*" before it.  
    So, they are actually the pointer for saving variable's memory address, and the variable's data type should be same with pa, pb, pc, and pd.  
    Because pa, pb, pc, and pd are pointer, so each of them would take 8 bytes for memory.  
