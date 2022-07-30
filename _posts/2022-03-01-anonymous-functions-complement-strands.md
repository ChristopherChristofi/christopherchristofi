---
category: Programming
topic: Python Programming
title: Anonymous Functions to Generate Complement DNA Strands
---

Here focus is not necessarily in the biomechanics of reverse complementation, polymer planning and completion of the tertiary DNA structure. Instead, focus posits python described nucleobase pair switching via anonymous functions, in response to conditionality that follows restrictive complementarity rules derived from secondary DNA structures. By disengaging from 'if' conditioning, specific acting processes of pattern matching could be intuitively distributed in an object profile via appointed properties -- inherent to objects, and natural to dictionary data structures -- rather than comparative statements.
This also somewhat enables access to resultant functionality of predisposed conditions of distribute, akin to application interface requests.

It is, however, still effective to at least introduce the relative biochemical concepts that underly the logical implementation -- DNA is formed of two fascinated strands that both complement each other and run in opposing direction. To form and maintain the DNA structure and double helix shape, both strands must bond with one another at the level of nucleobases, forming base pairs; the complementarity of such bases for each opposing strand is: adenine to thymine, and cytosine to guanine. Finally, where the secondary structure is known for a single strand, a corresponding reverse complement strand can be predicted, therefore, together, due to complementarity, both strands are then suitable to form the tertiary structure of a DNA molecule -- double helix shape.

With regards to computational logic, object attributives holding base pair switching functionality is first configured on compilation. Such build-orientated class methods hold: in its first 'base' property, the relative 'to match' read identifier; then in its second property (or any), an informational note that describes the process; and finally, in the objects third property resides the callable anonymous function, where in this case returns the complement base. An example detailing the attributes of the global compilation process can be found here:

<br>


*Receives G (guanine) as input and returns complement C (cytosine)*

-*method formation: build[read input base] = main(description, function)*

***main.base_exchange("G", "Guanine to Cytosine", lambda: "C")***

<br>

___

| Properties | Description |
| ------ | :---: |
| *Property 1* | *Key identifier that is called upon read input or element validation via the data structure it is stored in, similar to a get request.* |
| *Property #* | *Accessible property that entails information or any other miscellaneous function via the data structure it is stored in.* |
| *Property 3* | *The anonymous function that exists in the data structure it is stored relevant to its key identifier: data structure [ property 1 ] = compiler ( property 3 functionality )* |

___

<br>

When the program is run, the base exchange method first compiles the conditional attributes for the reference *build* data structure, where our input base is an acting key referencing a corresponding anonymous function inherent to properties of the main class. The very implementation of such functional distillation over the input strand is handed to us by the complement transform method of the main class. outlined below:

<br>

*Matched callable reference of the build body returns the anon function output*

-*from complement transform method*

***build[base].function()***

<br>

Within its functional body stands the *build* data structure that forms a dictionary reference for read base switching -- returning its complement base when called via input and key reference. The procedural distribution of work produced by the complement transform method, and main body of the generate complement strand function, is a comprehensive linear stream.

In addition to other complementary functions used to complete the generating of the complement strand, such as: capitalisation, string/strand reversal, and base validation -- its current functional form accepts standard input (which can be further expanded).

Although the biological problem is not all that complex in terms of logic, an attempt at a functional procedural method was an entertaining exercise to play around with. The python script can be found on my GitHub [here](https://github.com/ChristopherChristofi/bioinformatic-toolplayground/blob/main/string_manipulations/complement_strand.py).
