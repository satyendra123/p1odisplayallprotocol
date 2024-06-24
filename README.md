# p1odisplayallprotocol
i have the protocol by which i can send the message to the p10 display

|S|1E    - for setting the id-1
|S|2E    - for setting the id-2
|C|id|6| - clear screen

Note- when i shift the character at the same time in the both the display then both display id will be same even if i have not written the protocol for setting the id
|F|0E    - shfting the character at the left side
|F|1E    - shift one led right side

Note- agar mujhe 5 rows ki display hai to mujhe 5 cards chahiye rhega data send karne ke liye RGB display me.i have used two cards to control the two display this has two rows and two columns
|C|2|4|1|0-0-#GUP2345|    = it will display the UP2345 in the id-2 display board
|C|1|4|1|0-0-#GSID|       = it will display the SID in the id-1 display board. 
