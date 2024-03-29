---
layout: page
title: Papers
nav: papers
---

# Selected papers

{% for p in site.data.papers %}{% if p.featured %}
{% include paper.html %}
{% endif %}{% endfor %}

# All other papers

{% for p in site.data.papers %}{% if p.featured %}{% else %}
{% include paper.html %}
{% endif %}{% endfor %}


{% comment %}

**T. Poisot**, T. Bell, E. Martinez, C. Gougat-Barbera & M.E. Hochberg (2012) Terminal investment induced by a bacteriophage in a rhizosphere bacterium. *F1000 Research*. [online](http://f1000research.com/articles/1-21/v2).  <i class="fa fa-unlock-alt"></i>

**T. Poisot**, E. Canard, N. Mouquet & M.E. Hochberg (2012) A comparative study of ecological specialization estimators. *Methods in Ecology & Evolution*, 3 (3) 537-544. [pdf]({{ site.url }}/reprints/poisot_methodsecolevol_pdi.pdf), [R package](https://r-forge.r-project.org/R/?group_id=593).

**T. Poisot** (2012) L'ABC de la spécialisation: apparition, biodiversité, conservation. *Le Prisme à Idées* 4, 49-52. Vulgarization paper in French for the special issue *From uncertainty to risk*. [pdf]( {{ site.url }}/reprints/poisot_prisme_abc.pdf).

P.&nbsp;Desjardins-Proulx, **T. Poisot**, & D. Gravel (2012). A simple algorithm to study phylogeographies & speciation patterns in space. *ArXiV*. [pdf]({{ site.url }}/reprints/phdp_arxiv_wagner.pdf). <i class="fa fa-unlock-alt"></i>

**T. Poisot**, P.H. Thrall, M.E. Hochberg (2012) Trophic network structure emerges through antagonistic coevolution in temporally varying environments. *Proceedings of the Royal Society B: Biological Sciences*, 279 (1712) 299–308. [pdf]({{ site.url }}/reprints/poisot_prslb_coevolution.pdf), [suppl. mat.]({{ site.url }}/reprints/PRSLB_2011_supplementary-material.pdf).

**T. Poisot**, J.D. Bever, A. Nemri, P.H. Thrall & M.E. Hochberg (2011) A Conceptual Framework for the Evolution of Ecological Specialization. *Ecology Letters* 14 (9) 841–851. [online](http://onlinelibrary.wiley.com/doi/10.1111/j.1461-0248.2011.01645.x/full). <i class="fa fa-unlock-alt"></i>

P.S. Jørgensen, V. Bonhomme, T.H.G. Ezard, R.A. Hayes, **T. Poisot**, R. Salguero-gomez, S. Vizzini, N. Zimmerman. (2011) A global network of next generation ecologists. *INTECOL Bulletin* 5 (2) 4-6. [pdf]({{ site.url }}/reprints/jorgensen_intecol_innge.pdf).

**T. Poisot** (2011) The digitize Package: Extracting Numerical Data from Scatterplots. *The R Journal* 3 (1) 25–26. [pdf]({{ site.url }}/reprints/poisot_rjournal_digitize.pdf), [R package](https://github.com/tpoisot/digitize). <i class="fa fa-unlock-alt"></i>

**T. Poisot**, Y. Desdevises (2010) Putative speciation events in *Lamellodiscus* (Monogenea: Diplectanidae) assessed by a morphometric approach. *Biological Journal of the Linnean Society* 99 (3) 559-569. [pdf]({{ site.url }}/reprints/poisot_bjls_morphometry.pdf), [data](http://figshare.com/articles/Morphometric_measurements_of_Lamellodiscus_haptoral_parts/97320).

A.&nbsp;Tessier, **T. Poisot**, Y. Desdevises & P. Romans (2010) Effects of recreational fishing of *Paracentrotus lividus* on populations of sea urchins in Mediterranean shallow water. *Life & Environment* 60 (4) 299-305. [pdf]({{ site.url }}/reprints/tessier_vm_urchins.pdf).

**T. Poisot**, A. Simková, P. Hyrsl & S. Morand (2009) Interactions between immunocompetence, somatic condition and parasitism in the chub *Leuciscus cephalus* in early spring. *Journal of Fish Biology* 75 (7) 1667-1682. [pdf]({{ site.url }}/reprints/poisot_jfishb_chub.pdf).
{% endcomment %}
