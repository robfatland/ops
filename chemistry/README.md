
## A couple of chemistry problems


Suppose we have to start doing chemistry problems and we are presented with: 


26. How many ml of 0.25M KMnO4 are needed to deliver 0.00450 moles of KMnO4 during a chemical reaction? 


27. Suppose you needed to prepare a 100ml solution of 1.05M NaOH using 1.5M NaOH, distilled water, and a 100ml 
graduated cylinder. How would you do this?


***Before I begin working on this let me remark that I write using both markdown and LaTeX. Markdown afaik does not
support subscript / superscript; so I use LaTeX. Therefore C with a subscript of 12 could be written C_{12} and H 
with a superscript + might be written H^+ or H^{+}. Also a number written as 6e23 is read as 'six times ten
raised to the 23rd power'. That's how to translate some of my notation; and this issue will go away when
we add binder to the situation.***


### Define four ideas


A couple of observations to begin with: We need a good working definition of both **moles** and **molarity**. We also need
a good agreement on how we derive the **mass** of an atom or molecule. And we need to know why they stipulated a 
**graduated cylinder**. So this is four questions that I will answer. After that I will come back to and re-state 
the problems where we will hope they will be more tractable. 


One mole of something is one Avogadro's number of it; which is approximately 6e23 particles. That is 6 times ten raised 
to the twenty-third power; which is rather a lot. More accurately 6.022 but I will just use 6. It is interesting to
consider how much space a mole of Honda civics would take up in a cubical box.


By the way in addition to massive particles we can also have a mole of 
massless particles. In particular -- pun intended -- a mole of photons (light particles) is called an Einstein of 
photons, still 6e23 of them.


While the question of mass does not really come into play in our two problems... or maybe just a little bit...
nevertheless I think it is worth connecting these moles (particle counts) to masses. So time out while we
do that.

#### The mass of a bunch of identical particles 

I will treat protons and neutrons as having 
mass 1 and electrons as being massless. These are approximations. Furthermore for a given atom (fixed number
of protons) there are variable numbers of neutrons possible. These variants are called isotopes. For example 
we hear plenty about C_{12} (Carbon-12 = 6 protons + 6 neutrons) but there is a surprisingly large amount of 
C_{13} in the world as well; and it is pretty stable. There is even C_{14} but this tends to fall apart after 
a thousand years or so; and that is physics not chemistry. Point is I'm going to just take the mass of Carbon 
to be 12, full stop. We see atomic masses on the periodic table with usually some extra digits. I'm just going 
to round to the nearest integer when it comes to that. If we start working with mass spectrometers 
--whatever those are--then we get to use the extra digits. 


Now what are these proton units? Answer: They are called atomic mass units; where one proton has a mass of 1. 
This unit (I find) is now indicated by the letter **u** as in '1 Hydrogen atoms has a mass of 1 u'. Originally 
these were called Daltons and my chemistry friends still say Daltons so I will too. Daltons = atomic mass 
units (Da = u).


Now we can connect moles and Daltons via kilograms. One Da is 1.66e-27kg, a familiar mass. One mole of Hydrogen 
weighs less than one mole of carbon because moles are 'number of particles'. So moles do not translate to 
kilograms until you say moles of *what*. A mole of Hydrogen atoms -- each one weighing one Dalton -- weighs
6e23 (particles per mole) times 1 (Daltons per particle) times 1e-27 (kilograms per Dalton) = 0.001 kg 
or informally we say that is one gram.


Remember the joke question 'What weighs more: A pound of feathers or a pound of bricks?' Well now you know
a different version that is sensible: 'What weighs more: A mole of table salt or a mole of water?'


So... that's why Avogadro's number was chosen to be that goofy number 6.022e23 by the way: So that "a mole 
of something equals its (Daltons) weight but in grams". Therefore: Every time we see a mole of something 
and it has a molecular formula we can tot up all the atoms in that formula by their mass in Daltons; then 
convert that to grams; and then loudly proclaim "this many grams of this stuff is one mole of it". For example 
in problem 26 we see KMnO_4 which is one Potassium (K) at 39 Da, one Manganese at 55 Da, and 4 Oxygen each at 16 Da 
for a total of 158 Da. So 158 grams of KMnO_4 is one mole of it. 

#### Onward to cylinders (graduated) and molarity (concentration!) 


Now I have answered two of the four questions: What is a mole and how do we deal with the masses of molecules. 


Next let's dispense with the graduated cylinder. These do not have a lot of spare capacity above the top
line so a 100ml graduated cyclinder can be taken to hold only 100ml of liquid, not more. Therefore any 
solution-building we do can't exceed 100ml in the "bucket" at any one time. Which reminds me of gallon 
puzzles so let me give you one of those to work out while I go make sure I have a good working definition
of *molarity*. 


Suppose you have two beakers that are not graduated. Let's say they were held back by Professor Erlenmeyer.
They just have one line on the neck with a label showing how much you have when you fill to the line. 
One holds precisely 900ml and the other holds 400ml. Using a spigot of water flowing into a sink in your
chemistry lab: How would you obtain 300ml of water?  Is there only one way?


### molarity


I saved this one for last as the most important and the most difficult to comprehend. Molarity is moles per liter.


#### molarity revisited


Ok maybe I should expand that out a little bit. What I mean by molarity...


Molarity is a measure of concentration. If you add salt and more salt and more salt to a glass of water
you are increasing the concentration -- the molar concentration -- or the molarity -- of the salt in the 
water. Of course as you add salt you could tip out some of the solution to keep the volume of the solution
constant. Since you are adding in pure salt and tipping out water-with-salt-dissolved the salt is winning
and the concentration of salt increases. Let's restate this idea of concentration using more words.
First take a deep breath; then read (aloud if possible) the following two paragraphs...


Moles of something (say methane) per liters of something else (say kerosene) is molar concentration, also
called molarity. We might say that moles of sodium hydroxide per liter of water is another measure of 
molarity. Moles per liter is abbreviated with a capital **M**. Sometimes 
molar concentration is abbreviated as **mol/L** or the more confusing **molL-1** which unpacks as 
moles = mol and liters = L and 'raised to the -1' means you put it in the denominator so you get moles 
divided by liters. So ten moles of some solute -- some *thing* -- in 20 liters of some solvent -- some 
*liquidy thing* -- would be 0.5 molar concentration or 0.5 moles per liter or 0.5mol/l or 0.5molL-1 or 0.5M.


What is the molarity of water dissolved in water? This is a ludicrous question but let's think about it.
We have one liter of water which is 10 x 10 x 10 centimeters. One cubic centimeter of water weighs one gram. 
One liter of water weighs 10 x 10 x 10 = 1000 grams. One molecule of water weighs 18 Daltons. One mole of 
water weighs 18 grams. So 1000 grams of water contains 1000 / 18 = 55.555 moles of water. Rounding up: 
Water is 56 moles per liter that we have dissolved "in itself". There's nothing wrong with this; but it is
a bit weird that the solute and the solvent are the same thing. Usually in chemistry class the solute is not
the solvent; so it would take a real smarty-pants to say 
'You know what? The concentration of water is 56 moles per liter!'
and then Professor Erlenmeyer says 'Sit ***down*** Ms Granger.'


### Problem 26 Solution


> 26. How many ml of 0.25M KMnO4 are needed to deliver 0.00450 moles of KMnO4 during a chemical reaction? 


Spoiler alert: This could be wrong... but there is a better than 50% chance that it is right, in my estimation.


Let's call the answer **X** milliliters and notice the difference between the answer they want (X in milliliters) 
and the definition of molarity (moles per liter) that we work with. This we can address with unitary analysis: Keeping 
all the units in play to make sure the answer we get is in the units we want. In particular we introduce the ratio
of liters to milliliters as (1 / 1000) (liters / milliliter). 


By the way: Since we are working with moles and volumes we never actually need to calculate the mass of the 
KMnO4 in grams; so we do not need Daltons or grams. This is a convenient aspect of working with moles like me. 


X (milliliters) x (1 liter / 1000 milliliters) x 0.25 (moles / liter) = 0.0045 moles


This in English is "X-many milliliters of concentration 0.25 moles per liter equals .0045 moles; and don't forget to convert
from liters to milliliters." Notice that the molarity **M** I have written as **moles / liter**. The word 'liter' in the denominator
cancels the word 'liter' in the numerator of the (1/1000) fraction. The 'milliliters' also cancel leaving just moles. That is:
On the left side the only units that don't cancel out are moles and that is also what we have on the right side. This means
that our units balance out. 


Now numerically: When you take everything but **X** over to the right side you get 0.0045 * 1000 / 0.25 which is 18.


***Answer: 18 milliliters***


### Problem 27 Solution


> 27. Suppose you needed to prepare a 100ml solution of 1.05M NaOH using 1.5M NaOH, distilled water, and a 100ml 
graduated cylinder. How would you do this? 


First we notice we are starting with a concentration of 1.5M NaOH and ending with a concentration of 1.05M. 
This is good news because it means we are simply going to dilute the original solution. How much of it do we 
pour into the graduated cyclinder before topping it off with distilled water? Let's call that amount **Y**. 


I'm going to place the **Y** ml of 1.5M NaOH on the left side of an equation and multiply by the molar 
concentration to arrive at a number of moles. On the right I also calculate how many moles we would have
of NaOH if we have a volume of 100 ml (I use 1/10 liter) and a molar concentration of 1.05 mol / liter: 


**Y** ml x (1/1000) (liters/ml) x 1.5 moles / liter = (1/10) liters x 1.05 (mol / liter)


Again we have the units canceling leaving moles = moles; so that's good. In fact it is essential. 
Then the numbers give us Y = 70 ml. 
This makes sense because we are going from a concentration of 1.5M to 1.05M which is a bit more than
two-thirds; and 70 is a bit more than 2/3 of 100, the volume of the graduated cylinder. 


***Answer: Pour 30 ml of distilled water in the cylinder and add 70 ml of 1.5M NaOH solution.***


I have no idea if the order is correct here; but I am reasoning as follows: It is difficult to 
stir the contents of a graduated cylinder; and the NaOH is probably denser than the distilled 
water based on the relative molecular weights. If I pour in the NaOH first and then add water
the NaOH will stay on the bottom and perhaps not mix very well. If I do it in the other order
maybe the NaOH will mix itself into the water as it sinks. That's really just a guess. 




