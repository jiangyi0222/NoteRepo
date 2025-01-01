- 资料
	- ![CSAPP_2016.pdf](../assets/CSAPP_2016_1713252765986_0.pdf)
	- ![Computer Systems A Programmer’s Perspective (Randal E. Bryant etc.) (Z-Library).pdf](../assets/Computer_Systems_A_Programmer’s_Perspective_(Randal_E._Bryant_etc.)_(Z-Library)_1715772680182_0.pdf)
	- [CSAPP重点解读](https://fengmuzi2003.gitbook.io/csapp3e)
	- [ProjectOpenSource](http://csapp.cs.cmu.edu/3e/labs.html)
	- [csdiy#csapp](https://csdiy.wiki/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%B3%BB%E7%BB%9F%E5%9F%BA%E7%A1%80/CSAPP/#_1)
	- [course web](https://www.cs.cmu.edu/~213/)
	- [b站课程](https://www.bilibili.com/video/BV1iW411d7hd)
- ch1. ![02-03-bits-ints.pdf](../assets/02-03-bits-ints_1713510805575_0.pdf)
	- About the hex to binary，just remember:
		- A 1010    10
		  C 1100    12
		  E 1110     14
	- Numberic Ranges (w is the length of the binary bit) ((662219bc-a564-4554-b3dc-7a2d525b8e05))
		- Unsigned Values
			- UMin = 0;
			- UMax = $2^w - 1$
		- Two's Complement Values(补码）
			- TMin = $-2 ^{w-1}$
			- TMax = $2^{w-1} - 1$
	- Operations
		- Unsigned Addition
			- for  (0 <= x,y < $2^w - 1$) :  x + y = (x+y) mod $2^w$
		- two's complement vaules
			- **when the result isn't overflowed** : just add and truncation the overflow bit
			- **nagetive or positive overflowed** :
			   1101 <sub>-3</sub> + 1010 <sub>-6 </sub> = 0111 <sub>+7 </sub>
			   0111 <sub>+7 </sub> + 0101 <sub> +5 </sub> = 1100 <sub> -4 </sub>
	- nagate numbers(of cource for Two's Complement values) :
		- flip all the bits + 1,  example:
		-
		-
-
-