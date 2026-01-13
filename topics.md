# Essay topics for Philosophy and Theory of AI

[Click here to get back to the course webpage](README.md).

Here I collect some possible topics. This is still in progress: I might add more topics and update the present ones.


## Comments

Please take a look at the file [`formalities.pdf`](formalities.pdf) for requirements on the essay (word limit, format, etc.), including the grading criteria to get a clear idea of what a good essay is expected to look like.  
 As also described there, the topics below are just meant as first ideas. It is part of your task of writing an essay to also cover the following. 

* Argue for the importance of the chosen topic and identify a clear research question within the topic. The research question should be wide enough to capture an important aspect of the topic, but narrow enough to be answered in an essay (though, more often a research question is too wide, rather than too narrow). Ideally, the research question poses a yes/no question. Locate your contribution within related work.
* Your answer to the research question should involve philosophical or mathematical theory that we covered in class or that is closely related to the course.
* You should also describe an experiment to empirically test your answer to the research question. The description should be detailed in enough for a programmer to code it (which neural network architecture, which hyperparameters, which training data and how to get them, etc.; cf. the ‘machine learning pipeline’).
* Ideally, you also implement (a toy-version of) your experiment and describe the empirical results. However, this is not necessary, since coding is not required for the course. If you do not implement your experiment, then describe which results you would expect (e.g., by referring to papers with similar experiments).


## Topics

* _Representation_: The question of representation in neural networks came up several times. In the Phil Science section, we discussed if a well-predicting neural network also is a scientific model of the target domain (Freiesleben, et al. 2022 "Scientific Inference With Interpretable Machine Learning"). In the Phil Language section (Millière & Buckner 2024 "A Philosophical Introduction to Language Models Part II"), we discussed if an LLM needs to have some representation of, e.g., linguistic features, and how one can test for them (probing, mechanistic interpretability, etc.). In particular, Harding (2023, "Operationalizing Representation in Natural Language Processing") provides a framework to evaluate claims of representation in LLMs.

   Discuss this suggestion both theoretically by relating to the philosophical literature on representation (e.g., [scientific representation](https://plato.stanford.edu/entries/scientific-representation/) and [mental representation](https://plato.stanford.edu/entries/mental-representation/) and [representation in Phil AI](https://www.aiglossary.co.uk/index/representation)) and empirically by considering one concrete and simple task to test these ideas in a neural network.


* _Algorithmic fairness_: In class, we saw the impossibility result concerning two plausible necessary requirements for a prediction machine to be fair. What are ways out of this impossibility? Is one of the two principles not plausible on second sight? Does the plausibility depend on the context? Does a proper formulation of fairness criteria require more than just statistical language (e.g., also causal language)? Compare your takes to the existing literature, and test your ideas on existing datasets: a typical one is the Adult data set (Ding et al. 2021 "Retiring Adult: New Datasets for Fair Machine Learning").

   Regarding the idea of using a richer language, you may consult, e.g., Beigang (2023) on using causal models to specify a counterfactual fairness condition. You may also reflect on formulating this with the counterfactuals from philosophy (the Lewis-Stalnaker counterfactual) or from explainable AI (see Wachter 2018 "Counterfactual explanations without opening the black box")? You could also explore the variation semantics framework of Hudetz and Crawford (2022, "Variation semantics: when counterfactuals in explanations of algorithmic decisions are true").


* _Impossibility_: In the lecture on computability theory, we saw classical impossibility results for symbolic computation/AI. Indeed, in the classical philosophy of AI during the 1980s and 1990s, Gödel's Incompleteness Theorem played a central role in arguing for impossibilities for (symbolic) AI. (See [here](https://plato.stanford.edu/entries/artificial-intelligence/#GodeArguAgaiStroAI) for a brief overview.)

   Discuss whether these classical results have any bearing on modern, non-symbolic AI. If so, how would these results yield impossibilities for neural networks, and—most importantly—would that have any practical impact? If not, how exactly do neural networks evade those results and which other theorems would limit their power—again also thinking of the practical implications? For results in the latter case, think, e.g., of the no-free-lunch theorem in statistical learning theory, or, e.g., of Bastounis et al. (2024 "On the consistent reasoning paradox of intelligence and optimal trust in AI").


* _Interpretability_: One way to state the interpretability problem of neural networks (that I find particularly useful) is in terms of micro-level and macro-level. We completely understand neural networks at the micro-level: how they propagate the activation of the input neurons to the output neurons and how they update their weights during learning. The problem is understanding them at the macro-level: to explain in human-understandable terms this process that goes on at the micro-level. An analogy is provided by thermodynamics: we have a complete understanding of the billions of gas particles in a box (how their position and momentum changes over time), and thermodynamics also provides an understanding of this micro-level process in the macro-level terms of temperature and pressure.

   Geiger et al. (2025, "Causal Abstraction: A Theoretical Foundation for Mechanistic Interpretability") provide a precise general framework to bridge the micro-level and the macro-level in terms of causal models. Discuss this approach by relating to the philosophical literature on explanatory levels as, e.g., presented in this recent edited [book](https://fdslive.oup.com/www.oup.com/academic/pdf/openaccess/9780192862945.pdf) and, in particular, in the first paper in there by List (which is also [here](https://philarchive.org/archive/LISLOD)). Make sure to think of ways to test your claims in concrete tasks and neural networks. 



## Example

As an example of a paper that covers the required steps, you can consider Geiger et al. (2025, "Causal Abstraction: A Theoretical Foundation for Mechanistic Interpretability"). Note, though, that it is much more comprehensive than what would be required for an essay. So this is just for illustration, not to be followed very closely. Very briefly, the idea is this:
* topic: mechanistic interpretability
* research question: can causal abstraction formalize mechanistic interpretability?
* related work: literature on mechanistic interpretability
* philosophical/mathematical theory: causal explanation à la Pearl and specifically the notion of causal abstraction
* experiments: a companion jupyter notebook for a toy example as well as many references to existing results in the mechanistic interpretability literature.
