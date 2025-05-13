# me502-assignment-5--ordinary-differential-equation-solved
**TO GET THIS SOLUTION VISIT:** [ME502 Assignment 5- Ordinary Differential Equation Solved](https://www.ankitcodinghub.com/product/me502-assignment-5-ordinary-differential-equation-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93090&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ME502&nbsp;Assignment 5- Ordinary Differential Equation&nbsp;Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
ME502

Assignment 5: Ordinary Differential Equation

A. Solving Initial value problem (Ordinary differential equation with initial condition):

We want to solve following ODE (Ordinary differential equation) y′ = f(x,y) where y(x0) = y0;

i.e. we want to get values of y(x) at different x points (0 &lt; x &lt; L) such that it satisfy the above ODE.

Different Numerical Methods:

</div>
</div>
<div class="layoutArea">
<div class="column">
1. Euler Method:

where h = xn+1 − xn. 2. Mid Point Method:

</div>
<div class="column">
yn+1 =y(xn+1)=yn +hf(xn,yn),

</div>
</div>
<div class="layoutArea">
<div class="column">
yn+1 =y(xn+1)=yn−1 +2hf(xn,yn), Detailed Algorithm for Mid Point Method:

</div>
</div>
<div class="layoutArea">
<div class="column">
where h = xn+1 − xn. Input:

<ol>
<li>(a) &nbsp;Initial value (x0, y0),</li>
<li>(b) &nbsp;End point L,</li>
<li>(c) &nbsp;No. of steps N,</li>
<li>(d) &nbsp;Function f(x,y): Should be provided as different function,</li>
<li>(e) &nbsp;Analytical Solution (if available), y = g(x): Should be provided as another function for error calculation</li>
</ol>
Algorithm:

(i) h = L−x0 ; N

(ii) Initialize a one dimensional array yval[N] with yval[0] = y0; (iii) esum = 0, (To calculate L2 norm of error);

(iv) y1 =y0+hf(x0,y0);(FirststepbyEulermethod)

(v) esum = esum + (y1 − g(x0 + h))2; (vi) yn−1 = y0; xn−1 = x0;

</div>
</div>
<div class="layoutArea">
<div class="column">
(vii) yn =y1;xn =x0 +h;

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
(viii) For i=2:N

yn+1 =yn−1 +2hf(xn,yn);

yval[i] = yn+1;

esum = esum + (yn+1 − g(xn + h))2; xn = xn + h;

yn−1 = yn, yn = yn+1;

End For(i)

(ix) eL2 = N1 √esum;

3. Runge-Kutta method of second order (RK2):

y n + 1 = y n + 12 ( k 1 + k 2 ) , k1 =hf(xn,yn),

k2 =hf(xn+1,yn +k1),

where h = xn+1 − xn.

4. Runge-Kutta method of fourth order (RK4):

y n + 1 = y n + 16 ( k 1 + 2 k 2 + 2 k 3 + k 4 ) , k1 =hf(xn,yn),

k2 = hf (xn + h , yn + k1 ), 22

k3 = hf (xn + h , yn + k2 ), 22

</div>
</div>
<div class="layoutArea">
<div class="column">
k4 =hf(xn+1,yn +k3), Detailed Algorithm for RK4 Method:

</div>
</div>
<div class="layoutArea">
<div class="column">
where h = xn+1 − xn. Input:

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol>
<li>(a) &nbsp;Initial value (x0, y0),</li>
<li>(b) &nbsp;End point L,</li>
<li>(c) &nbsp;No. of steps N,</li>
<li>(d) &nbsp;Function f(x,y): Should be provided as different function,</li>
<li>(e) &nbsp;Analytical Solution (if available), y = g(x): Should be provided as another function for error calculation</li>
</ol>
Algorithm:

(i) h = L−x0 ; N

(ii) Initialize a one dimensional array yval[N] with yval[0] = y0; (iii) esum = 0, (To calculate L2 norm of error);

(iv) yn = y0;xn = x0;

2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
(v) For i=1:N

k1 =hf(xn,yn);

k2 =hf(xn +h,yn +k1); 22

k3 =hf(xn +h,yn +k2); 22

k4 =hf(xn+1,yn +k3);

yn+1 = yn + 61 (k1 +2k2 +2k3 +k4); yval[i] = yn+1;

esum = esum + (yn+1 − g(xn + h))2; xn = xn + h;

yn = yn+1;

End For(i)

(vi) eL2 = N1 √esum;

Problem 1: Let us consider following initial value problem

xy′ − 2y = x3, where y(1) = 6.

We want to find distribution of y in 1 &lt; x &lt; 6 by above four numerical methods. Analytical

solution of above ODE is given as

y(x) = x3 + 5×2.

<ul>
<li>Write a function which calculate f(x,y) in y′ = f(x,y).</li>
<li>Write another function which calculate analytical solution g(x) = x3 + 5×2.</li>
<li>Write four different functions Euler, Midpt, RK2, RK4 where for each function INPUTS: x0, y0, L, N and

OUTPUTS: yval[N],eL2.

In each of these functions, functions f(x,y) and g(x) will be called for required calculation.</li>
</ul>
<ol>
<li>(a) &nbsp;Find yval[N] for N = 5,10,20 for all four methods. You should represent your output in tabular form. Table 1 represent one such table for N = 5. There will be similar
x Analytical,y(x) yn (Euler) yn (MidPoint) yn (RK2) yn (RK4) 1.0

2.0 3.0 4.0 5.0 6.0

Table 1: Values of yn for different methods for N = 5. tables for N = 10 and N = 20. [10+4+4=18]
</li>
<li>(b) &nbsp;Find eL2 for N = 2, 5, 10, 15, 20, 25 for all four methods. Represent your results in tabular form as shown in Table 2 [12]
3
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
N Euler MidPoint RK2 RK4 2

5 10 15 20 25

Table 2: L2 error norms for different methods. B. Solving system of initial value problems:

Consider following system of initial value problems

u′(x) = f(x, u, v), u(a) = u0,

v′(x) = g(x, u, v), v(a) = v0,

where we want to find u(x) and v(x) in a &lt; x &lt; b such that both u and v satisfy above

coupled ODEs.

Runge-Kutta of Fourth order (RK4) for system of ODEs:

</div>
</div>
<div class="layoutArea">
<div class="column">
u n + 1 = u n + 16 ( k 1 + 2 k 2 + 2 k 3 + k 4 ) , k1 =hf(xn,un,vn),

</div>
<div class="column">
v n + 1 = v n + 16 ( l 1 + 2 l 2 + 2 l 3 + l 4 ) , l1 =hg(xn,un,vn),

</div>
</div>
<div class="layoutArea">
<div class="column">
l2 =hg(xn +h,un +k1,vn +l1), k3 =hf(xn +h,un +k2,vn +l2), l3 =hg(xn +h,un +k2,vn +l2),

Detailed Algorithm for RK4 Method for system of ODEs: Input:

1. Initial value (x0, u0, v0),

2. End point L,

3. No. of steps N,

4. Function f(x,u,v) and g(x,u,v): Should be provided as different function,

5. Analytical Solution (if available), u = l(x), v = m(x): Provided for error calculation.

Algorithm:

(i) h = L−x0 ; N

(ii) Initialize two one dimensional arrays uval[N] with uval[0] = u0 and vval[N] with vval[0] = v0;

4

</div>
</div>
<div class="layoutArea">
<div class="column">
k2 =hf(xn +h,un +k1,vn +l1),

222 222

</div>
</div>
<div class="layoutArea">
<div class="column">
222 222 k4 =hf(xn+1,un +k3,vn +l3), l4 =hg(xn+1,un +k3,vn +l3),

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
<ol start="3">
<li>(iii) &nbsp;esumu = 0, esumv = 0 (To calculate L2 norm of errors for both u and v);</li>
<li>(iv) &nbsp;un = u0;vn = v0;xn = x0;</li>
<li>(v) &nbsp;For i=1:N

k1 =hf(xn,un,vn);

l1 =hg(xn,un,vn);

k2 =hf(xn +h,un +k1,vn +l1);

l2 =hg(xn +h,un +k1,vn +l1); 222

k3 =hf(xn +h,un +k2,vn +l2); 222

l3 =hg(xn +h,un +k2,vn +l2); 222

k4 =hf(xn+1,un +k3,vn +l3);

l4 =hg(xn+1,un +k3,vn +l3);

u n + 1 = u n + 61 ( k 1 + 2 k 2 + 2 k 3 + k 4 ) ; vn+1 = vn + 61 (l1 +2l2 +2l3 +l4); uval[i] = un+1;

vval[i] = vn+1;

esumu = esumu + (un+1 − l(xn + h))2; esumv = esumv + (vn+1 − m(xn + h))2; xn = xn + h;

un = un+1;

vn = vn+1;

End For(i)
</li>
<li>(vi) &nbsp;euL2 = N1 √esumu;</li>
<li>(vii) &nbsp;evL2 = N1 √esumv;</li>
</ol>
Problem 2: Let us consider following system of initial value problem

</div>
</div>
<div class="layoutArea">
<div class="column">
222

</div>
</div>
<div class="layoutArea">
<div class="column">
y′ =yz+y, wherey(1)=e, ′ 2ex

</div>
</div>
<div class="layoutArea">
<div class="column">
z =− y , wherez(1)=2.

We want to find distribution of y and z in 1 &lt; x &lt; 5 by RK4 method. Analytical solution

</div>
</div>
<div class="layoutArea">
<div class="column">
of above set of ODEs is given as

y(x) = x2ex, z(x) = x2.

• Write two functions which calculate f(x,y,z) in y′ = f(x,y,z) and g(x,y,z) in z′ = g(x,y,z) .

<ul>
<li>Write two functions l(x) and m(x) which calculate two analytical solutions.</li>
<li>Write the function RK4system where

INPUTS: x0, y0, z0, L, N and

OUTPUTS: yval[N],zval[N],eyL2,ezL2.

In RK4system, functions f(x,y,z),g(x,y,z),l(x),m(x) will be called for required calculation.

5
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
x Analytical,y(x) yn (RK4) Analytical,z(x) zn (RK4) 1.0

1.8 2.6 3.4 4.2 5.0

Table 3: Values of yn and zn for RK4 method for N = 5.

<ol>
<li>(a) &nbsp;Find yval[N] and zval[N] for N = 5,10,20 with RK4 method. You should represent your output in tabular form. Table 3 represent one such table for N = 5. There will be similar tables for N = 10 and N = 20. [10+4+4=18]</li>
<li>(b) &nbsp;Find ey L2 and ez L2 for N = 2, 5, 10, 15, 20, 25. Represent your results in tabular form as shown in Table 4 [12]</li>
</ol>
N eyL2 ezL2 2

5

10 15 20 25

Table 4: Error norms (eyL2 and ezL2).

C. Expressing higher order ODE as system of first order ODEs:

Let us consider following higher order ODE

y′′′ −xy′′ +y′ −8y4 =ytanx, wherey(1)=5,y′(1)=0,y′′(1)=10

We can express above equation as system of 3 first order ODEs as below

</div>
</div>
<div class="layoutArea">
<div class="column">
y′ = u, u′ = v,

′4

v =ytanx+8y −u+xv

</div>
<div class="column">
y(1) = 5 u(1) = 0 v(1)=10

</div>
</div>
<div class="layoutArea">
<div class="column">
Problem 3: Let us consider following higher order ODE

3y′′ +xy′ −3y+20x+5×2 =0subjectedtoy(0)=10,y′(0)=19.

We want to find distribution of y and y′ in 0 &lt; x &lt; 5 by RK4 method. Analytical solution of above ODE is given as

y=x3 +5×2 +19x+10 6

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
x Analytical,y(x) yn (RK4) Analytical,y′(x) yn′ (RK4) 0.0

1.0 2.0 3.0 4.0 5.0

Table 5: Values of yn and yn′ for RK4 method for N = 5.

<ol>
<li>(a) &nbsp;Find yval[N] and y′ [N] for N = 5,10,20 with RK4 method. You should represent
your output in tabular form. Table 5 represent one such table for N = 5. There will be similar tables for N = 10 and N = 20. [10+4+4=18]
</li>
<li>(b) &nbsp;Find eyL2 and ey′L2 for N = 2,5,10,15,20,25. Represent your results in tabular form as shown in Table 6 [12]</li>
</ol>
N eyL2 ey′L2 2

5

10 15 20 25

Table 6: Error norms (eyL2 and ey′ L2).

</div>
</div>
<div class="layoutArea">
<div class="column">
val

</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</div>
