# Zprime_to_tT

Z' search with top and heavy top (adopted from https://github.com/osherson/Zprime_to_tT).


## Files starting with TT_ pertain to the TTBAR estimate

* TemplateMaker makes the theta feed for the tamplate morphing
* TemplateMorpher does the obivous: morphs the templates. (need to be run in a theta repository containing the output of the above)
* TemplateChecker checks the results of the above in the ttbar region
* TemplateCheckerHeavy checks how the new shapes perform in the heavy(er) top region.

## NT_ for non-top
* One file: Takes the muon/elec data and some MC and computes the NumPass/NumFail linear fits which should apply to the signal region. 

## SR for signal region plotters
