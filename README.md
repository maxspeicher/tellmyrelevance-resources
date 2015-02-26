TellMyRelevance! (TMR)
======================

## Abstract

It is crucial for the success of a search-driven web application to answer users' queries in the best possible way. A common approach is to use click models for guessing the relevance of search results. However, these models are imprecise and waive valuable information one can gain from non-click user interactions. We introduce *TellMyRelevance! (TMR)*--a novel automatic end-to-end pipeline for tracking cursor interactions at the client, analyzing these and learning according relevance models. A large-scale interaction log analysis showed that we can learn relevance models whose predictions compare favorably to predictions of an existing state-of-the-art click model (Dynamic Bayesian Network click model, DBN) as well as a click-only version of TMR.

## Publication(s)

- Maximilian Speicher, Andreas Both, and Martin Gaedke (2013). "TellMyRelevance! Predicting the Relevance of Web Search Results from Cursor Interactions". In: *Proc. CIKM*. http://dl.acm.org/citation.cfm?id=2505703

## Resources

This repository contains:

- in the folder **datasets** (to be used with [WEKA](http://www.cs.waikato.ac.nz/ml/weka/)):
  - The test/training data for each of the three datasets; produced with the default version of TMR (full feature set).
  - The test/training data for each of the three datasets; produced with the click-only version of TMR.
- in the folder **models** (to be used with [WEKA](http://www.cs.waikato.ac.nz/ml/weka/)):
  - The relevance models for each of the three datasets; produced with the default version of TMR (full feature set).
  - The relevance models for each of the three datasets; produced with the clicks-only version of TMR.
- in the folder **precision-recall-data**:
  - All data necessary to reproduce Precision-Recall and ROC analyses for all datasets and compared approaches (TMR, DBN, click-only TMR).

## References

1. Chapelle, Olivier, and Ya Zhang. "A dynamic bayesian network click model for web search ranking." In *Proceedings of the 18th International Conference on World Wide Web (WWW '09)*. ACM, 2009.

## License

[![Creative Commons License](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).
