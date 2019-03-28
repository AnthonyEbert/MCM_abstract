# MCM_abstract

Title: 
Approximate Bayesian computation to model passenger flow within airport terminals

Abstract:
Rapidly increasing numbers of air passengers have led to congestion within airport terminals. To help manage this congestion, we develop statistical tools for decision support. Existing decision support tools for passenger flows in airports do not allow parameters to be inferred systematically and do not account for parameter uncertainty. This is because the complexity of processes occurring within the terminal make the likelihood intractable, meaning that approximate Bayesian computation (ABC), which is based on a distance between data and model realisations, should be appropriate. However, standard queueing simulation techniques are computationally expensive which make ABC infeasible for such problems. A new queueing simulation algorithm called queue departure computation has made ABC feasible for such models. We repurpose maximum mean discrepancy, a distance on probability measures as a distance on functional data between observed passenger flow counts and model realisations. We demonstrate how it is used to infer parameters and provide tools for decision support with a case study of a delayed flight. Finally, we adapt curve registration techniques to the likelihood-free domain to further enhance our ABC distance. 

