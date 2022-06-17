# Things to know - Light
***



<pre>

</pre>
### 1. Intro stuff
***

#### Triangle extrapolation
[Similar triangles](https://www.mathsisfun.com/geometry/triangles-similar.html) are triangles that only **differ in size**. 

Similar triangles are related (and can be solved) by setting up a ratio of sides:
- $\frac{length_1}{height_1}=\frac{length_2}{height_2}$

	or
	
- $\frac{height_1}{length_1}=\frac{height_2}{length_2}$

	With any one of these being replaced by and unknown or $x$

<pre>
</pre>
#### Michelson experiment
This the one with the spinny thing

To calculate $\Delta t$:

1. Get period ($T$ in $s$)
	
	$T=\frac{1}{f}$
2. Divide period ($T$) by the number of mirrors

	$\Delta t=\frac{T}{\text{number of mirrors}}$
	
3. With $\Delta t$, $v$ can be calculated with $v=\frac{d}{t}$
4. Profit



<pre>

</pre>
### 2. Reflection
***
#### Law of reflection:
1. $\theta_{i}=\theta_{r}$
	- The angle on **incidence** **equals** the angle of **reflection**. The angle is measured from an imaginary line which is perpendicular to the boundary and is called the **normal**.

2. The incident ray, normal, and reflected ray all lie in the same plane.



<pre>

</pre>
### 3. Curved mirrors
***
Curved mirrors still obey the law of reflection ($\theta _i=\theta _r$)
- NOTE: The **normal** is *always the radius of the sphere*

<pre>
</pre>
#### Converging mirror/Concave mirror
1. Light is reflected towards the focal point
2. Light rays parallel to the principal axis are reflected towards a real focal point

<pre>
</pre>
#### Diverging mirror/Convex mirror
1. Light is reflected away from the focal point
2. Light rays parallel to the principal axis are reflected away from a real focal point

<pre>
</pre>
#### Image formation
[[_Light Equations#Mirror equations]]

There are **3 useful rays** which may be used to determine the **position**, **orientation**, and **nature** of the image being formed

Incident rays that are:
1. **Parallel** to the principal axis which will reflect through or away from the **focal point** (depending on whether it is a concave or convex mirror.)
2. Through the **focal point** which is reflected **parallel** to the principal axis
3. Through the **center of curvature** and is reflected **straight back**

Whether or not an image is formed depends on a number of factors
1. Type of mirror
2. Focal length
3. Distance from the mirror to the object

<pre></pre>
##### Mirror characteristics:
1. Focal length ($f$):
	- Concave: Positive ($+$)
	- Convex: Negative ($-$)

2. Distance from mirror to object ($d_o$): 
	- Always positive ($+$)

3. Distance from mirror to image ($d_i$):
	- Real image: Positive ($+$)
	- Virtual image: Negative ($-$)

4. Height of object ($h_o$):
	- Always positive ($+$)

5. Height of image ($h_i$):
	- Real image: Negative ($-$)
	- Virtual image: Positive ($+$)



<iframe src="https://www.desmos.com/calculator/7ytyd4qvy2?embed" width="500" height="450" style="border: 1px solid #ccc" frameborder=0></iframe>


<pre></pre>
##### Mirror info
**<u>Image orientation:</u>** 
- All real images are inverted
- All virtual images are erect

<u>**Image Size:**</u>
- $|d_i|>|d_o|$: Image is bigger
- $|d_i|<|d_o|$: Object is bigger

**$f$**: 
- $f$ is negative if it is a diverging mirror (convex)*
- $f$ is positive for converging mirror (concave)*

\*I could not find this explicitly stated in the notes. It is stated in the practice problems. This might not be entirely correct.


<pre>

</pre>
### 4. Refraction
***
The fastest that light can travel is $c=3.00\cdot10^8m/s$ in a vacuum. Light is always slower in different substances.

$\text{index of refraction} = \frac{\text{speed in vacuum}}{\text{speed in medium}}$
 | $n=\frac{c}{v}$
 
 - $n$ is always greater or equal to 1 and has **no units**
 - the slower the medium is, the bigger $n$ is

<pre></pre>
#### Snell's law
$$
\frac{\text{sin}\theta_{1}}{\text{sin}\theta_{2}}=\frac{\lambda_{1}}{\lambda_{2}}=\frac{v_{1}}{v_{2}}=\frac{n_2}{n_1}
$$

<pre></pre>
#### Special problems

##### Parallel sides:
The emerging ray is parallel to the original ray.
$$
\theta _{\text{original}} = \theta _{\text{emerging}}
$$


##### Triangular prisms:
Since the sides are not parallel, the internal angles of refraction and incidence will not be the same.

<pre></pre>
#### Total internal reflection
When a light ray passes from slow to fast medium, $\theta r>\theta i$. Eventually, $\theta r$ approaches $90^{\circ}$

At the **critical angle** ($\theta c$), $\theta r=90^{\circ}$. Beyond this, refraction no longer occurs. The result is total internal reflection which obeys [[Things to know - Light#Law of reflection | the law of reflection]].

**NOTE:** total internal reflection only happens when passing from low to high speed medium.

<pre></pre>
#### Lenses
Lenses are very similar to [[Things to know - Light#3 Curved mirrors | curved mirrors]].

<pre></pre>
##### Image formation
Uses the [[_Light Equations#Mirror equations | same equations as mirrors]]. Image characteristics are a bit different:


**<u>Mirror characteristics:</u>**
1. Focal length ($f$):
	- Real image: Positive ($+$)
	- Virtual image: Negative ($-$)

2. Distance from lense to object ($d_o$)

4. Distance from lense to image ($d_i$):
	- Real image: Positive ($+$)
	- Virtual image: Negative ($-$)

5. Height of object ($h_o$):
	- Always positive ($+$)

6. Height of image ($h_i$):
	- Real image: Negative ($-$)
	- Virtual image: Positive ($+$)

7. Magnification:
	- Real image: inverted ($-$)
	- Virtual image: upright ($+$)

<pre></pre>
##### Lense info
<u>**Image formation location:**</u>
- Real images form **in front of mirrors** and **behind lenses**.

<u>**Image Size:**</u>
- $|d_i|>|d_o|$: Image is bigger
- $|d_i|<|d_o|$: Object is bigger

**$f$**: 
- $f$ is negative if it is a diverging lense (concave)*
- $f$ is positive for converging lenses (convex)*

\*I could not find this explicitly stated in the notes. It is stated in the practice problems. This might not be entirely correct.

<pre>
</pre>
#### Image formation
[[_Light Equations#Snell's law]]

There are **3 useful rays** which may be used to determine the **position**, **orientation**, and **nature** of the image being formed

Incident rays that are:
1. Parallel to the principal axis which is refracted:
	- Convex lense: <u>towards</u> the <u>real focal point</u> on the other side of the lense.
	- Concave lense: <u>away</u> from the <u>virtual focal point</u>
2. Refracted parallel to the principal axis by traveling:
	- Convex lense: <u>through</u> the <u>virtual focal point</u>
	- Concave lense: <u>towards</u> the <u>real focal point</u>
3. Through the <u>center</u> of the lense and passes straight through


Whether or not an image is formed depends on a number of factors
1. Type of mirror
2. Focal length
3. Distance from the mirror to the object

> Concave/Diverging lense\
> *https://www.desmos.com/calculator/qoyncgtbtd*
> <iframe src="https://www.desmos.com/calculator/fb94sraxm8?embed" width="500" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>

> Concave/Converging lense\
> *https://www.desmos.com/calculator/tagefpyast*
> <iframe src="https://www.desmos.com/calculator/5izof2wtn1?embed" width="500" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>

<pre>

</pre>
### 5. Theory of color
***
#### Subtraction theory of color
White light is composed of:
- Red light
- Green light
- Blue light

When white light hits an object, it reflects some light and absorbs others
- Red objects absorb green and blue light while reflecting red light
- etc

#### Addition theory of color
If different colours of light are combined, new colours will be formed.



<pre>

</pre>
### 6. Polarization
*https://en.wikipedia.org/wiki/Polarization_(waves)*
***
Light travels transversely in multiple planes. A polarized filter only allows one plane to pass.

- 2 filters $90^{\circ}$ to each other lets nearly $0$ light through.



<pre>

</pre>
### 7. Young's double slit experiment
[[_Light Equations#Interference equations | Interference equations]]
***
#### Interference
If two wavelengths are lined up (whole number multiple of wavelength: $\lambda$, $2\lambda$, $\cdots$, $a\lambda$), they **constructively interfere with each other**, meaning that their $\lambda$ add.

If they are not lined up, their wavelengths interfere destructively.

<pre></pre>
#### Young's Experiment
<u>**Description:**</u>\
Light was diffracted through a slit in one screen. It was then diffracted through another screen with 2 slits. The first screen makes sure that the light is coherent (same phase).

After being diffracted through the 2 slits, the screen shows an interference pattern.
- **Bright fringes** are antinodes
- **Dark fringes** are nodes

> [[_Light Equations#Interference equations | Interference equations]]
> 
> When $\theta>10^{\circ}$:
> $$
> \lambda=\frac{d\text{sin}\theta}{n}
> $$
> 
> When $\theta<10^{\circ}$:
> $$
> \lambda=\frac{dx}{n\ell}
> $$
> 
> - Replace $n$ wit $n-\frac{1}{2}$ for destructive interference

