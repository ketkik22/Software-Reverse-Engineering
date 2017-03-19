# Software-Reverse-Engineering

We used a shareware developed by I2D solutions for reverse engineering. It’s a 3D minesweeper. What we did is we disassembled the program into machine code using Ollydbg. Then we looked into memory map and loaded the .rdata onto CPU dump. We then checked for the string in dump and find all the functions from where it is referenced and patched the code. 

It’s a demo version and registered version can be bought for $14.95 from http://www.i2d.com.au/catalog/bomb3d/buy.html. Once we were done with reverse engineering, we were able to decrese or increase the time in seconds which were left to close the game.

