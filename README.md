squarelife
==========


###############################
!!! readme in progress !!!
###############################


Genes:

Every object (which is an animal in this case) has it's own genetics. Currently 
there are only a few 'genes'. They are responsible for the phenotype of each
individual. If the animals mate, the genes are mixed up pretty randomly and new
genotypes (and therefore sometimes new phenotypes) occur. Here a short example 
for a mating process and the resulting animal:


Parent genetics:

A:              B:
AbCdeFgH        abCDefGH
aBCdEFGh        ABcDeFgH

Every letter stands for a 'gene'. Uppercase letters are dominant and lowercase
are recessive. In my simulation, dominant genes are the ones that are expressed.
For example: Aa, aA and AA will behave the same, aa will be weaker or ill.

The resulting animal in this case could look like this:

AbCdeFgH
ABcDeFgH

In this case, and for the sake of this example, I just used the upper line from
animal A and the lower line from animal B. For simplicity reasons I decided for
myself, that lines for themself cannot be splitted.


Phenotypes:

In the section above you saw that we have genes. But how do they 'work' in this 
simulation?

The simulation is _very_ simple, so please don't judge me for anything incorrect
or stupid, but basically animals with dominant genes have a better chance to
survive. Gene 'A' for example is the gene for proper leg development. If the
genotype is 'aa', the animal will be weaker and slower. Same thing with the
other letters.

A:  leg development (aa means very slow)
B:  eye development (bb means basically blind)
C:  colour (cc is white, Cc is green)
D:  ...
E:  immune system (ee is very fragile)
F:  fertility (ff is infertile)
...



Natural Selection:


Well, there is no natural selection. BUT, you can trigger events like hunger,
predators, fires, food shortage. If you trigger the events, you can see which
of your animals can survive.
