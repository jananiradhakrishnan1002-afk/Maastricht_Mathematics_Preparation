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


**7**  **If $y = \sin x$,** write an expression for $\frac{\Delta y}{\Delta x}$ at any point $x$.
**We see later that this $\frac{\Delta y}{\Delta x}$ approaches $\cos x$**






***Practice problems from Prof. Gilbert Strang's Lecture - Max and Min***

