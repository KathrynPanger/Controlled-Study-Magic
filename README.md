# Controlled-Study-Magic

<h2>Falsifying Magic: A controlled study of the effect of magic spells on randomly generated integers. </h2>
Many people believe that magic is real, and that it can influence the world to such a degree that a scientific test would demonstrate this. I designed and implemented such a study. Note that this same study can be used to test the efficacy of prayer.

<h3>Methods</h3>
This simple program generates two lists of random numbers, one is supposedly affected by "magic" and one which is not. Using simple linear regression I test whether the so-called magician can use their magic to enchant the computer such that it will generate the second list under the influence of this magic, injecting bias into the generation of the second list.
<br>
<br>
Independent Variable: "Enchanted." This is a dummy variable indicating whether a magic spell was cast upon the computer before the computation of the random list (experimental group, coded 1) or if it was not (control group, 0).
<br>
<br>
<p>Dependent Variable: "Value." These are the values for the randomly generated numbers in both lists.</p>
<br>
<p>This process of generating a regression model is reproducable. Because the significance of the effect of the magic spell is tested at a 95% confidence level (p<0.05), results should be reproduced several times in order to determine whether the initial results fall into the 5% probability of a false positive or false negative result.</p>


<h2>Limitations and Opportunities for Increased Rigor</h2>
* Rigor could be increased by changing the control group to a "placebo" tradition, whereby the researcher engages in  what they consider a non-magical ritual practiced before this set of numbers is generated, like reciting the pledge of allegence, for example.<br>  
* Rigor could be increased by generating multiple lists for both the control and the experimental condition, rather than simply casting the spell once and assuming it was done correctly.<br>  
* Rigor could be increased by introducing a third categorical variable into the regression model accounting for the denomiation of the caster, and thus the type of spell which was cast.<br>  
* This study is limited in that it cannot test for the possibility that magic is inherently untestable and unfalsifiable, a claim that many magicians make. This of course would mean that any study is doomed to fail, and also that magic spells have no measurable material effect on the physical world. This, I believe, would mean that magic spells cannot affect our lives in any way and are therefore useless, but that is a matter of philosophical debate.</p>

<h2>Critiques and Rebutals</h2>
<p>Critique: "Number generation is only pseudo-random, and not truely random, so the results are invalidated." 
<p>Rebuttal: If this is true, then it is equally true for both the control group and the experimental group, so it would not introduce bias into the final results.
<p>
<p>Critique: "Magic only works on (x) and does not work on randomly generated numbers."
<p>Rebuttal: This claim is an example of the heuristic of confirmation bias (evidence only counts when it verifies my beliefs) and the fallacy of shifting the goalposts (post-hoc changing the requirements for evidence after the fact in order to invalidate any study with unwanted results).</p>
<p></p>
<p></p>
<h2>Results</h2>
Results for this study are pending implimentation by someone who believes in magic (i.e. not me) and who is fully qualified to cast such a spell. If you feel that you are qualified, feel free to try the study for yourself!</p>
