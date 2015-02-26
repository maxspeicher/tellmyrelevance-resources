TellMyRelevance! (TMR)
======================

## Abstract

It is crucial for the success of a search-driven web application to answer users' queries in the best possible way. A common approach is to use click models for guessing the relevance of search results. However, these models are imprecise and waive valuable information one can gain from non-click user interactions. We introduce *TellMyRelevance!*--a novel automatic end-to-end pipeline for tracking cursor interactions at the client, analyzing these and learning according relevance models. Yet, the models depend on the layout of the search results page involved, which makes them difficult to evaluate and compare. Thus, we use a *Random Mouse Cursor* as an extension to our pipeline for generating layout-dependent baselines. Based on these, we can perform evaluations of real-world relevance models. A large-scale interaction log analysis showed that we can learn relevance models whose predictions compare favorably to predictions of an existing state-of-the-art click model.

## Publication(s)

- Maximilian Speicher, Andreas Both, and Martin Gaedke (2013). "TellMyRelevance! Predicting the Relevance of Web Search Results from Cursor Interactions". In: *Proc. CIKM*. http://dl.acm.org/citation.cfm?id=2505703

## Resources

This repository contains:

- in the folder **data** (to be used with [WEKA](http://www.cs.waikato.ac.nz/ml/weka/)):
  - The relevance models and corresponding training data for each of the three datasets; produced with the default version of TMR (full feature set).
  - The relevance models and corresponding training data for each of the three datasets; produced with the clicks-only version of TMR.
  - The baseline model and corresponding training data; generated using the Random Mouse Cursor extension.

## License

[![Creative Commons License](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).
