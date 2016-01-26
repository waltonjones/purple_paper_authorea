The relationship of a miRNA to its targets is theoretically sequence-specific. 
Here, we are using miRNA over-expression as a tool, not to explore the biology of the miRNAs themselves, but to direct a follow-up screen using gene-specific RNAi. 
We thus compiled a list of potential _miR-iab-4_ targets using [TargetScan](http://www.targetscan.org/fly_12/) \cite{Ruby_2007}. 
Using the FlyAtlas tissue-specific expression data \cite{Chintapalli_2007} available on [FlyBase](http://flybase.org), we limited the list of potential *miR-iab-4* targets to those expressed in the adult fat body. 
In a small secondary screen using gene-specific RNAi (See Table S2 for a list of screened genes), we identified _purple_ (*pr*) as a novel regulator of feeding behavior in *Drosophila*. 
When combined with the fat body driver r4-GAL4, we found two *pr*-IR (inverted repeat) lines, each targeting different parts of the *pr* mRNA, both significantly enhance adult *ad libitum* feeding in the CAFE assay (UAS-pr-IR1, Fig. 2A; UAS-pr-IR2, Fig. 2B). 
Similarly, FB-Gal4 \cite{Gr_nke_2003}, another fat body-specific GAL4 line, also enhances adult feeding when combined with UAS-pr-IR1 (Fig. 2C).

*Purple*, like many *Drosophila* genes, is named for one of its most recognizable mutant phenotypes---purplish eyes. 
Indeed, according to FlyAtlas, the eye is the site of highest *pr* expression. 
There, *pr*, which encodes the enzyme 6-pyruvoyltetrahydropterin synthase (PTPS), is critical for the synthesis of the drosopterin class of light-screening eye pigments \cite{Kim_2013}. 
Using the eye-specific GMR-GAL4 to knock-down *pr*, we found that the *pr* expressed in the eye does not seem to be involved in the regulation of adult feeding behavior (Fig. 2D).

Although r4-GAL4 and FB-GAL4 are expressed in the adult fat body, they are also expressed in the larval fat body making it possible that the effect of *pr* on adult feeding we are observing could originate during development. 
Thus, we used the ubiquitously expressed temperature-sensitive tub-GAL80<sup>ts</sup>, which blocks the activity of GAL4 except at elevated temperatures, to limit our knock-down of *pr* to the adult fat body. 
At the permissive temperature (18ºC), the feeding of *tub-GAL80<sup>ts</sup>;r4-GAL4;UAS-pr-IR1* is indistinguishable from the appropriate heterozygous controls. 
When flies of the same genotype are shifted to the restrictive temperature (30ºC) post-eclosion, the GAL80 is inactivated allowing knock-down of *pr*. 
These flies eat significantly more than heterozygous controls (Fig. 2E). 
While there is a clear effect of ambient temperature on feeding amount, this result suggests *pr* does play a role in the adult fat body influencing feeding behavior.

To confirm this effect of *pr* on feeding behavior, we measured the feeding of two hypomorphic *pr* mutant strains, *pr<sup>1</sup>* and *pr<sup>G3141</sup>* and found both eat more than *w<sup>1118</sup>* and Canton-S "wild type" controls (Fig. 2F). 
We next asked whether the fat body-specific over-expression of *pr* can rescue the hyperphagic phenotype of the *pr<sup>G3141</sup>* mutant. 
In the absence of the *pr<sup>G3141</sup>* mutation, transgenic over-expression of *pr* in the fat body produces a small but significant reduction in feeding compared to heterozygous controls (Fig. 2G, above). 
In the presence of the *pr<sup>G3141</sup>* mutation, *pr* over-expression produces a much more robust reduction in feeding compared to the appropriate controls (Fig. 2G, below). 
These data confirm that fat body expression of *pr* is required for normal control of feeding behavior. 
