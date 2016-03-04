## Secondary screen for fat body inhibitors of feeding
The relationship of a miRNA to its targets is sequence-specific.
Here, we are using miRNA over-expression as a tool, not to explore the biology of the miRNAs themselves, but to direct a follow-up screen using gene-specific RNAi.
We thus compiled a list of potential _miR-iab-4_ targets using the online prediction algorithm [TargetScan](http://www.targetscan.org/fly_12/) \cite{Ruby_2007}.
Using the FlyAtlas tissue-specific expression data \cite{Chintapalli_2007} available on [FlyBase](http://flybase.org), we limited this list of potential _miR-iab-4_ targets to those expressed in the adult fat body.
In a small secondary screen using gene-specific RNAi (See Table S2 for a list of screened genes), we identified _purple_ (_pr_) as a novel regulator of feeding behavior in _Drosophila_.
When combined with the fat body driver r4-GAL4, we found two _pr_-IR (inverted repeat) lines, each targeting different parts of the _pr_ mRNA, both enhance adult _ad libitum_ feeding in the CAFE assay (UAS-pr-IR1, Fig. 2A; UAS-pr-IR2, Fig. 2B).
Similarly, FB-Gal4 \cite{Gr_nke_2003}, another fat body-specific GAL4 line, also enhances adult feeding when combined with UAS-pr-IR1 (Fig. 2C).

The _purple_ gene got its name from one of its most recognizable mutant phenotypes—purplish eyes.
Indeed, according to FlyAtlas, the eye is the site of highest _pr_ expression.
There, _pr_, which encodes the enzyme 6-pyruvoyltetrahydropterin synthase (PTPS), is critical for the synthesis of the drosopterin class of light-screening eye pigments \cite{Kim_2013}.
Using the eye-specific GMR-GAL4 to knock-down _pr_, we found that the expression of _pr_ in the eye does not seem to alter feeding  (Fig. 2D).

Although r4-GAL4 and FB-GAL4 are highly expressed in the adult fat body, they are also expressed in the larval fat body making it possible the effect of _pr_ on adult feeding we are observing could originate during development.
Thus, we used the ubiquitously expressed temperature-sensitive tub-GAL80<sup>ts</sup>, which blocks the activity of GAL4 except at elevated temperatures, to limit our knock-down of _pr_ to the adult fat body.
At 18ºC, the feeding of _tub-GAL80<sup>ts</sup>;r4-GAL4;UAS-pr-IR1_ flies is indistinguishable from the appropriate heterozygous controls.
After shifting them to 30ºC post-eclosion so that GAL80 can no longer block the GAL4-mediated expression of _pr_-IR1, flies of the same genotype eat more than heterozygous controls (Fig. 2E).
While there is a clear effect of ambient temperature on feeding amount, this result suggests _pr_ in the adult fat body does influence feeding behavior.

To confirm this effect of _pr_ on feeding behavior, we measured the feeding of two hypomorphic _pr_ mutant strains (i.e., _pr<sup>1</sup>_ and _pr<sup>G3141</sup>_)and that found both eat more than _w<sup>1118</sup>_ and Canton-S "wild-type" controls (Fig. 2F).
We next asked whether fat body-specific over-expression of _pr_ can rescue the hyperphagic phenotype of the _pr<sup>G3141</sup>_ mutant.
In the absence of the _pr<sup>G3141</sup>_ mutation, transgenic over-expression of _pr_ in the fat body produces a small but significant reduction in feeding compared to heterozygous controls (Fig. 2G, above).
In the presence of the _pr<sup>G3141</sup>_ mutation, _pr_ over-expression produces a much more robust reduction in feeding compared to the appropriate controls (Fig. 2G, below).
These data confirm that normal feeding behavior requires the fat body expression of _pr_.
