# Things to know - Electrostatic and Electric Fields
***
  


### 1. Electrostatic shit
***

- Elementary charge: $e=1.6\cdot 10^{-19}C$

- Electrons are **negative**

- Protons are **positive**

#### Charging
##### Charging by friction
Rubbing two object together allows electrons to move from one object to another
-   Some shit holds onto electrons loosely and other hold onto them tightly<sup>[[Things to know - Electrostatic and Electric Fields#Random Shit | Addendum]]</sup>

<pre></pre>
##### Charging by conduction
When two objects touch, they end up having the same charge.

Charge distribution:
- Larger surface area means it will take more charge
- The charge it takes is proportional to the ratio of their surface areas
	- i.e. if one sphere has twice the surface area of the other, it will have twice the charge.

\*Charging an electroscope causes both the electroscope and the charging device to have the same charge

<pre></pre>
##### Induced charge separation
Moving a charged item near a neutral item causes the like charge in the neutral item to “move out of the way”


<pre>

</pre>
### 2. Laws and stuff
***

**Conservation of Charge**:
-   Net charge stays the same; charge is conserved

**Law of Charges**:
-   Like charges repel and unlike charges attract

**Measuring charge**:
-   Unit is *Coulomb* ($C$) and the symbol for charge is $q$

**Electrons move, protons do not move**

**Distribution of Charges**
-   Conductors allow electricity to flow easily
	-   Charge is distributed around the object evenly*
-   Insulators do not allow electricity to flow very easily. 
	- Charge is not distributed around the object*



<pre>

</pre>
### 3. Coulomb’s Law
[[_Electrostatic and Electric Fields Equations#Coulomb's law | Coulomb's Law]]
***
$$
\begin{align}
F_e &= d\frac{q_1q_2}{r^2} \\
k &= 8.99\cdot 10^9 \frac{N\cdot m^2}{C^2} \\
\end{align}
$$

If 2 or more charges are exerting a force on an object, you must calculate the force in the $x$ and $y$ direction, then use *Pythagoreatn's theorem* to find $F_{NET}$.

Remember the [[Things to know - Electrostatic and Electric Fields#2 Laws and stuff | Law of Charges]] to determine the direction of the force

Also, remember [[Misc#No explicit values given]]



<pre>

</pre>
### 4. Current
*https://en.wikipedia.org/wiki/Electric_current* \
[[_Electrostatic and Electric Fields Equations#Current | Current]]
***
$$
I=\frac{q}{t}
$$



<pre>

</pre>
### 5. Resistance
*https://en.wikipedia.org/wiki/Electrical_resistance_and_conductance*\
[[_Electrostatic and Electric Fields Equations#Resistance | Resistance]]
***
$$
V=IR
$$
**<u>NOTE</u>**: Either;
1. This is not on the formula sheet
<pre>
	or
</pre>
2. I am fucking blind



<pre>

</pre>
### 6. Electric fields
*https://en.wikipedia.org/wiki/Electric_field*\
The direction that a small imaginary **positive** test charge ($q_t$) will move in the electric field.
***
* Electric fields can be produced by $+/-$ charged objects
* Field strength decreases with distance
* Electric fields are vector fields.

<pre></pre>

> [[_Electrostatic and Electric Fields Equations#Electric fields | Electric Field Equations]]
> $$
|\vec{E}|=\frac{\vec{F}_e}{q} \\
> $$
>$\vec{E}$ is absolute. This means we only get the **magnitude**. Remember that the direction of an electric field is defined as:
> - The direction that a small imaginary **positive** test charge ($q_t$) will move in the electric field.
> - [[Things to know - Electrostatic and Electric Fields#Direction of Charges | Direction of charges]]


> [[_Electrostatic and Electric Fields Equations#Electric fields | Electric Field Equation]]
> $$
> |\vec{E}|=k\frac{q}{r^2}
> $$
> <pre></pre>
> Although this equation is on your data sheet, it can be derived using
> - [[_Electrostatic and Electric Fields Equations#Electric fields | Electric Field Equation]]: $|\vec{E}| = \frac{|\vec{F}_e|}{q}$
> - [[_Electrostatic and Electric Fields Equations#Coulomb's law | Coulbom's Law]]: $\vec{F_e} = k\frac{q_0q_2}{r^2}$
> 
> $$
> \begin{align}
> |\vec{E}| &= \frac{k\frac{q_1q_2}{r^2}}{q} \\
> |\vec{E}| &= \frac{k\frac{q_1\cancel{q_2}}{r^2}}{\cancel q} \\
> |\vec{E}| &= k\frac{q}{r^2}
> \end{align}
> $$

#### Static Equilibrium on Conductors
In a conductor, electrons move freely until they reach a state of static equilibrium – i.e. all charges are at rest and experience **no net force**
<pre></pre>
**<u>On a regular shaped object</u>**
- i.e. Sphere, flat surface 
- Even charge all around the object

<pre></pre>
**<u>On an irregularly shaped object</u>**
- i.e. A piece of shit
- Charges accumulate at convex (pointy out) parts of the object.
- Charges spread out at concave (pointy in) parts of the object.

#### Electric field diagram
##### Direction of Charges
Remember that the direction of an electric field is defined as:
-  The direction that a small imaginary **positive** test charge ($q_t$) will move in the electric field.
<img src="https://cdn.kastatic.org/ka-perseus-images/6db3d4851432e3cded684cd6748f779fea347f52.svg" alt="" tabindex="0">

##### Same Charges
Remember [[Things to know - Electrostatic and Electric Fields#Direction of Charges | Direction of charges!]] This diagram does not specify charges
<iframe src="https://www.desmos.com/calculator/r9sulv37pn?embed" width="500" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>

##### Different Charges
Remember [[Things to know - Electrostatic and Electric Fields#Direction of Charges | Direction of charges!]] This diagram does not specify charges
<iframe src="https://www.desmos.com/calculator/1ke2jsz4of?embed" width="500" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>




<pre>

</pre>

### 7. Electric Potential Energy
[[_Electrostatic and Electric Fields Equations#Electric potential | Electric potential equations]]
***
* If work is done against the electric field, potential energy is gained

$$
\Delta V=\frac{\Delta E_p}{q}
$$

This can be used in combination with $E_k$:

$$
\begin{align}
E_p &= E_k \\
\Delta Vq &= \frac{1}{2}mv^2
\end{align}
$$



<pre>

</pre>
### 8. Parallel Plates
Parallel plates create a uniform electric field between the two plates \
[[_Electrostatic and Electric Fields Equations#Parallel plate electric field strength | Parallel plate electric field strength equation]]
***
$$
|\vec{E}|=\frac{V}{d}
$$

#### Millikan's oil drop experiment
The basic design of Millikan’s experiment involved two parallel plates, a distance (d) apart, hooked up to a variable voltage source where the voltage could be adjusted to provide just enough of an electric force to balance the force of gravity on the oil drop.

When the drop is motionless, the $F_E$ and $F_g$ are balanced:
$$
\begin{align}
F_E &= F_g \\
q|\vec{E}| &= mg \\
q\frac{\Delta V}{\Delta d} &= mg \\
\end{align}
$$

Millikan made a few assumptions:     

1. All electrons are identical – each has the same amount of charge.
2. The mass of each electron is so small that the addition or subtraction of a few will not significantly change the mass of the oil droplet.
3. The amount of charge on the oil droplet will be a whole number multiple of the charge of one electron (i.e. 2 e, 7 e, 12 e, etc.).



<pre>

</pre>
### 9. Direction of current
1. <u>Conventional current</u>:
	- $+\rightarrow -$
	- Charge moves from an area of excess (positive) to an area of deficit (negative).

2. <u>Electron current</u>
	- $-\rightarrow +$
	- Electrons (negative) move to positive (positive)


<pre>

</pre>
### Random Shit
1. <u>Ebonite</u> becomes <u>negatively</u> charged when rubbed with fur.
2. <u>Glass</u> becomes <u>positively</u> charged when rubbed with silk.
3. Atoms and shit:
	- Its atomic number is its number of protons
	- Its atomic weight is its number of protons and neutrons