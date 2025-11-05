**Problem 136**: Sine $(a+b)^5=a^5+5a^4b+10a^3b^2+10a^2b^3+4ab^4+b^5$, you can just plug $2x+1$ and find the first term, which is $a^5$, or $(2x)^5=32x^5$

**Problem 137**: So the degree of $P\cdot Q$ is $m+n$, because $x^m\cdot x^n=x^{m+n}$ and the coefficent of it would be the coefficent of $P$ multiplied by the coefficent $Q$.

**Problem 138**: 
* $a)$ It is $9$ because a degree of $9$ is bigger than a degree of $7$
* $b)$ The degree of that would have a degree that is $\le 7$

**Problem 139**: So since the equation with $x$ has a degree $10$ and you substitute $y^7\cdots$ with $x$ then that means you get $(y^7\cdots)^{10} \cdots$ so the highest possible degree for that would be $70$.

**Problem 140**: It degree of the quotient would be $4$ because a degree $7$ equation divided by a degree $3$ always has a degree $4$ as the quotient. The remainder may be $0$, $1$, $2$, or undifined.

**Problem 141**: Assume that we have $P$ divided by $S$, then who ahve two possible quotients, which are $Q_1$ and $Q_2$ and two remainders, $R_1$ and $R_2$. So we have
* $P=Q_1S+R_1$
* $P=Q_2S+R_2$

So you can change that into:

$R_1-R_2=Q_2S-Q_1S=(Q_1-Q_2)S$

So $R_1-R_2$ is the difference of tthe two polynomials of degree smaller than the degree of $s$. So ttheir difference must have a degree smaller than the degree of $S$ and it cannot be a multiple of $S$, so $Q_1-Q_2=0$ is also $Q_1=Q_2$ and $R_1=R_2$. 

**Problem 142**: The fraction is already proper in this case, so the quotient is equal to $0$ and the remainder is equal to the dividend.

**Problem 143**: 

* $(a)$: $x^2+x+1$
* $(b)$: $x^3+x^2+x+1$
* $(c)$: For here you can see a pattern, if you have $x^n-1$ divided by $x-1$ then you get $1+x+\cdots+x_{n-1}$. So by applying that to this question you get $1+x+x^2+...+x^8+x^9$.
* $(d)$: $x^2-x+1$
* $(e)$: $x^3-x^2+x-1$ with a remainder of $2$

**Problem 144**: You start with $1+x+x^2+\cdots + x^{n-1}=\frac{x^n-1}{x-1}$, and when $x=2$ you get $1+2+2^2+\cdots + 2^{n-1}=\frac{2^n-1}{2-1}=2^n-1$

**Problem 145**:
* $(a)$: If $n\ge 1$ then it works because $1$ is a root of $x^n-1$
* $(b)$: Since $x+1$ is equal to $x-(-1)$, that means $-1$ is a root of $x^n+1$, so it is divisible when $n$ is a positive odd number.

**Problem 146**: 
* $(a)$: $x^4+5x-6=(x-1)(x+2)(x^2-x+3)$
* $(b)$: $x^4+3x^2+5x+1=(x+1)(x^3-x^2+4x+1)$
* $(c)$: $x^3-3x-2=(x-2)(x+1)(x+1)$

**Problem 147**: Since $P$ is divisible by $x-1$ that means that $1$ is a root of $P$. So $P=(x-1)\cdot Q$ for some polynomial $Q$. And if you substitute $2$ for $x$ then you can find that $2$ is a root of $Q$, so $Q$ is divisible by $x-2$, so that means that $Q=(x-2)\cdot R$ for some polynomial $R$. So $P=(x-1)(x-2)R$

**Problem 148**: The answer is $5$ because any larger polynomial it will be a degree six or more since there are six or more $x$'s.

**Problem 149**: You just have to check if $1$ and $-1$ are roots of $P$.

**Problem 150**: So I tested out different possible values for $n$ and $x^n-1$ is only divisible by $x^2-1$ when $n$ is a multiple of $2$, so if $x=1$, then you get $0$, so it is a root. And for $-1$, it is a root only when $n$ is a even number. 

**Problem 151**: 
* If $x=1$, then you substitute $x$ for $1$ you get (by using the equation in the hint) $P(1)=(1^2-1)(quotient)+(a+b)=a+b$, so $P(1)=a+b$
* If $x=-1$, then substitue and you get $P=((-1)^2-1)(quotient)+(-a+b)$, so $P(-1)=(-a+b)$
So $b=(P(1)+P(-1))/2$ and $a=(P(1)-P(-1))/2$.

**Problem 152**: Since $x^2-1$ is divisible by $x-1$, so you get $P(x)=Q(x)(x^2-1)+5x-7$, and since you need to find what the remainder is when $P(x)$ is divided by $x-1$ you just need to plug $1$ in the first equation and you get $-2$.

**Problem 153**: For $(a)$, $(b)$, and $(c)$, I just substituted the new roots with the polynomial $P$.
* $(a)$:
 $$(x-1)^3+(x-1)^2-10(x-1)+1$$
 $$=x^3-3x^2+3x-1+x^2-2x+1-10x+10+1$$
 $$=x^3-2x^2-9x+10$$

* $(b)$: 
    $$(\frac{1}{2}x)^3+(\frac{1}{2}x)^2-10(\frac{1}{2}x)+1$$
    $$=\frac{1}{8}x^3+\frac{1}{4}x^2-5x+1$$
* $(c)$: Asummeing that $x=\frac{1}{x_1}$, and put $x$ into $P$ then you get 
$$(\frac{1}{x})^3+(\frac{1}{x})^2-10(\frac{1}{x})+1$$
$$=\frac{1}{x^3}+\frac{1}{x^2}-\frac{10}{x}+1$$



**Problem 154**: Since $x^2-3x+2$ is divisible by $x-1$ and $x-2$, then $x-1$ and $x-2$ must also be divisible by $x^3+ax^2+x+b$. So that means that if you plug in $1$ and $2$ into this equation they both must equal to $0$ since they are both the roots of $x^3+ax^2+x+b$.
* If $x=1$: $1^3+a1^2+1+b=1+a+1+b=a+b+2=0$. So $a+b=-2$.
* If $x=2$: $2^3+a2^2+2+b=8+4a+2+b=4a+b+10=0$. So $4a+b=-10$

By using those two equations, $a+b=-2$ and $4a+b=-10$, then you can find that $a=-2\frac{2}{3}$ and $b=\frac{2}{3}$. So by pluging $a$ and $b$ in the first equation you get the final answer which is $x^3-\frac{8}{3}x^2+x+\frac{2}{3}$

**Problem 155**: 
* $P(0)=0^3-2=-2$
* $P(1)=1^3-2=-1$
* $P(2)=2^3-2=6$
* $P(3)=3^3-2=25$
* $P(4)=4^3-2=62$
* $P(5)=5^3-2=123$
* $P(6)=6^3-2=214$

**Problem 156**: Since it is all double differences, you can write it as $P(n)$, $P(n+1)$, and $P(n+2)$ and plug each expression into the equation $x^2-x-4$.

* $P(n)=n^2-n-4$
* $P(n+1)=(n+1)^2-(n+1)-4=n^2+2n+1-n-1-4=n^2+n-4$
* $P(n+2)=(n+2)^2-(n+2)-4=n^2+4n+4-n-2-4=n^2+3n-2$

Now you find the difference between each adjacent equations:

* $P(n+1)-P(n)=2n$
* $P(n+1)-P(n+2)=2n+2$

And take the difference again:
* $(2n+2)-(2n)=2$

So the difference between each double difference is $2n-2$, so the difference between each double difference will be the same.


**Problem 157**: By doing the same trick as the problem before, you get this:

* $P(n)=an^2+bn+c$
* $P(n+1)=an^2+(2a+b)n+a+b+c$
* $P(n+2)=an^2+(4a+b)n+4a+2b+c$

Then you take the difference between each adjacent equation:

* $P(n+1)-P(n)=(an^2+(2a+b)n+a+b+c)-(an^2+bn+c)=2an+a+b$
* $P(n+2)-P(n+1)=(an^2+(4a+b)n+4a+2b+c)-(an^2+(2a+b)n+a+b+c)=2an+3a+b$

And then you take the difference again:

* $(2an+3a+b)-(2an+a+b)=2a$

So that means that for all $a$, $b$, $c$, and $n$ values their second difference will always be the same.


**Problem 158**: should be $3a^2$

**Problem 159**: 
* $P(1)=43$
* $P(2)=47$
* $P(3)=53$
* $P(4)=61$
* $P(5)=71$
* $P(6)=83$
* $P(7)=97$
* $P(8)=113$
* $P(9)=131$
* $P(10)=151$

So all of them are all prime. Yes, it will all be prime up to $n=10$.

**Problem 160**: Since $P(x)=ax+b$ you can substitute $x$ for $1$ and $2$, and you get 

$$P(1)=a+b=7$$
$$P(2)=2a+b=5$$

By using those two equations you get $a=-2$ and $b=9$, so the answer is $P(x)=-2x+9$

**Problem 161**: By using the same formula from Problem 160, you get

$$P(1)=a+b=0$$
$$P(2)=2a+b=0$$

So that means $a$ must be $0$ so $b$ also must be $0$, so for any $P(x)$ you will always get $0$.


**Problem 162**: No. If you were to look at the polynomial $P(x)=(x-1)(x-2)=x^2-3x+2$. So if $x$ were to equal $1$ or $2$ then the answer would be $0$ but any other number would be a non-zero answer.

**Problem 163**: For the previous problems, we used $P(x)=a(x-1)(x-2)$ when $x$ doesn't exceed degree 2, and $a$ would equal to $1$. To solve this problem you have to find a value for $a$ that would satisfy the equation. If you substitute $x$ for $3$, then you get $P(3)=a(3-1)(3-2)=2a=4$ so $a=2$, so the final equation would be $2x^2-6x+4$ 

**Problem 164**: Consider that $R(x)=P(x)-Q(x)$ amd it's degrees doesn't exceed $2$. And we also know that $R(x_1)=R(x_2)=R(x_3)=0$. In other words, $x_1$, $x_2$, and $x_3$ are the roots of the polynomial $R(x)$. But since the degree cannot exceed $2$, then we know that it cannot have more than two roots unless it is equal to $0$. Therefor $R(x)$ is equal to $0$ and $P(x)=Q(x)$

**Problem 165**: By subtracting the last equation by the middle equation and also subtract the middle equation by the first equation you get:

* $100a+10b+c=0$ subtract by $49a+7b+c=0$: $51a+3b=0$
* $\cdots=33a+3b=0$

And by subtracting both equations by each other you get $18a=0$, so $a$ must be equal to $0$. Now by pluging $a=0$ to each equation, you get:

* $4b+c=0$
* $7b+c=0$
* $10b+c=0$

You can minus the first and the second equation or the second and the last equation, it doesn't matter because you get the same thing, which is $3b=0$, so $b=0$. And by pluging in $b=0$ to all the equation you get $c=0$ for all three equations. So $a=b=c=0$. 

**Problem 166**: Similar to Problem 164. If there are two, then their difference has $n+1$ roots which is possible only when it is zero. So the difference is zero.

**Problem 167**: 
* $(a):2(x-1)(x-2)$
* $(b): -2(x-1)(x-3)$
* $(c):3(x-2)(x-3)$
* $(d):3x^2-13x+16$

**Problem 168**: For $P(0)=1$, that means that $ax^3+bx^2+cx+d$ when $x=0$ then it equals to $1$, so that means $d=1$. For $P(1)=2$, that means that all of the coeffiecents of the cubic equation added together is equal to $2$, which gets you $a+b+c+1=2$ or $a+b+c=1$. For $P(2)=7$, it will be $8a+4b+2c+1=7$ or $8a+4b+2c=6$. And for $P(-1)=2$, you get $-a+b-c=1$. By using these equation you can do this:

$$P(-1)+P(1)=2b=2$$

So $b=1$. Then:

$8(P(1))-P(2)$

You get $8a+8b+8c=8$ and $8a+4b+2c=6$, and substract them, which you get $4b+6c=2$, and by using our previous info that $b=1$, you can plug that in to get $6c=-2$, so $c=-\frac{1}{3}$. Then by using all of this information you can plug $b$ and $c$ into $P(1)$ or $a+b+c=1$, and when plug in $b$ and $c$ you get $a+1-\frac{1}{3}=1$ you find that $a=\frac{1}{3}$. So using all of that you get a final equation of $\frac{1}{3}x^3+x^2-\frac{1}{3}x+1=0$. 



**Problem 169**: skip   

**Problem 170**: skip

**Problem 171**: The minimal degree is $10$ because $P(x)=(x-1)...(x-10)$ and $P(11)=10!=3268800$.

