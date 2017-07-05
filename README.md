**The original repository is accessible [here](https://github.com/Roy-lab/merlin-p)**

Condition specific inferred networks:
-------------------------------------
*Heat stress:*

* heat_All.txt (All inferred edges)
* heat_3more.txt (Edges with frequency of 3 or more)

*Osmotic stress:*

* osmotic_All.txt (*All inferred edges*)
* osmotic_3more.txt (*Edges with frequency of 3 or more*)

Skeleton network:
-----------------
* merlin_M_K_C_All.txt (*All inferred edges*)
* merlin_M_K_C_30K.txt (*Top 30K inferred edges*)


All predictions in yeast:
-------------------------

* yeast_networks/inferred/ (*All inferred networks, from 8 methods and 3 expression datasets*)
* yeast_networks/gold/ (*The gold standard networks (filtered to include only genes from specific datasets)*)
* yeast_networks/priors/ (*The prior networks*)

All predictions in human LCL:
-----------------------------
* LCL_networks/inferred	(*Inferred networks using PGG, on 4 expression datasets and 3 prior setting (no prior, beta=3, and beta=4)*)
* LCL_networks/gold (*The two gold standards*)
* LCL_networks/prior (*The prior network*)

Description of the datasets:
----------------------------

The full description of the datasets can be found in the original paper:
> **A prior-based integrative framework for functional transcriptional regulatory network inference**
>
> Siahpirani and Roy, Nucl Acids Res, 2016.
>
> https://academic.oup.com/nar/article/doi/10.1093/nar/gkw963/2333925/A-prior-based-integrative-framework-for-functional

**Yeast datasets:**

*Prior networks:*

* Motif prior: 
    * Gordân et al. Genome Biol. 2011
    * YeTFaSCo (de Boer and Hughes Nucleic Acids Res. 2012)
* ChIP network: 
    * Harbison et al. Nature 2004
    * Venters et al. Mol. Cell. 2011*
* KO network: 
    * Hu et al. Nat. Genet. 2007
    * Reimand et al. Nucleic Acids Res. 2010*

*Expression datasets:* 

* Natural variation: 
    * Brem and Kruglyak Proc. Natl. Acad. Sci. U.S.A. 2005
    * Smith and Kruglyak PLoS Biol. 2008
    * Zhu et al. PLoS Biol. 2012
* Knockout:
    * Chua et al. Proc. Natl. Acad. Sci. U.S.A. 2006
    * Hu et al. Nat. Genet. 2007
* Stress response:
    * Gasch et al. Mol. Biol. Cell. 2000

**Human datasets:**

*Prior networks:*

* Motif prior: Cis-BP (Weirauch et al. Cell 2014)

*Expression datasets:*

* Natural variation:
    * Geuvadis (Lappalainen et al. Nature 2013
    * Niu et al. Genome Res. 2010
* Stress response:
    * Benton et al. BMC Genomics. 2011
    * Junaid et al. Biochem. Biophys. Res. Commun. 2011
    * Forrester et al. PLoS One. 2012
    * Luca et al. PLoS One. 2013
    * Su et al. PLoS Genet. 2015
    * Glover et al. PLoS One. 2015
    * GSE22639 and GSE51454
