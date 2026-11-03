---
layout: page
---

A central goal of evolutionary biology is to understand the diversity of organismal adaptation. Achieving this, however, is challenging: most evolution has occurred in the past, and ongoing evolution often takes longer than a human lifetime to observe.

Therefore, answers to fundamental questions remain elusive. Why do some organisms have sex? Why do some outcross and others self-fertilise? Why are some
haploid and others diploid? Does adaptation rely on pre-existing
variation or new mutations? Why is fitness variation maintained? Why does genetic variation vary between genomes and species?

Fortunately, we have tools to overcome this: a century of mathematical models of evolution, allied with new genomic datasets and experimental systems to manipulate and understand evolution. 

I use these tools to address a variety of questions about evolutionary adaptation, such as:

-----

### Why is there genetic variation?

#### Fitness variation

Many organisms harbour extensive genetic variation for fitness, but the reasons are unclear (e.g. Charlesworth 2015, *PNAS*). One hypothesis is that recurrent deleterious mutations generate fitness variation. Another possibility is that fitness variation is actively maintained under balancing selection -- for example, due to heterozygote advantage, negative frequency-dependent selection, or various trade-offs between selective contexts. We have recently reviewed this century-old body of theory ([Ruzicka et al. 2025, Biological Reviews](/assets/Ruzickaetal2025BiolRev.pdf)).

![Pic](/assets/Ruzickaetal2025Fig1.pdf)

One trade-off that can potentially generate balancing selection and maintain fitness variation is sexually antagonistic selection, in which selection is opposing between females and males. In *Drosophila melanogaster*, we performed the first genome-wide association study of sexually antagonistic genetic variation ([Ruzicka et al.
2019, PLOS Biology](/assets/Ruzickaetal2019PlosBiol.pdf)). We then linked GWAS signals of sexually antagonistic variation with molecular polymorphism data from worldwide populations of *D. melanogaster* and its sister species *D. simulans*. We showed that sexually antagonistic selection indeed contributes to the long-term maintenance of fitness variation.

![Pic](/assets/Ruzickaetal2019Fig4.pdf)

Later, we also identified signals of sexually antagonistic variation in humans ([Ruzicka et
al. 2022, PLOS Biology](/assets/Ruzickaetal2022PlosBiol.pdf)). There, the association between signals of sexually antagonistic variation and long-term maintenance of polymorphism were much weaker, possibly due to differences in the effectiveness of selection between *Drosophila* and humans.

#### Trait variation

Sex differences in lifespan are a prominent form of within-species diversity. One hypothesis for sex differences in lifespan is that recessive deleterious mutations are expressed on the X chromosome in males, but not in females, leading to shorter lifespan in males. We modelled this "unguarded X effect" and used empirical estimates to parameterise our model. We found that the contribution of the unguarded X effect should typically be smaller than existing estimates of sexual dimorphism ([Connallon et al.
2022, Evolution Letters](/assets/Connallonetal2022EvolLett.pdf)).

![Pic](/assets/Connallonetal2022Fig2.pdf)

#### Molecular variation

The causes of molecular variation -- both within genomes and between species -- are incompletely understood. So much so that the weak relationship between census population sizes and molecular genetic diversity of species has been termed "Lewontin's paradox" (e.g. Buffalo 2021, *eLife*). One aspect of between-species molecular variation is the difference between X chromosomes and autosomes. In *D. melanogaster*, we have shown that purifying selection is typically stronger on the X chromosome than autosomes, as reflected in elevated additive genetic variance for male fitness, and lower levels of functional polymorphism, on the X relative to autosomes ([Ruzicka et al.
2021, Genetics](/assets/Ruzickaetal2021Genetics.pdf)), which is consistent with predictions based on the partial recessivity of deleterious mutations.

![Pic](/assets/Ruzickaetal2021Fig5.pdf)

### What is the genetic basis of adaptation? 
 
Much genetic variation in natural populations is neutral or nearly-neutral, yet questions about adaptation require us to identify and characterise *adaptive* variation. 
 
#### Adaptive trade-offs

Genetic variants that are adaptive in one sex but detrimental in the other -- sexually antagonistic variants -- are a form of adaptive variation. A major obstacle in identifying such variation is that males and females are part of the same population, which restricts signals of genetic divergence between them ([Ruzicka et al.
2020, Evolution Letters](/assets/Ruzickaetal2020EvolLett.pdf)). In *Drosophila melanogaster*, we overcame this obstacle by measuring sex-specific fitness among 200 "hemiclone" lines. Combining these data with whole-genome sequences, we identified genome-wide sexually antagonistic variants for the first time ([Ruzicka et al.
2019, PLOS Biology](/assets/Ruzickaetal2019PlosBiol.pdf)).  

![Pic](/assets/Ruzickaetal2019Fig1.pdf)

In humans, experimental manipulation is not feasible, so that identifying sexually antagonistic variants is more challenging. To remedy this -- and instead of using single-locus approaches that are invariably under-powered ([Ruzicka et al.
2020, Evolution Letters](/assets/Ruzickaetal2020EvolLett.pdf)) -- we developed new polygenic tests of sexually antagonistic selection. We first developed new theory for detecting allele frequency differences between females and males. Compared to our null models, we uncovered clear polygenic signals of sexually antagonistic selection in a quarter-million humans from the UK Biobank ([Ruzicka et
al. 2022, PLOS Biology](/assets/Ruzickaetal2022PlosBiol.pdf)). We also found such signals in genomic datasets of flycatcher and pipefish ([Ruzicka et al.
2020, Evolution Letters](/assets/Ruzickaetal2020EvolLett.pdf)). 

![Pic](/assets/Ruzickaetal2022Fig1.pdf)
![Pic](/assets/Ruzickaetal2022Fig2.pdf)

Our new test further allowed us to examine a long-standing hypothesis that sexually antagonistic variation is enriched on the X chromosome ([Ruzicka
and Connallon 2020, Proc B](/assets/RuzickaConnallon2020ProcB.pdf), [Ruzicka
and Connallon 2022, Proc B](/assets/RuzickaConnallon2022ProcB.pdf)). In contrast to this long-standing hypothesis, however, we detected no such enrichment on the X chromosome.

![Pic](/assets/RuzickaConnallon2020Fig1.pdf)
![Pic](/assets/RuzickaConnallon2022Fig2.pdf)

We have also asked whether alleles subject to trade-offs (such as sexually antagonistic variants) should contribute to adaptive divergence between species ([Connallon et al. 2025, Evolution](/assets/Connallonetal2025Evolution.pdf)). We have shown that -- although trade-offs should be common among new and segregating mutations -- they should contribute much less to adaptive divergence. 

![Pic](/assets/Connallonetal2025Fig2.pdf)

#### Genetic dominance 

Genetic dominance influences adaptive responses to selection, and major evolutionary transitions like sex, ploidy and mating systems. 

![Pic](/assets/DominanceFig.pdf)

Yet, it is unclear whether adaptive mutations are dominant or recessive. On one hand, adaptation is nearly always faster on sex chromosomes than autosomes, implying that adaptive mutations are recessive (because recessive mutations should respond more readily to selection when X-linked than autosomal). 

![Pic](/assets/McDonoughetal2024Fig1.pdf)

On the other hand, long-standing theories of dominance predict that adaptive mutations should be dominant. 

![Pic](/assets/McDonoughetal2024Fig2.pdf)

As a first step toward resolving this puzzle, we developed a new theory of sex chromosome evolution that is compatible with theories of dominance, provided such mutations have sufficiently large effects ([McDonough et al.
2024, PNAS](/assets/McDonoughetal2024PNAS.pdf)). Our theory, which is based on Fisher’s geometric model, proposes that large-effect mutations are often overdominant on an autosome -- and therefore selected against in homozygotes -- but have a net positive effect on the X chromosome, which favours their fixation. In recent work, we used the ranking of mutations by the magnitudes of their effects on proteins to test the theoretical prediction that faster-X
adaptive divergence becomes more likely for large-effect mutations ([Ruzicka & Vicoso 2026, GBE](/assets/RuzickaVicoso2026GBE.pdf)). 

![Pic](/assets/RuzickaVicoso2026Fig4.pdf)

  

