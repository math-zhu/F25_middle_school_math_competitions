**Problem 1**:
Since the last digit of $1000$ is $0$, that means there are 5 total numbers being added together (because $5 \cdot 8 = 40$ which ends in a $0$). Then you need to find out how many $8$'s you need plus 4 (because of the 40), and that will get you to two 8's. Then I just guess-checked and adjusted and got $8+8+8+88+888= 1000$

**Problem 2**:
First, you can easily find out what $A$ is because you can add two 3-digit numbers and the answer has a number greater than 1 in the thousands place. And since you have to carry over a one in this problem, the only answer for $B$ would be $9$. So the final answer is $111+999=1110$

**Problem 3**:
The answer is $715715$ and the trick is to just take that 3-digit number and write it down 2 times because it's multiplying to 1001.

**Problem 4**:
Same as the last problem. The answer is $5,757,575,757$.

**Problem 5**:
$10204060804050$

**Problem 6**:
$12344321$

**Problem 7**:
If you memorize $\frac{1}{7}$, $\frac{2}{7}$, $\cdots$ in decimal, you might be able to recognize that 142857 times 3 is 428571 (which are the decimal places for 1/7 and 3/7). So the answer is $142857$. Or you could just follow the solution in the book.

**Problem 8**:
This problem is a lot like problems $3$ & $4$, it's just $1001001$.

**Problem 9**:
11

**Problem 10**:
$14285714285714285714.2867142867\cdots$.

**Problem 11**:
It's a pattern and it will repeat forever because $1 \div 7 = 0.142857142857\cdots$

**Problem 12**: (They all have 20 zeros at the end.)
* $200\cdots 000: 28571428571428571428\frac{4}{7}$
* $300\cdots 000: 42857142857142857142\frac{6}{7}$
* $400\cdots 000: 57142857142857142857\frac{1}{7}$

You can see that they just repeat the same digits (142857) over and over. 

**Problem 13**:
Just change the order of the number (142857 $\cdot$ 1 = 142857, 142857 $\cdot$ 2 = 285714 etc.)

**Problem 14**:
One example is $\frac{1}{14}$, which also has the 142857 pattern.

**Problem 15**:
Continue from the list in the book: 1101, 1111, 10000, 10001, 10010, 10011, 10100, 10101 and so on.

**Problem 16**:
You can get all because it's exactly like the binary system.

**Problem 17**:
* 14 = 1110 in binary
* 10000 in base 2 equals 16 in decimal

**Problem 18**:
$45 = 101101$

**Problem 19**:
$173$

**Problem 20**:
* 1010 + 101 = 1111
* 1111 + 1 = 10000
* 1011 + 1 = 1100
* 1111 + 1111 = 11110

**Problem 21**:
* 1101 - 101 = 1000
* 110 - 1 = 101
* 1000 - 1 = 111

**Problem 22**:
$1101 \cdot 1010 = 13 \cdot 10 = 130 = 10000010$

**Problem 23**:
$11011 \div 101 = 101.0110011\cdots$

**Problem 24**:
It's $0.010101\cdots$.

**Problem 25**:
$(1+2)+3 = 1+ (2+3)$

**Problem 26**:
Combine 17,999 and one, which makes 18,000, then just add the 357. Which gets you $18,357$.

**Problem 27**:
You can subtract one from 357 to make it 356 and put that 1 in 17,999. Then you need to do 18,000 + 356, which is $18,356$. 

**Problem 28**:
$899+1343+101 = 899+101+1343 = 1000+1343 = 2343$.

**Problem 29**:
$37\cdot 25\cdot 4 = 25\cdot 4\cdot 37 = 100\cdot 37 = 3700$

**Problem 30**:
$125\cdot 37\cdot 8 = 125\cdot 8\cdot 37 = 1000\cdot 37 = 37000$

**Problem 31**:
So all I did was group them by how many parenthesis there were and how many numbers in each parenthesis, and at the end I got 14, listed below:
* 1*(...) gives 5 of them
* ()*5 gives 5 of them
* ((12)3)(45) (1(23))(45)
* (12)(3(45)) (12)(3(45))

The idea for general product of $n$ numbers is below:
* let $f(n)$ be the different ways of inserting parenthesis. We know $f(1)=f(2)=1$ and $f(3)=2$.
* let $m$ be the position of the right parenthesis which multiply by $1$, for example, 
    * $m=3$ for $(1(23))4$, number of ways $f(3)f(1)$
    * $m=4$ for $1((23)4)$, number of ways $f(1)f(3)$
    * $m=2$ for $(12)(34)$, number of ways $f(2)f(2)$
* So the general formula for $n$ numbers is $f(n-1)f(1)+f(n-2)f(2)+...+f(1)f(n-1)$.
* $f(5)=2f(4)+f(3)f(2)+f(2)f(3)=14$.
* $f(6)=2f(5)+2f(2)f(4)+f(3)f(3)=2*14+2*5+4=42$

**Problem 32**:
$99$.

**Problem 33**:
If you pair them together, you get 50 different pairs and each pair's sum equals 101. So $101\cdot 50 = 5050$.

**Problem 34**:
$1001\cdot 20 = (1000 + 1)20 = 20000 + 20 = 20020$

**Problem 35**:
$1001\cdot 102 = 1001(100 + 2) = 100100 + 2002 = 102102$

**Problem 36**:
$(a+b+c+d+e)(x+y+z) = ax+ay+az+bx+by+bz+cx+cy+cz+dx+dy+dz+ex+ey+ez$ so there are $15$ terms. (Or you could have just done 5 times 3 because there are 5 different terms in the first parentheses and 3 in the second one.)

**Problem 37**: $s$ = small vessel and $b$ = big vessel

$s + b = 5$, $2s + 3b = 13$. Then I did $2s + 2b = 10$, and subtracted that from the second equation, you get $b=3$. So from that, you can find the volume of both of them, which is $s=2$ and $b=3$.

**Problem 38**:
Say that $x$ is the number you choose,

$2(x+3) - x - 4 - x = 2$

$2x+6-2x-4=2$

Then since $2x - 2x = 0$, you can completely remove them and get this:

$6-4=2$

So that means that must be true.