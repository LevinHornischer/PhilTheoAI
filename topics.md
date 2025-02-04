# Essay topics for Philosophy and Theory of AI

[Click here to get back to the course webpage](README.md).


Here I collect some possible topics. This is still in progress: I might add more topics and update the present ones.

## Comments

Just to be sure, the suggested topics are meant as first ideas. It is part of the task of writing an essay to turn an interesting aspect of the suggested topic into a precise research question and collect the relevant literature on it. Please take a look at the grading criteria mentioned in the file [`formalities.pdf`](formalities.pdf) to get a clear idea of what a good essay is expected to look like. 

Overall, the topics aim for a fruitful interaction between philosophy and AI: use philosophical theory to better understand AI models, and use AI models to concretely implement philosophical theories and thus empirically test them.

## Topics

* We discussed the question of holistic vs elementwise representation in the Phil Science section (Freiesleben, König, et al. 2022 "Scientific Inference With Interpretable Machine Learning"). A closely related distinction - reductionism vs holism - is discussed by Abramsky (2022,  "Nothing will come from everything"), specifically mentioning the case of AI on page 544. In light of these ideas, discuss to what extent a holistic representation of neural network behavior is compatible with a compositional approach to interpretable machine learning. (You might also refer to a classic of modern philosophy, Quine's 'Two Dogmas of Empiricism', as a critique of a too reductionist approach.)

* In Beigang (2023), counterfactual fairness of a prediction model was formalized using the counterfactual provided by causal models. Could it be formulated also using the counterfactuals from philosophy (the Lewis-Stalnaker counterfactual) or from explainable AI (see Wachter 2018 "Counterfactual explanations without opening the black box")? For this, one could explore the variation semantics framework of Hudetz and Crawford (2022, "Variation semantics: when counterfactuals in explanations of algorithmic decisions are true").

* In classical philosophy of AI (from the 1980s and 1990s), Gödel's Incompleteness Theorem played a crucial role for arguing for impossibilities for (symbolic) AI. (See [here](https://plato.stanford.edu/entries/artificial-intelligence/#GodeArguAgaiStroAI) for a brief overview.) Discuss and compare this to modern impossiblity result for machine learning like that of Colbrook et al. (2022, "The difficulty of computing stable and accurate neural networks")?

* In an ideal case of interpretable AI, one can show how a neural network - that was trained to predict a real-world phenomenon - has learned a useful representation of this phenomenon from which it derives its predictions. Discuss how achievable this ideal case is. Specifically, does it even make sense to say that a neural network has ' representational capacities that are akin to mental representations' (Freiesleben & Grote 2023, footnote 4)? (For a quick overview of `representation' in AI, see [here](https://www.aiglossary.co.uk/index/representation) and also see the reading Millière & Buckner 2024 part 2, especially section 2.4.)

* One way to state the interpretability problem of neural networks (that I find particularly useful) is in terms of micro-level and macro-level. We completely understand neural networks at the micro-level: how they propagate the activation of the input neurons to the output neurons and how they update their weights during learning. The problem is understanding them at the macro-level: to explain in human-understandable terms this process that goes on at the micro-level. An analogy is provided by thermodynamics: we have a complete understanding of the billions of gas particles in a box (how their position and momentum changes over time), and thermodynamics also provides an understanding of this micro-level process in the macro-level terms of temperature and pressure. What can be said about this problem of relating the micro-level to the macro-level from a general philosophical theory of explanatory levels as, e.g., presented in this recent [book](https://fdslive.oup.com/www.oup.com/academic/pdf/openaccess/9780192862945.pdf) and, in particular, in the first paper in there by List (which is also [here](https://philarchive.org/archive/LISLOD))?  
 
