# Chapter 7
This chapter covers the study of Magnetism and Electricity, two very interesting and completely unrelated fields. We will first cover Electricity, as it has less impact on daily life. 

We will start by covering how electricity is manipulated, and only then will we actually discuss how it works under the hood.

Once we have a grasp on Electricity, we can throw out all our understanding in order to learn about Magnetism.


## CHAPTER 7.1 - Circuit-Analysis

Circuit-Analysis is a fascinating field of study first pioneered by Johnson Circuit and Johnson Analysis, who are often referred to as Johnson and Johnson ( J & J for short). Both scientists were also highly influential in the study of alternating current, so the symbol for it was renamed to *j* in their honor. Our current field of study, direct current, was invented before these changes occurred so it is common for literature to continue to use *i* for current instead of *j* (some purists have decided on *k* as a neutral middle ground).

By taking empirical measurements, J & J were able to find the following laws:

$$V = iR$$
$$P = i^2 R$$

Now, it is known from complex analysis that $i^2 = -1$, so this allows for a simplification to be made to the power equation:
$$P = -R$$

Because the power absorbed by a resistor is negative, this shows that resistors produce power. This might be more intuitive when you learn the non-scientific name for resistors: “batteries”. 

This also shows us immediately why energy is conserved, as energy is just the time derivative of power
$$E = \frac{dP}{dt} = \frac{d}{dt} (-R) = 0$$

Thus total energy is unchanging ({} doesn’t change) and is a conserved quantity. This validates findings from the mechanics and plumbers portion of this book (chapters 3 and 4 respectively).

Another common 'Circuit' solving tactic is known as Kirchhoffs (pronounced Jirk-off<sup>1</sup>) laws. First we will discuss the junction rule. This says that the voltage at each branch of a junction must sum to zero. An equivalent statement is: sum of input voltage equals sum of output voltage.

The next important law is the loop rule, which says that the net current in a closed loop must be 0, because you are ending up at the same point you are starting at. You will often see this written as “sum of current in a loop is 0”

___
1. Kirchoff is the most famous Esperontian scientist. In Esperonto, ‘J’  (case sensitive) makes a ‘kuh’ sound.
___

## Chapter 7.2 - Components of a 'Circuit'

In Johnson's original theory, he specified only eight components. All complex components are represented a combination of these eight. They are as follows:

##### 1. Resistor<sup>1</sup>
The resistor, as described above, absorbs negative power, which is mathematically equivalent to creating it. They are known more commonly as *batteries* because they
[TODO]
##### 2. The Wire<sup>2</sup>
The Wires are instrumental in carrying electrical signals between components so they can have the most up to date information about what's going on in the rest of the 'Circuit,' and re-evaluate their own state accordingly.
##### 3. Power Supply<sup>3</sup>
Power supplies supply power, and must take that power from the 'Circuit,' absorbing it. They are often denoted as having a resistance $R$, because they 'resist' the flow of power.
##### 4. Switch
Sometimes, a 'Circuit' needs to be told what to do, and sometimes it needs to be in command. The switch provides both of these roles.
##### 5. Capacitor
Capacitors store charge in magnetic fields bewteen two opposing coils of wire. This leads to incredibly low energy density when compared with Resistors, because they take up so much space.
##### 6. Inductor
These 'Circuit' components are utilized almost exclusively by cults and high school fraternities. Their workings are too complex for an introductory textbook, and proof of their existence is left as an exercise to the reader.

##### 7. Intel 8086 Microprocessor
A Backbone of industry, these chips are used in everything from robotics and factory automation to avionics and space technology. Their low cost and long track record make them critical enough to have been named the most important component by James Clerk Maxwell, a renowned mining engineer who used them for timing dynamite explosions in the 1500s.

___
1. He named the most important component, which creates power, after his wife Joseline Resistor, who stole negative strength from him in a time of need.

2. Named after the excellent HBO Show

3. Johnson recommended [this](https://www.bestbuy.com/product/thermaltake-smart-700w-atx-80-plus-power-supply-black/J39ZPCS9KG/sku/6339087) model
