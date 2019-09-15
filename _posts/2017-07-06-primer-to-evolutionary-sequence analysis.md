---
layout: post
title: A Primer to Evolutionary Sequence Analysis
date:  2017-07-06 08:23:00
description: a multi-faceted subject within biology and bioinformatics
---

![Photo: [stefaanroelofs](https://pixabay.com/en/users/stefaanroelofs-1175041/)](https://cdn-images-1.medium.com/max/3840/1*lfDuXhg1WfDHOlAg7Fm06A.jpeg){:width="100%"}

Sequence analysis is a multi-faceted subject within biology and bioinformatics that revolves around a basic concept — the relatedness of all biological sequences.
>  This makes sense actually.

In every species in existence, at least ones that we know of, the population is very similar when looking at the entire species as whole. For example, all humans share 99.9% of the same genetic material, with only 0.01% variation between us on average. Rarely do we see drastic differences between us on an individual level (a person with twenty limbs and five heads isn’t common…) Something as improbable as this physiology likely requires way more than a variance of 0.01% of the genome, which drives my point home — that we are very similar to one another.

Taking it even further, and comparing species to species, say humans compared to chimpanzees, there are more differences than simply comparing human to human. But, if one looks down the list of features that define us as “human”, chimpanzees are very similar to us, (obviously because we are part of the same evolutionary family). But, going down the list — they are bipedal, hairy, intelligent, and make use of tools...ect. You get my point.

The same type of comparison occurs when we shrink down past the physiological similarities, and look the genetics of one species to another. Using the same example, of humans (Homo sapiens) and chimpanzees (Homo pan), the variation between the two species is around 99% instead of the 99.1% difference that occurs between humans. The question after all this is, how do we make those comparisons?

The answer is Sequence Analysis (*horn fanfare*), the analysis concerned with the smallest levels of differences measurable between species — the genetics. With those comparisons, scientists can gain a large degree of insight of where a species came from and how it may be related to another species.

### Basics of Sequence Analysis

![The sequences of different genes or proteins may be aligned side-by-side to measure their similarity. This alignment compares protein sequences containing. [WPP domains](http://www.wikiwand.com/en/WPP_domain).](https://cdn-images-1.medium.com/max/2000/1*nsdsHyYeiBCDuInKw2VbWg.png){:width="100%"}

There’s a few basic definitions I need to define before jumping into sequence analysis terms, so I’ll start here. So first off, we need some basic unit of measuring genetic information in order to make meaningful comparisons of genetics between two species or whatever we are comparing. That unit is in the form of a gene. A **gene** is simply defined as, “*a distinct sequence of nucleotides forming part of a chromosome, the order of which determines the order of monomers in a polypeptide or nucleic acid molecule which a cell (or virus) may synthesize*”. Caveats into what a gene is and isn’t is in four years of a biology undergraduate, so I’m not going to delve into here. So from the now defined unit of genetic information, or gene, we can take it a step further and make comparisons of genes between species.

The relatedness of biological sequences is measured by what’s called **similarity**, which is defined as, *resembling without being identical*. In a bioinformatics perspective, similarity tells us the degree to which two sequences vary, with a higher percentage indicating a high relatedness of the sequences, which demonstrates the concept of **homology**. Homology is defined as, *the state of having the same or similar relation, relative position, or structure*, and homology can further be subdivided into orthologs and paralogs.

### Orthologs & Paralogs

An **ortholog** is defined as homologous gene derived from a single ancestral gene in the last common ancestor of the given two species. Orthologous relationships are therefor the result of what is called vertical evolution, which makes sense when you look at the root word of ortholog. The prefix ortho- comes from Greek , means, “straight,” “upright,” “right,” or “correct”. So a gene *straight* from a common ancestor, to the current organism(s) gene is how a good way to think about an ortholog.

From the Greek prefix para-, which means “at or to one side of, beside, side by side” , a **paralog** is a homologous gene that evolved through duplication within the same or ancestral genome. Imagine, a gene in location A in an ancestor has a copy of itself to the side of location A in the current organism. Paralogs are interesting, at least in my opinion because there are large number of reasons why gene is duplicated, but the impact of duplication can have effects on the function of the gene. Because paralogous genes are related due to duplication events. Paralogous genes do not necessary have the same function.

Whether paralogous or orthologous, researchers use the aforementioned characteristics to group certain sequences and organisms together, forming **phylogenetic** relationships and defining the relatedness of all organisms in the process. These formed relationships can later be used to compute and or predict relationships of unknown species to species we know and understand.

### In Regard to Evolution

In background of analyzing genes from a last common ancestor, to forming basic genetic relationships between organisms, evolution hangs out in the background, reminding us all that speciation may and likely occur given time. Evolution is easy to remember — survival of the fittest is a popular phrase describing the process of a species surviving selection and being fit genetically and prepared to survive. It’s simply change over time due to selective (specific) pressures. Evolution makes sense when we look at the famous Finch example that Darwin himself observed on the Galapagos Islands.

![Darwin’s finches or Galapagos finches. Darwin, 1845. Photo: [John Gould](https://commons.wikimedia.org/wiki/John_Gould) (14.Sep.1804–3.Feb.1881)](https://cdn-images-1.medium.com/max/3496/0*op4iRhUTtq_eqjkr.jpg){:width="100%"}

Genes can start off as homologous, similar common ancestor and sequence, just possessing several variations between them. Over time, especially if the distinct genes are separated environmental, a build up of variations over many generations occurs. As each adds variation on top of variation, the sequence similarity begins to drop. Before long, and this takes a very long time, we have two distinct species, previously related organisms that over time, deviated so much from their common ancestor that they can no longer reproduce. This process is called **speciation**, or divergent evolution.

**Divergent evolution** is defined as, “*the accumulation of differences between groups which can lead to the formation of new species, usually a result of diffusion of the same species to different and isolated environments which blocks the gene flow among the distinct populations allowing differentiated fixation of characteristics through genetic drift and natural selection.*”. From Darwin’s Finch example, every Finch looked very similar, but varied in the beak and other phenotypic traits. The isolation of each to it’s own area in the environment or niche lead to the speciation of distinct finches incapable of reproducing.
>  But what happens two separate species look similar but are in fact not closely related at all?

The question I ask above seems weird, but it actually occurs more than one would think. Take for instance the dolphin, shark and ichthyosaur. All three are large sea predators with fins, but all arise from three different ancestors — fish, land reptile, and land mammal respectively.

![Photo: [Claudia14](https://pixabay.com/en/users/Claudia14-80737/)](https://cdn-images-1.medium.com/max/3840/1*or8UCf_yBnhhSNYo7Y7jNQ.jpeg){:width="100%"}

Because of this difference of ancestral origin, the identity of these sequences is likely low. But these organisms look similar due to a process called convergent evolution. These organisms were at one point under functional selection during the course of their evolutions, possibly the environment required their ancestors to have the ability to swim or live in an aquatic environment, and they therefor adapted to survive the environment. Because of the functional role of these sequences are similar, they are called **analogues**.
>  There are always exceptions, and evolution is no different

All evolutionary pathways mentioned up until now have been vertical in nature, coming from ancestors or previous generations and the result is a modern day organism with traits of those ancestors. But there is an exception. Seriously, in biology, there is always an exception to something, and evolution is no different.

### Horizontal Gene Transfer

The exception to vertical evolution is known as Horizontal Gene Transfer (HGT). This method of genetic variation is characteristic in that organisms can also obtain genes from other species, genera, or even taxa. We see this in antibiotic resistant bacterium.

![Scanning electron micrograph of a human neutrophil ingesting MRSA National Institute of Allergy and Infectious Diseases (NIAID)](https://cdn-images-1.medium.com/max/5002/1*MuBCnEtf9eIvZXI8lkEJAA.jpeg){:width="100%"}

Staphylococcus is not the only example of HGT. Cases of *E. Coli* contamination of other organisms, has lead to nationwide recalls of various products, ranging from alfalfa sprouts and beef products, and resulted deaths due to infections — all due to the rapid evolution of organisms by way of HGT.

In closing out this introduction, sequence analysis is a multi-faceted subject within bioinformatics that revolves around the analysis of the relationship between all biological sequences. This subject relies heavily on evolutionary principles discussed above, utilizing these concepts to later compute and or predict relationships between as of yet unidentified organisms and species well-studied. Evolution is constantly occurring, horizontally and vertically, and it is the goal of sequence analysis to know where those occurred, and what changes those evolutionary events may lead.
