---
title: "Tension Force"
description: Pulleys-Atwood machine
date: 2023-02-09T19:34:35+05:30
url: /posts/tension-force/
image: images/tension-force.jpg
authorImageUrl: "https://atulhost.com/wp-content/uploads/2019/07/indian-flag-full-hd-tricolour-flag-of-india-waving.jpg"
libraries:
    -mathjax
draft: false
---
## The Atwood Machine
The above system is called Atwood machine.
To find the acceleration and tension in the cable, we have to write the force equations for the masses $ m_1$, $m_2$

$$F_(g1)= m_1 g  and $$
$$F_(g_1)= m_2 g$$
$$F_{g_2}-F_T=m_2 a$$
$$F_T=F_{g_2}-m_2 a$$
$$F_T=m_2 g - m_2 a$$
for mass 
$$m_1$$
$$F_T - F_{g1} = m_1 a$$
$$m_2g-m_2a-m_1g = m_1a$$
$$(m_2-m_1)g = (m_1+m_2)a$$
$$a=\frac{(m_2-m_1)g}{m_1+m_2}$$
$$F_T=m_2g-m_2a$$
$$F_T=m_2g-m_2\frac{(m_2-m_1)g}{m_1+m_2}$$
$$F_T=\frac{2m_1m_2g}{m_1+m_2}$$
We need not do the numerical problem for this as is jusst plugging in the numbers to get the answer.

But how to remember the formula?

To find the acceleration, we are using the Newton's 2^nd law.
$$\sum{F_(net)}=ma$$
Here m is the total mass and net force is the difference in weights of the masses. $F_g$ is nothing but weight.

Tension is the net force acting on any of the masses. Since tension in the sstring is same, we can calculaatae it easily from the force diagram.


Next problem-

Two boxes are connected by a cord running over a pulley. The coefficient of kinetic frictiion between box A and the table is $ \mu_k $ We ignore the mass of the cord and pulley and any friction in the pulley, which means we can asume that a force applied to one end of the cord will have the same magnitude at the other end. We wish to find the acceleration, a of the system, which will have the same magnitude for both assuming the cord doesn't strect. As box B moves down, box A moves to the right.

Let us write the force equation for $ m_2 $
$$\sum{F_y}=F_T-F_g=-m_2a$$
negaative sign indicates mass $ m_2 $ is going down. (we consider downwaaard directiion as negative)

Force equation for $ m_1 $
$$\sum{F_y}=F_N-F_g=0$$
$$\therefore{F_N}=F_g$$ but
$${F_fr}=\mu_kF_N$$
$$F_fr=\mu_km_1 g$$
$$\sum{F_x}=F_T-F_fr=m_1 a$$
$$F_T=F_fr+m_1 a$$
substituting $ {F_T} $ in the equation 1
$$F_fr+m_1 a - m_2 g=- m_2 a$$
$$(m_1+m_2)a=(m_2 - \mu_km_1)g$$
$$a=\frac{(m_2 -\mu_km_1)g}{(m_1+m_2)}$$

To understand better, we will input some numerical values.

$$m_1=7kg; m_2=3kg; \mu_k = 0.20;g=10m/s^2 $$
$$a=\frac{(3-(0.20)7)\times10}{7+3} = 1.6m/s^2$$

{{<boxmd>}}
**Avoid THIS MISTAKE: generally, students do the mistake by seeing the right-side forces (tension and weight) of the second mass balance each other, hence tension is equal to weight of the second mass. But that is not true. Here the block is going down with an acceleration.**
{{</boxmd>}}

## Numericals

 Two masses m_A = 3.0 kg and m_B=7.0 kg are on inclines and are connected together by a ssstring as shown in fig. The coefficient of kinetic friction between each mass and its incline is $ \mu_k=0.30 $ If $ m_A $ moves up, and $ m_B $ moves down, determine their acceleration. [Ignore masses of the frictionless pulley and the cord.]
 Let us write the force equations for the blocks A and B.
 Block A goes up and block B goes down. since blocks are tied together their tension and acceleration are same.
 Block A (direction of motion of block A is taken as positive)
 $$\sum F_yA = F_NA - m_A \times g \times\cos\cos \theta A  =0$$
 $$F_NA=3.0 \times 9.8\times \cos\cos 60°=14.7N$$
 $$F_fr=\mu F_{NA}= 0.3 \times 14.7=4.41N$$
 $$\sum F_{XA}=F_T -F_fr -mg\sin\sin\theta A = m_A a$$
 $$F_T - (F_fr+mg\sin\sin\theta A)=m_A a$$
 $$F_fr+mg\sin\sin\theta_A = 4.41+25.46=29.87N$$
 $$F_T - 29.87N=3.0(a)\to1$$
Block B  
$\sum F_{yB} = F_{NB} - m_B \times g \cos\cos 30° =59.40N $
$$ F_{fr} = \mu F_{NB} =0.3 \times 59.40 = 17.83N $$
Direction of motion of block B is taken as positive.
$$\sum F_{xB}=-F_T -F_fr + mg\sin\sin\theta_B = m_B\times a$$
$$-F_T - 17.83N+7.0\times 9.8\times \sin\sin30^0=m_B\times a$$
$$-F_T +16.48N=7.0(a)\to2$$
Adding equations (1)and (2)
$$F_T -29.87N+(-F_T +16.48N)=3.0(a)+7.0(a)$$
$$-13.39=10.0(a)$$
$$a= -1.34m/s^2$$

Suppose the coefficient of kinetic friction between m_A and the plane in fig.is 
$\mu_k = 0.20$ and that $m_A=m_B=m$.  As m_B moves down, determine the magnitude of the acceleration of $m_A$ and $m_B$ and given $ \theta =35^0 (a)$ What smallest value of $\mu_k$ will keep the system from accelerating? [ignore masses of the (frictionless) pulley and the cord.]
Both the blocks have the same mass and block B is going down, so acceleration is negative. Eventually, Block A moves up so acceleration is positive.(we are taking upward forces as positive and downward forces as negative.)
$$\sum F_{yB} = F_T - F_g = -ma$$
$$F_T=F_N - mg\cos\cos\theta = 0$$
$$F_fr = \mu F_N$$ 
$$\sum F_xA=F_T - F_fr - mg\sin\sin\theta = ma$$
$$a=\frac {(1-\mu \cos\cos\theta - \sin\sin\theta) g}2 = 0$$
$$\mu _k\cos\cos\theta = 1 - \sin\sin\theta$$
$$\mu _k = \frac {1-\sin\sin\theta}{\cos\cos\theta}$$
$$\mu _k = 0.52$$

