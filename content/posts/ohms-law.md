---
title: "Ohm's Law"
description: A detailed explanation of Ohm's Law
date: 2022-12-25T16:41:18+05:30
url: /posts/ohms-law/
image: images/ohms-law.png
authorImageUrl: "https://atulhost.com/wp-content/uploads/2019/07/indian-flag-full-hd-tricolour-flag-of-india-waving.jpg"
libraries:
    - mathjax
draft: false
---
Ohm’s law gives the relationship between the current flowing through the conductor and the potential difference between the ends of the conductor.
For all the other physical parameters being constant, the current flowing through a conductor is proportional to the voltage across the conductor.
Thus, 
 $$ i = \frac{v}{r} $$
Where i= current flowing through the conductor (ampere)
v=voltage across the conductor (volt)
r=resistance offered by the conductor (ohm)

A Simple Circuit Diagram: 

![](https://lh6.googleusercontent.com/qtlS_lS73ZxtRfh3ac5KC79LVBrW2kE2HnhsCvx1I614uXOqIvfgweTAYIEvUbQNxgsGs-8QzS77g6lHhZKeaVp5-tuFfZwRfdxHlarxTLbmkbV_3OFh-SYrtQvmGgbKNrpmpEFsceF04vPEphzE9DGV1ou9yF9_04YeHI59QKgyBFiZAhSnM3vpij72htNzmarkbFnbcA)
|Key| Value    |
|---|----------|
| B | Battery  |
| K | Key      |
| V | Voltmeter|
| A | Ammeter  |
| R | Resistor |

Here is an example graph to find the resistance of a conductor using the above circuit.

![](https://lh4.googleusercontent.com/UFqIb77tKV90x9bljRlE9NjAqNsPE1jO41dr9_S1TZUxvRe3blUM6pSfTClJy-C4gUClTXWov3S-xLR9SMEcWbqlQ89tTV2DgSE5lydtfgK4Y7Q8WoHCN6hZ-YlPpa1sL7ZPMCORk7imLbg9V5omKaRViqtjokt-btkP2wDE_FQEkntcvoPr2D4Nl78r1Os2_8RCsTe-fA)

## Factors Affecting Resistance

**Length of the conductor:** - As the length of the conductor increases, resistance increases.

**Cross-sectional area:** - As the cross-sectional area of conductor increases, resistance decreases.

**Temperature:** - As temperature of the conductor increases, the resistance increases.

**Material:** - Keeping length, cross-sectional area and temperature constant, resistance changes with the material of the conductor. 
(E.g., resistance of Platinum > Iron > Aluminium > Gold > Copper > Silver. )

Hence:
$$ r\alpha\frac{l}{A} $$
$$ r = \frac{\rho l}{A} $$
$$ \rho = \frac{rA}{l} $$

Where r=resistance of the conductor

l = length of the conductor (meter)
A = Area of cross-section of the conductor. (square meter)
ρ = Specific resistance of the conductor. (ohm-meter)

**Specific resistance** of a conductor is the resistance offered by the conductor of unit length and unit cross-sectional area. Specific resistance is the property of a material.

Human body acts as a variable resistor. Dry skin has enough resistance to keep the currents produced by moderate to low voltages. If skin is wet, its resistance decreases to allow the high electric currents to pass through. A current as low as 1mA causes mild electric shock, while currents of 15mA can cause loss of muscle control and currents of 100mA can cause death.

General observation: - It’s our common experience to see Birds sitting on high tension wire without getting hurt. The reason is the bird is sitting on the wire with it’s legs attached to the HT wire. 

Electric current flows only when the circuit is closed. So, circuit is not closed and the bird is safe. 

If the bird holds the wire with one leg and another leg to the earth, then the damage occurs. Since earth has a high resistance and is very good conductor of electricity, electric current flows through the bird’s body causing instant death.

{{<boxmd>}}
Why conventional current flows from positive terminal to negative terminal?
{{</boxmd>}}

By the time electric current invented, electrons were not discovered. Scientists are of the opinion that atom is the smallest building block and is indivisible. They thought that some positive particles are carrying the charge from positive terminal to negative terminal. Later electrons were discovered and found that electrons are the charge carriers. Hence electron movement is opposite to conventional current movement.

## Resistors in a Series

Let R1, R2, R3 are connected in series as shown in circuit diagram.

![](https://lh3.googleusercontent.com/2NWTGYWBgUYnnAil7FIVjji6KWgLiMjUv71dC58LQSB-AnyZTMk-WNpbuoddwn5Kmydm3-qLLvLh8V_ws7OW95fJkWtLJS1j500zEYthc_Lrh5hYXyemJ3NRhtASczpDDfz4QcW-oxy7u3BzD4LZ5N_LIhP9zeefKdZ7HrJb4BlrQEAuiIM4enGEUALP26vJpGgIAdPJ9g)

Let a current i flows through the circuit. The same current flows through the resistors, but the voltage(V) changes as the resistance of the resistors is different.

According to Ohm’s law, V=ir
$$ \therefore V_1  = iR_i; V_2 = iR_2; V_3 = iR_3 $$
$ Since, V = V_1 + V_2 + V_3$
$$V = iR_1 + iR_2 + iR_3 $$
$$\frac{V}{i} = R_{effective} = R_1 + R_2 + R_3$$

A numerical example to understand better. Let 1 Ω ,2 Ω ,3 Ω resistors are connected in series as shown in the circuit diagram to a 12V battery. Then the effective resistance of the circuit is 6 Ω (1 + 2 + 3 = 6).

## Resitors in Parallel

Let R1, R2, R3 are connected in parallel as shown in circuit diagram.

![](https://lh6.googleusercontent.com/b_BEaB5_qokE8s7dzQym8-L4_RCdB7I0yBmo1DIsDk4fLLBtU8VW_9yTQvWiOEpvJns7Ngju3_1dDw4Ro8iMjoF3rID9XqL-8-dg9FLocAIDFNPQffngBfsDjrmxf4vutybcaIxM81Lc06vgW3R964VO_MHtIabDeNsvE0VjZAGp_CqYY03YPhmU7FU5_PX39gqf2ZXbtA)

Let I be the current flowing in the circuit and V be the voltage supplied by the battery. Since the resistors are connected in parallel, voltage across the resistors is same across them and the current flowing through the resistors changes as per Ohm’s law.

$$ as V = ir \to i = \frac{V}{r} $$
$$ i_1 = \frac{V}{R_1}; i_2 = {V}{R_2}; i_3 = \frac{V}{R_3}$$
$$ i = i_1 + i_2 + i_3 $$
$$ \frac{V}{R} = \frac{V}{R_1} + \frac{V}{R_2} + \frac{V}{R_3}$$
$$ \frac{1}{R} = \frac{1}{R_1} + \frac{1}{R_2} + \frac{1}{R_3} $$
$$ R_{effective} = \frac{R_1R_2R_3}{R_1 + R_2 + R_3} $$

Now let us input the same resistances in the parallel circuit also. i.e.,

$$ R_1 = 1\Omega; R_2 = 2\Omega; R_3 = 3\Omega $$
$$ R_{effective}  = \frac{1\times 2\times 3}{1 + 2 +3} = 1\Omega $$

Hence when resistors are connected in series, the effective resistance increases and when connected in parallel decreases.

## Resistors in Series AND Parallel ?

We will try to learn with an example.
![](https://lh4.googleusercontent.com/PZpCWxuUp77eCCMlJ4cMH55AT5eChz_tfbTAU_qTxETigV3Xjm0hzE2ROyABXgeGIMEbujyYcXEwYt0mz4JIT5l_wfh0KmdLFD9SaemifHtq2LZ6WQX2uThqJF0NGFDnRtHwzG8epsUGuys5fQkMowgZr1FGDl7hULqrMXjSC280UMdSWrPy_Z-oiVsey655iwSyAorpcw)

First, we have to find out the effective resistance of the circuit.
The effective resistance of the parallel resistors 6.0 Ω and 9.0 Ω is 3.6 Ω
$$ R_{effective} = \frac{6\times 9}{6 + 9} = 3.6\Omega $$
This 3.6 Ω resistance is in series with 3.0 Ω resistance. Thus, the effective resistance of the circuit is 6.6 Ω

The current flowing in the circuit is 
$$ i = \frac{V}{r} = \frac{12.0}{6.6} = 1.\overline{81} amp $$
So, 1.81 amp current flows through 3.0 Ω resistor.

Voltage across 3.0 Ω resistor is $ V = 1.\overline{81}\times 3 = 5.43 V $

Now current flowing in the parallel circuit of 6.0 Ω and 9.0 Ω is (since the circuit is parallel to the battery, voltage is same i.e., 12.0 V)
$$ i  = \frac{V}{r} = \frac{12.0 V}{3.6 \Omega} = 3.3 amp $$
This 3.3amp current is divided between the resistors 6.0 Ω and 9.0 Ω.
$$ i_{6.0} = 3.3 \times \frac{6}{15} = 1.\overline{33} amp $$
$$ i_{9.0} = 3.3 \times \frac{9}{15} = 2.0 amp $$

## Ananlyzing Circuits
Let's Analyze another circuit:
![](https://lh6.googleusercontent.com/k4MkuFp9PRzUGxO86z-Fd9zWxWb8viucPzYNGpX_JFpj_0dGhabQFEuxU8NtkA9SrpsZaW7c7kRm2NnnGDPlxE3Ys36aIsciGSyExP1mK58IWqySZc9NEJV-9wSZRxOSOx7W0-R51oH31oAKMvHYgiUODEx1_JYP7yGFl_vTtPFYu4weaAIDd_YlE2XtgT6yDGAsgc2UJg)

Effective resistance between 30.0 Ω, 50.0 Ω and 90.0 Ω resistance is $ R_{effective} = \frac{30\times 50 \times 90}{30 + 50 + 90} = 42.35\Omega$
Effective resistance of the circuit= 20.0 + 42.35 = 62.35 Ω

Therefore 0.192amp current flows through the parallel circuit, now the voltage of this circuit is 
$$ V = 0.192 \times 42.35 = 8.13 V $$
Since (30 Ω,50 Ω),90 Ω are parallel, Voltage is same and we have to find out the current flowing through each resistor.
$$ i_{90} = \frac{8.13}{90.0} = 0.090 amp $$
$$ i_{50} = \frac{8.13}{80.0} = 0.1018 amp $$

Let us check According to Kirchoff’s law of currents, the current entering into the junction must be equal to current leaving the junction.

Hence 0.090 + 0.1018 = 0.1918 amp

50 Ω and 30 Ω are in series, same amount of current(0.1018 amp) flows through them. But voltage is different. Let us calculate the voltage

Voltage Across $ 90.0\Omega = 8.13 V$
Voltage Across $50.0\Omega = 0.1018 \times 50 = 5.09 V $
Voltage Across $ 30.0\Omega  = 0.1018 \times 30 = 3.05 V$

Next, 20 Ω resistor is in series with 42.35 Ω resistor. 
∴ current flowing through them is same. i.e., 0.192 amp. But voltage is different. Let us calculate the Voltage across 20 Ω resistor.
$$ V_{20} = 0.192 \times 20 = 3.84 V $$
![](https://lh3.googleusercontent.com/-kqVfIu9f2NBZf1trTiUaEEyGK9V1DokoGEBGOZh7yfxGKyowFqF0WHlBy_Px3UQzR-TyLJ6UNAADGj2HRevP8kF9JD5HptS-U8E9zOlv95X9nM4LagRyvPf0rC1TWFUVBlNAfVf3S-csNJP_XwBtip0LCc_OlZSQLREMWtgQfMOcSll8rkB_p5jqYp4Ur2SJEdm-K25ig)

Let us analyse one more circuit
![](https://lh3.googleusercontent.com/ZeCpvgQC0z4BA32mLj7A-zLRQXlQC6l43q3E1KIElOuho9zEJk0qmpyOovS0HzLJFVEo2ACE5J_CmKOsnYm5ctcbjC8TvLsHpea6mXtXNpJp4l9cnIcI2moqvLT24VpEXBRqvxYMWEogso4JbCOz6v84WJSggjXv93AcvbJXjAf-i3OYCzU5S9Dkfq3n9IKJG3VAwQIaXQ)

a. Effective resistance between 600 Ω and 400 Ω
$$ R_{effective} = \frac{600 \times 400}{600 + 400} = \frac{240000}{1000} = 240\Omega $$
b. Effective resistance between 240 Ω and 560 Ω {240 Ω and 560 Ω are in series.}
$$ R_{effective} = 240\Omega + 560 \Omega = 800 \Omega $$
c. Effective resistance of the circuit [800 Ω and 800 Ω are in parallel]
$$ R_{effective} = \frac{800 \times 800}{800 + 800} = 400 \Omega $$

Current Flowing in Circuit = $ i = \frac{V}{r} = \frac{12 V}{400 \Omega} = 3.0 \times 10^{-2} A = 30 mA $

Let us find out the current flowing in (c)
800Ω is parallel to 800Ω and is parallel to battery. Hence the voltage across the load is 12V
$$ i = \frac{12 V}{800 \Omega} = 1.5 \times 10^{-2} A = 15 mA $$
800Ω is the effective resistance of 240Ω and 560Ω. Which are in series. Hence current is same but voltage is different.
$$ i_{560} = 1.5 \times 10^{-2} A $$
$$ V_{560} = 1.5 \times 10^{-2} \times 560 = 8.4 V$$
$$ i_{240} = 1.5 \times 10^{-2}$$
$$ V_{240} = 1.5 \times 10^{-2} \times 240 = 3.6 V $$

240 Ω is the effective resistance of the parallel resistors 600 Ω and 400 Ω.

Hence voltage across the resistors is same. i.e., 3.6 V. But current flowing through them is different.
$$ i_{600} = \frac{3.6 V}{600 \Omega} = 0.6 \times 10^{-2} A = 6.0 mA $$
$$ i_{400} = \frac{3.6 V}{400 \Omega} = 0.9 \times 10^{-2} A = 9.0 mA $$
