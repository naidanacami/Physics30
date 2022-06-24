This page is for miscellaneous information that is applicable for each unit
***

### No explicit values given
***
When a question gives no explicit values and only gives increases/decreases of values
> Ex:\
> Two point charged objects produce an electric force of $0.0620N$ on each other. What is the electric force if the distance between them increases three times and one of the charges is doubled? 

<u>**Solving:**</u>
1. Get original equation\
$f(x)=x$

2. Multiply/divide the variables that were increased/decreased\
$ax$

3. Separate the coefficients\
$a\cdot x$

4. Substitute in the original equation\
$f(x)a$

5. Profit

> Example:\
> Two point charged objects produce an electric force of $0.0620N$ on each other. What is the electric force if the distance between them increases three times and one of the charges is doubled? 
> 
> 1. Get original equation
> $$
> F=0.062N=\frac{kq_1q_2}{r^2}
> $$
> 
> 2. Multiply/divide the variables that were increased/decreased
> $$
> \frac{k2q_1q_2}{(3r)^2}
> $$
> 
> 3. Separate the coefficients
> $$
> \frac{kq_1q_2}{r^2}\cdot\frac{2}{9}
> $$
> 
> 4. Substitute in the original equation
> $$
> F\cdot\frac{2}{9}
> $$
> 
> 5. Profit
> $$
> 0.062\cdot\frac{2}{9}=0.0138N
> $$

<pre></pre>
#### Abridged ver.
<u>**Solving:**</u>
1. Get original equation\
$f(x)=x$

2. Set each variable to $1$. Add the changes that the question says to the variables\
$x = a\cdot 1$

3. Substitute the variables into the original equation\
$x=a$

4. This number is the ratio between the old and the new value. Multiply the old value with it to get the new value\
$af(x)$

> Example:\
> Two point charged objects produce an electric force of $0.0620N$ on each other. What is the electric force if the distance between them increases three times and one of the charges is doubled? 
> 
> 1. Get original equation
> $$
> F=0.062N=\frac{kq_1q_2}{r^2}
> $$
> 
> 2. Set each variable to $1$. Add the changes that the question says to the variables\
> $$
> \begin{eqnarray}
> k=1\\
> q_1=1\cdot 2\\
> q_2=1\\
> r=1\cdot 3\\
> \end{eqnarray}
> $$
> 
> 3. Substitute the variables into the original equation
> $$
> \frac{1\cdot2\cdot1}{3^2}=\frac{2}{9}
> $$
> 
> 4. This number is the ratio between the old and the new value. Multiply the old value with it to get the new value
> $$
> \frac{2}{9}\cdot 0.062=0.0138
> $$



<pre>

</pre>
### Pendulum at rest
***

When the pendulum is at rest, $F_{NET}=0$
<iframe src="https://www.desmos.com/calculator/qqtbeyeeok?embed" width="500" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>

That means that:

$$
\begin{align}
F_t^2 &= F_a^2+F_g^2 \\\\
\sin\theta &= \frac{F_a}{F_t} \\\\
\cos\theta &= \frac{F_g}{F_t} \\\\
\tan\theta &= \frac{F_a}{F_g}\\\\
\end{align}
$$


Ex:\
A $3.0\cdot 10^{-4}kg$ pith ball hangs from a $1.0m$ long thread between two vertical, parallel plates that are $0.10m$ apart, as shown in the given diagram. When the potential difference across the plates is $420V$, the pith ball deflects $0.010m$ to the side and comes to rest.

What is the magnitude of the electric force that deflects the pith ball?

$$
\tan\theta = \frac{F_E}{F_g}
$$

We first need to get $\theta$
$$
\begin{align}
\tan\theta &= \frac{o}{a} \\
\tan\theta &= \frac{1}{0.01} \\
\theta &= \tan^{-1}\left(\frac{0.01}{1}\right) \\
\theta &= ~89.4270613^\circ
\end{align}
$$

We can now find $F_E$
$$
\begin{align}
\tan\theta &= \frac{F_E}{F_g} \\
F_g\cdot\tan\theta &= F_E \\
m\cdot g\cdot\tan\theta &= F_E \\
F_E &= (3.0\cdot10^{-4})\cdot(9.81)\cdot\tan\left(\tan^{-1}\left(0.01\right)\right) \\
F_E &= 2.9\cdot 10^{-5}
\end{align}
$$