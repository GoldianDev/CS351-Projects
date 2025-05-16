# CS351-Projects
Various projects for my CS351 - Computer Architecture course at Sonoma State.

Project 1:

![image](https://github.com/user-attachments/assets/da4d1986-f4df-47c7-8702-5ddbfcf9a1ac)

1. One big difference between hash-00 and every other program is that hash-00 is reading ASCII data instead of binary, however this itself should not make make it so much slower. The other big difference seems to be the way in which the data is actually read - hash-00 specifically reads Data.txt "a value at a time," whereas hash-01 immediately determines how many hashes need to be computed. I imagine that hash-00 is so much slower because it has to reformat the data its reading, one piece at a time.
2. Without optimization, there is small time difference between hash-01 and hash-02, but when optimized, the difference is negligable. 
3. Neither with or without optimization did a fixed-size array run substantially faster or slower.
4. My asusumption is that the memory useage is larger since it is individually accessing and working on each piece of data. Since each bit of data has to be worked on (and thus dereferenced), each piece is added into the programs' address space, resulting in substantially greater memory useage.
5. I did not try any other compiler options (yet)...
