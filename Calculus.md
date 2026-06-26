Average slope:  

$$
\frac{\Delta y}{\Delta x}
=
\frac{y_2-y_1}{x_2-x_1}
$$

Slope at one point: also known as instant slope: is the derivative of the funcction

$$ \frac{dy}{dx}$$
***Practice problems from Prof. Gilbert Strang's Lecture - Big Picture Derivatives***
1. For $y = 2x^3$, what is the average slope = $\frac{\Delta y}{\Delta x}$ from $x = 1$ to $x = 2$?
2. What is the instant slope of $y = 2x^3$ at $x = 1$?
3. $y = x^n$ has $\frac{dy}{dx} = nx^{n-1}$. What is $\frac{dy}{dx}$ when $y(x) = \frac{1}{x} = x^{-1}$?
4. For $y = x^{-1}$, what is the average slope $\frac{\Delta y}{\Delta x}$ from $x = \frac{1}{2}$ to $x = 1$?
5. What is the instant slope of $y = x^{-1}$ at $x = \frac{1}{2}$?


Q1,2

$$y=2x^3$$
given : two points: at x =1 to x =2
we first compute y values at the given points.
$$
\begin{aligned}
f(1) &= 2(1)^3 = 2 \\
f(2) &= 2(2)^3 = 16
\end{aligned}
$$
$$\frac{\Delta y}{\Delta x}
=
\frac{y_2-y_1}{x_2-x_1}
= \frac{16-2}{2-1}
=\frac{14}{1}
$$
then to find the instant slope , we differentiate the given equation. 

$$
\begin{aligned}
f(x)=2x^3\\
d/dx(x)=6x^2\\
at\ x = 1, f'(x)= 6(1)^3 = 6
\end{aligned}
$$ 
q3.
$$\begin{aligned}
f(x)=\frac{1}{x}\\
f(x)=1.x^{-1}\\
f(x)'=-1x^{(-1-1)}=-1x^{-2}
\end {aligned}
$$
Q4 &. Q5
for  $$y = x^{-1}$$what is the average slope from x = 1/2 to x = 1?
y values at the two given points are:
at x= 1/2 $$y=(\frac{1}{2})^{-1}=(\frac{-1}{2})^{-2}=0.25$$
at x - 1
$$y=1^{-1}=\frac{1}{1}=1$$
Average slope = 
$$\frac{\Delta y}{\Delta x}
=
\frac{y_2-y_1}{x_2-x_1}
= \frac{1-0.25}{1-0.5}
=\frac{0.75}{0.5}=1.5
$$
Instant slope:
$$\begin{aligned}
\frac{d}{dx}x^{-1}=-1x^{-2}=\frac{-1}{x^{2}}\\
\text{at } x=\frac{1}{2}\\\text{ the slope is } \frac{-1}{(\frac{1}{2})^{2}}=\frac{-1}{0.25}=-4 
\end{aligned}$$
**Q6 Suppose the graph of $y(x)$ climbs up to its maximum at $x = 1$. Then it goes downward for $x > 1$**. 
**6A.** What is the sign of $\frac{dy}{dx}$ for $x < 1$ and then for $x > 1$?
**6B.** What is the instant slope at $x = 1$?

before x=1, that is when x<1, y increases, the slope is positive. at x=1, the slope is 0. and when the x>1, slope is negative. 

**7**  **If $y = \sin x$,** write an expression for $\frac{\Delta y}{\Delta x}$ at any point $x$.
**We see later that this $\frac{\Delta y}{\Delta x}$ approaches $\cos x$**

we need two points to calculate slope, but if the point is extremely close to the initial point such that the difference between the two points is almost 0, then such slope is called a derivative
 
 in case of sin(x) let x be the first point and x+h be the second point such that h ->0
in that case f(x) = sin (x) and f(x+h)= sin(x+h)

Change in y : sin(x+h)-sin(x)
change in x: x+h - x = h 
slope:    $$
\frac{sin(x+h)-sin(x)}{h}\\
$$



**Practice problems from Prof. Gilbert Strang's Lecture - Max and Min and Second Derivative**

**1  Which $x^*$ gives the minimum of $y(x) = x^2 + 2x$? Solve $\dfrac{dy}{dx} = 0$**
minimum of the parabola is at its vertex.
the vertex can be given by x = -b/2a
=$$\frac{-2}{2} = -1$$
therefore, the minimum point of y(x) is at x = -1. 
$$\begin{aligned}\\
y(x)'= 2x+2\\\
2x+2 = 0\\
2x= -2
x= -2/2 = -1
\end{aligned}$$



**3 Find the maximum height of $y(x) = 2 + 6x - x^2$. Solve $\dfrac{dy}{dx} = 0$.**
the equation can be re written as:  $$y(x)= -x^{2}+6x+2$$
now we know its a down open parabola , the maximum point is 
$$\begin{aligned}
\frac{-b}{2a}= \frac{-6}{2*(-1)}=\frac{-6}{-2}=3\\
\end{aligned}$$
$$\begin{aligned}
y(x)'=-2x+6\\
at -2x+6=0,  x=\frac{0-6}{-2} = 3
\end{aligned}$$
**4 Find $\dfrac{d^2y}{dx^2}$ to show that this parabola bends down.**
the second derivative is :
$$\begin{aligned}
y(x)'=-2x+6\\
y(x)''=-2\\
\dfrac{d^2y}{dx^2}<0\\
 \text{ =>hence, its a down open parabola}
\end{aligned}$$



**5  For $y(x) = x^4 - 2x^2$ show that $\dfrac{dy}{dx} = 0$ at $x = -1, 0, 1$. Find $y(-1), y(0), y(-1)$.**

when $\dfrac{dy}{dx} = 0$ , the slope is 0 , and those are the peaks (max and min) of the function's graph
to find those points ( max and min), we can do so by differentiating the function, factorizing it by  setting it to 0. 

$$\begin{aligned}
y(x) =x^{4} - 2x^{2}\\
y(x)' = 4x^{3}-4x\\
\text{at } 4x^{3}-4x=0\\
4x(x^2-1)=0]\\
4x= 0 x=0 ----->(1)\\
(x^2-1)= (x+1)(x-1)\\
(x+1)=0, x=-1\\ 
(X-1)=0, x=1\\
therefore, dy/dx =0 \text{ at x = -1,0,1}
\end{aligned}$$ 
6 Now $\dfrac{dy}{dx} = 4x^3 - 4x$. What is the second derivative $\dfrac{d^2y}{dx^2}$? 
$$\dfrac{d^2y}{dx^2}= 12x^2-4$$
**7 At a minimum point explain why $\dfrac{dy}{dx} = 0$ and $\dfrac{d^2y}{dx^2} > 0$.**
At minimum point the point is neither decreasing , nor increasing. So, its horizontal without any upward or downward movement. therefore dy/dx (the slope) is 0.

Likewise, the second derivative tells us how the slope is changing, if its positive, the slope is changing in an upward/positive direction otherwise in a downward direction 


**Practice problems from Prof. Gilbert Strang's Lecture - Exponential Functions**
**1 What is the derivative of $\dfrac{x^{10}}{10!}$? = $\frac{x^{10}}{1}.\frac{1}{10!}$**
derivative: $$10x^{9}.\frac{1}{10!}+x^{10}.0=\frac{10x^{9}}{10!}=\frac{x^9}{9!}$$

**3 Why is $\dfrac{1}{e^x}$ the same as $e^{-x}$?**

exponential property recalled: $$x^a.x^b=x^{a+b}$$$$\begin{aligned}
e^a.e^b=e^{a+b}\\
\text{for }e^{-x}.e^{x}=e^{-x+x}=e^0 = 1\\
\text{so } e^{-x}e^{x}=1\\
e^{-x}=\frac{1}{e^x}
\end{aligned}$$


**4 Why is $e^{-1} = 1 - 1 + \dfrac{1}{2} - \dfrac{1}{6} + \cdots$ between $\dfrac{1}{3}$ and $\dfrac{1}{2}$? Then $2 < e < 3$.**

We know, $e^x = 1 + x + \dfrac{1}{2}x^2 + \dfrac{1}{6}x^3 + \cdots$

when we substitute x = 1 
$e^1 = 1 + 1 + \dfrac{1}{2}1^2 + \dfrac{1}{6}1^3 + \cdots$
$e^1 = 1 + 1 + \dfrac{1}{2}+\dfrac{1}{6}+\cdots = 2.71828... (e)$ - is between 2 and 3 

Since $e = 1 + 1 + \frac{1}{2} + \frac{1}{6} + \cdots = 2.718\ldots$, 
we have $2 < e < 3$.

Then, $e^{-x} = \dfrac{1}{e^x} = \dfrac{1}{1 + x + \dfrac{1}{2}x^2 + \dfrac{1}{6}x^3 + \cdots}$ Taking reciprocals and flipping the inequalities, $$\frac{1}{3} < \frac{1}{e} < \frac{1}{2} \text{ as we can see below}$$
$e^{-1} = \dfrac{1}{e^1} = \dfrac{1}{1 + 1 + \dfrac{1}{2}(1)^2 + \dfrac{1}{6}(1)^3 + \cdots}= \dfrac{1}{2.718...}\text{is in between}\dfrac{1}{3} and \dfrac{1}{2}$


**5 Can you solve $\dfrac{dy}{dx} = y$ starting from $y = 3$ at $x = 0$?**

we know, that $$\begin{aligned}
\frac{dy}{dx}e^x =e^x\\
\text{if }\frac{d}{dx}y = y, \text{ then y must be equal to }e^x\\
\text{so the function is } y = e^x\\ 
\text{when }x = 0, y=e^0= 1\\
y = 3 \text{ when } y =3e^0    
\end{aligned}$$
given $$\frac{dy}{dx}=y=> \frac{dy}{y}=dx$$ 



**Why is $y = 3e^x$ the right answer?**
Because, the  natural exponent is the only function which is the derivative of itself. hence y= e^x


**6 Can you solve $\dfrac{dy}{dx} = 5y$ starting from $y = 1$ at $x = 0$?** **Why is $y = e^{5x}$ the right answer?**

here y = e^5x
for function $$e^{5x} \text{ using chain rule}, \frac{d}{dx}e^{5x}= e^{5x}*5= 5e^{5x} $$
**7 Why does $\dfrac{e^{\Delta x} - 1}{\Delta x}$ approach $1$ as $\Delta x$ gets smaller?**

using the difference quotient / Slope formula  
$$\text{here } {\Delta x} = h$$
$$\frac{dy}{dx}e^x = \frac{e^{x+h}-e^x}{h}$$
at x= 0 and h approaching 0, we can re write the above as:
$$\frac{dy}{dx}e^0 = \frac{e^{0+h}-e^0}{h}= \frac{e^{h}-1}{h}$$
now as h approaches 0 , 
$$\frac{dy}{dx}e^0 \text{ approaches }1$$



**Practice problems from Prof. Gilbert Strang's Lecture - Big Picture: Integrals**
1 What functions $y(t)$ have the constant derivative $s(t) = 7$?
$$\text{anti derivative of  } s(t) = 7 =y(t) = 7t+C$$
2 What is the area from $0$ to $t$ under the graph of $s(t) = 7$?
$$\displaystyle\int_0^t 7 \ dt = \displaystyle\int_0^t 7x$$


3 From $t = 0$ to $2$, find the integral $\displaystyle\int_0^2 7 \, dt =$
antiderivative = 7t 
from t = 0 to 2, = 7(2)-7(0)= 14-0 = 14

4 What function $y(t)$ has the derivative $s(t) = 7 + 6t$?
$$\text{antiderivative of }s(t) = 7t + \frac{6t^2}{2}=7t+3t^2 $$
5 From $t = 0$ to $2$, find area $=$ integral $\displaystyle\int_0^2 (7 + 6t) \, dt$.
$\displaystyle\int_0^2 (7 + 6t) \, dt$ = $$\displaystyle\int_0^2 7t+3t^2 = (7(2)+3(2)^2 )-(7(0)+3(0)^2)=14+12 -0 = 26$$
6 At this instant $t = 2$, what is $\dfrac{d(\text{area})}{dt}$?
the area function is 7t+3t^2, the derivative is s(t) itself which is 7+6t 
at t=2 , its 7+6(2)= 7+12 = 19

7 & 8
 From $0$ to $t$, the area under the curve $s = e^t$ IS NOT $y = e^t$. If $t$ is small, the area must be small. But $t = 0$ has $y = e^0 = 1$. From $0$ to $t$, the correct area under $s = e^t$ is $y = e^t - 1$. The slope $\dfrac{dy}{dt}$ is \_\_\_\_\_ and now $y(0) = ?$ 

$$\begin{aligned}
\frac{dy}{dt}=e^t\\
y(0)=1-1 = 0
\end{aligned}$$
9 Notice $y_0$ in $(y_1 - y_0) + (y_2 - y_1) + (y_3 - y_2) =-y_0+y_3$  The sum of $\Delta y = \dfrac{\Delta y}{\Delta t} \Delta t$ becomes the integral of $\dfrac{dy}{dt} \, dt$ The area under $s(t)$ from $0$ to $t$ becomes $y(t) - y(0)$.

**Practice problems from Prof. Gilbert Strang's Lecture - Derivative of sin x and cos x**

**18.01SC - Single Variable Calculus - Prof. David Jerison https://ocw.mit.edu/courses/18-01sc-single-variable-calculus-fall-2010/pages/1.-differentiation/**
 

PROBLEM SET 1: 

Slope and Derivative

a) Use the difference quotient definition of derivative to calculate the rate of change of the area of a disk with respect to its radius. (Your answer should be the circumference of the disk.)

area of a disk with radius r is :  $$function is: A(r)=\pi.r^2$$
now the when r changes by "h" 

$$\text{difference quotient} = \frac{f(r+h)-f(r)}{h}$$
putting it in the area function:
$$\text{difference quotient} = \frac{\pi.(r+h)^2 -\pi r^2}{h}= \frac{\pi r^2+\pi h^2+\pi2rh -\pi r^2}{h}=\frac{\pi h^2+\pi2rh}{h}=\frac{h(\pi h+\pi2r)}{h}$$

**1C-3** Calculate the derivative of each of these functions directly from the definition.

a) $f(x) = 1/(2x + 1)=1*(2x+1)^{-1}$
$f'(x)=-1(2x+1)*2=-2(2x+1)$

d) $f(x) = 1/\sqrt{x}=1*x^{\frac{-1}{2}}$
$f(X)=\frac{-1}{2}.x^{\frac{-1}{2}-1}=\frac{-1}{2}.x^{\frac{-3}{2}}=\frac{-1}{2\sqrt{x^{3}}}$


---

**1C-4** Write an equation for the tangent line for the following functions:

a) $f(x) = 1/(2x+1)$ at $x = 1$ 
$f'(x)=-1(2x+1)*2=-2(2x+1)\text{at x = 1 }f'(1)=-2(2(1)+1)= -6$
b) $f(x) = 2x^2 + 5x + 4$ at $x = a$
$f'(x)=4x+5, at x =a , f'(a)=4(a)+5$

---
**1D-1** Calculate the following limits if they exist. If they do not exist, then indicate whether they are $+\infty$, $-\infty$ or undefined.

a) $\displaystyle\lim_{x \to 0} \dfrac{4}{x - 1}$  

substituting 0 , we get : 
$\displaystyle\lim_{x \to 0} \dfrac{4}{x - 1}=\frac{4}{0-1}=\frac{-4}{1}=-4$

c) $\displaystyle\lim_{x \to -2} \dfrac{4x^2}{x + 2}$
$\dfrac{4(-2)^2}{-2+2}=16/0$
denominator is 0 

from the right , using-1.9 $\dfrac{4(-1.9)^2}{-1.9+2}=\dfrac{14.44}{0.1}=144.4$
from the left side using $\dfrac{4(-2.1)^2}{-2.1+2}$=-176.4 
hence the left and right sides head somewere differnet and not to a same point 
the limit is undefined

d) $\displaystyle\lim_{x \to 2^+} \dfrac{4x^2}{2 - x}$ 

=$\dfrac{4(2)^2}{2-2}=16/0$

the limit is not defined at 2.  
from the right side, lets try plugging in 2.1.

= $\dfrac{4(2.1)^2}{2-2.1}=\dfrac{4.41*4}{-0.1}=-176.4.$

plugging in 2.01
$=\dfrac{4(2.01)^2}{2-2.01}=\dfrac{16.1604}{-0.01}=-1616.04.$

so as x appraches 2 from the right, the value increases and goes towards −∞


f) $\displaystyle\lim_{x \to \infty} \dfrac{4x^2}{x - 2}$
as x increases the numerator increases in a faster rate than the denominator


g) $\displaystyle\lim_{x \to \infty}\dfrac{4x^2}{x - 2} - \frac{(4x)(x-2)}{x-2}$
$=\dfrac{4x^2}{x - 2} - \dfrac{(4x)(x-2)}{x-2}= \dfrac{4x^2 - 4x^2 + 8x}{x-2}$ 
$=\dfrac{+8x}{x-2}$

dividing by the highest degree term of denominator 
=$\dfrac{\dfrac{8x}{x}}{\dfrac{x}{x}-\dfrac{2}{x}}=\dfrac{8}{1-\dfrac{2}{x}}$

as x increases,, 2/x approaches 0 
so $\dfrac{\dfrac{8x}{x}}{\dfrac{x}{x}-\dfrac{2}{x}}=\dfrac{8}{1-0}=8$

j) $\displaystyle\lim_{x \to 2} \dfrac{x - 2}{x^2 - 4}$
$\dfrac{x-2}{(x+2)(x-2)}$
$=\dfrac{1}{(x+2)}$
=1/4= 0.25

---
**1D-3** Identify and give the type of the points of discontinuity of each of the following:

a) $\dfrac{x - 2}{x^2 - 4}$ 

finding the discontinuity:
setting the denominator to 0, 
x^2 -4 = 0 
x= +/- 2

factoring the above equation:
$\dfrac{(x - 2)}{(x-2)(x+2)}$
=$\dfrac{1}{x+2}$
(x-2) cancels so x = 2  is a fixable dicontinuity 
however, x = -2 is not fixable , its infinite discontinuity

---
b) $\dfrac{1}{\sin x}$

at x = 0 , $\pi$, and every $\pi$, sin is 0. 
So at n$\pi$, sin is 0 
it doesnt cancel , so infinite discontinuity


c) $\dfrac{x^4}{x^3}=x$ 
it cancels completely and the dicontinuity is completely removable 


d) $f(x) = \begin{cases} x + a, & x > 0 \\ a - x, & x < 0 \end{cases}$
here, at x =1 1+a and x = -1 a+1
both sides agree. 
however, at x = 0 we don't have a defined function
at x = 0, f(x) = a is a function that removes this discontinuity


e) $f'(x)$, for the $f(x)$ = $\begin{cases} x + a, & x > 0 \\ a - x, & x < 0 \end{cases}$ 
f'(x)= 1 for x>0 and -1 for x < 0
these are not agreeing. so there is a jump discontinuity

f) $(f(x))^2$, where $f(x) = \dfrac{d}{dx}|x|$ ---->  
|x|=$\begin{cases} x, & x >0 \\ -x, & x<0 \end{cases}$
$\dfrac{d}{dx}|x|$= $\begin{cases} 1, & x >0 \\ -1, & x<0 \end{cases}$
$(f(x))^2= \begin{cases} 1, & x >0 \\ 1, & x<0 \end{cases}$
the function f(x)=1 at x =0 removes discontinuity


**1D-5** Define $f(x) = \begin{cases} ax + b, & x \geq 1 \\ x^2, & x < 1 \end{cases}$


a) Find all values of $a, b$ such that $f(x)$ is continuous.

b) Find all values of $a, b$ such that $f'(x)$ is continuous. (Be careful!)

---

**1D-6** For each of the following functions, find all values of the constants $a$ and $b$ for which the function is differentiable.

a) $f(x) = \begin{cases} x^2 + 4x + 1, & x \geq 0 \\ ax + b, & x < 0 \end{cases}$
$\qquad$ b) $f(x) = \begin{cases} x^2 + 4x + 1, & x \geq 1 \\ ax + b, & x < 1 \end{cases}$
