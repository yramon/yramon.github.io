## About me

I am a Doctoral Researcher in the Applied Data Mining research group at the University of Antwerp (Engineering Department), having a PhD fellowship granted by the [Research Foundation-Flanders](https://www.fwo.be/en/the-fwo/){:target="_blank"}. My PhD supervisor is [Prof. dr. ir. David Martens](https://www.uantwerpen.be/nl/personeel/david-martens/){:target="_blank"}. In my research, I am working on *Explaining Prediction Models on High-dimensional Behavioral data*. More precisely, I am investigating interpretation techniques for explaining decisions of models mining big data, like humanly-generated behavioral data (web browsing data, location data, payments data, and so on) and textual data (online reviews, news articles, and so on). <br/> <br/> In my **first project**, I've proposed two model-agnostic algorithms for computing *counterfactual explanations* by aligning additive feature attribution explanation methods with the notion of counterfactuals. (Read [here](https://www.kdnuggets.com/2020/05/evidence-counterfactuals-predictive-models-big-data.html) my KDnuggets blogpost about counterfactual explanations). These hybrid algorithms are called [LIME-C](https://github.com/yramon/LimeCounterfactual) and [SHAP-C](https://github.com/yramon/ShapCounterfactual). Counterfactual explanations are tailored to a single model decision and show a set of features such that, when removing them (setting their values to zero), the predicted class changes. Martens & Provost (2013) have proposed a heuristic algorithm [SEDC](pages.stern.nyu.edu/~fprovost/Papers/MartensProvost_Explaining.pdf){:target="_blank"} based on local improvement, originally in the context of explaining document classifications (find the open-source code [here](https://github.com/yramon/edc){:target="_blank"}). In this [paper](https://link.springer.com/epdf/10.1007/s11634-020-00418-3?sharing_token=S-ZlX5lQWJkpuxoiUPV8__e4RwlQNchNByi7wbcMAY7sQ9KluI1KeELkdg_mEQicaoXaoohNECLfwgFaf3b6zksBL6ll0pEm465_TkCFlp7tmugduGTXK0-0enwdOxmDo5-DA0ru28xQcmK6soKgWU9rHQcx-QtJAJic3LSda-I%3D){:target="_blank"}, I compared the effectiveness and efficiency of the two novel algorithms against the existing SEDC algorithm, and found that LIME-C is a suitable alternative to SEDC, especially for data with large instances. <br/> <br/> In my **second project**, I've worked on global explanations for prediction models using so-called "metafeatures". We used rule-extraction to extract a set of rules that mimic the decisions of the "black-box" model, of which the inner workings are not interpretable. Metafeatures are high-level features that cluster fine-grained features: for example, Facebook pages can be grouped into categories (e.g., "Fashion" and "Entrepreneurship") and credit card transactions can be grouped into spending categories (e.g.,"Charity" and "Coffee Shops"). In this [paper](https://arxiv.org/abs/2003.04792){:target="_blank"}, we show how explanations using metafeatures (e.g., spending categories) are better at mimicking the black-box model than explanations with the fine-grained features (e.g., transactions). We also show that there are important tradeoffs between fidelity, stability, accuracy, and the complexity of explanation rules.

In 2018 (2016), I've obtained a Master's (Bachelor's) degree in Business Engineering (spec. Financial Engineering) from the University of Antwerp. As part of my Master's program, I studied at the Toulouse School of Management (TSM) during the Fall 2017 semester. 

Find my Curriculum Vitae [here](https://yramon.github.io/files/Resume_YanouRamon_2020.pdf).

## Publications

* Deep Learning on Big, Sparse, Behavioral Data. (2019). <br/>Sofie De Cnudde, Yanou Ramon, David Martens, and Foster Provost.<br/> Big Data, 7:4, p.286-307. Available [online](https://www.liebertpub.com/doi/abs/10.1089/big.2019.0095){:target="_blank"}. <br/>
Full pdf available via this [link](https://www.researchgate.net/publication/338091651_Deep_Learning_on_Big_Sparse_Behavioral_Data){:target="_blank"}.

* A Comparison of Instance-level Counterfactual Explanation Algorithms for Behavioral and Textual Data: SEDC, LIME-C and SHAP-C. (2020). Yanou Ramon, David Martens, Foster Provost, and Theodoros Evgeniou. Advances in Data Analysis and Classification, https://doi.org/10.1007/s11634-020-00418-3. Available [online](https://link.springer.com/article/10.1007/s11634-020-00418-3){:target="_blank"}. <br/>
Full pdf available via this [link](https://rdcu.be/b6HCl){:target="_blank"}.

* Metafeatures-based Rule-Extraction for Classifiers on Behavioral and Textual Data. (2020). <br/> Yanou Ramon, David Martens, Theodoros Evgeniou and Stiene Praet. <br/> *Manuscript under review.* Preprint available on the [arXiv](https://arxiv.org/abs/2003.04792){:target="_blank"}.

## Open-source Code

* Implementation of explanation algorithms [SEDC](https://github.com/yramon/edc), [LIME-C](https://github.com/yramon/LimeCounterfactual) and [SHAP-C](https://github.com/yramon/ShapCounterfactual) to compute counterfactual explanations for predictions of classifiers trained on behavioral and textual data (code in Python). Take a look at the tutorials on how to use the SEDC explainer object to explain model predictions on [behavioral data](https://yramon.github.io/tutorials/Tutorial_BehavioralDataMovielens_LR_SEDC.html){:target="_blank"} and [text data](https://yramon.github.io/tutorials/Tutorial_TextData_SEDC.html){:target="_blank"}!

## Talks & Blogposts
* [A Comparison of Counterfactual Algorithms for Explaining Prediction Models on Behavioral and Textual Data](https://yramon.github.io/files/AIMLAI_YR_Oct2020.pdf){:target="_blank"}
<br/> Invited Talk at [Advances in Interpretable Machine Learning and Artificial Intelligence Workshop](https://project.inria.fr/aimlai/program/){:target="_blank"} (CIKM online conference), 20th of October 2020

* [Towards Explainable Prediction Models on Behavioral and Textual Data.](https://yramon.github.io/files/researchseminar_YR_19june2020.pdf){:target="_blank"} 
<br/> Online Research Seminar, Dpt. of Engineering Management, Antwerp (Belgium), June 2020

* [Explaining predictive models: the Evidence Counterfactual](https://blog.uantwerpen.be/business-economics/predictive-models-on-big-data-mining-a-pool-of-evidence/){:target="_blank"}
<br/> Blogpost Faculty of Business & Economics, University of Antwerp, June 2020

* [Evidence Counterfactuals for explaining predictive models on Big Data.](https://www.kdnuggets.com/2020/05/evidence-counterfactuals-predictive-models-big-data.html){:target="_blank"} 
<br/> KDnuggets blogpost, May 2020

* [Counterfactual explanations for models built from behavioral and textual data.](https://yramon.github.io/files/NYC_presentation_YRamon_oct2019_short.pdf){:target="_blank"} <br/> Invited Talk at LenddoEFL (Knowledge Sharing), New York City (USA), October 2019

* [Comparative study of instance-level explanations for big, sparse data.](https://yramon.github.io/files/EURO_presentation_Dublin_June19_YanouRamon.pdf){:target="_blank"} <br/> EURO Conference, Dublin (Ireland), June 2019

* [Instance-based explanations: motivation, overview, and the evidence counterfactual approach.](https://yramon.github.io/files/ECDA_presentation_Bayreuth_YanouRamon.pdf){:target="_blank"} <br/> European Conference on Data Analysis, Bayreuth (Germany), March 2019 <br/> [book of abstracts](http://www.gfkl.org/ecda2019/wp-content/uploads/sites/7/2019/03/Book_of_Abstracts_FINAL.pdf){:target="_blank"} / [ECDA 2019](http://www.gfkl.org/ecda2019/){:target="_blank"}

## Teaching & Other projects
* Assistant of *Data Mining*, *Ethics in Data Science*, *Case studies and trends in Data Mining*, *Data Engineering* (part of the [Major Data Science](https://www.uantwerpen.be/en/research-groups/applied-data-mining/education/){:target="_blank"}) taught by Prof. David Martens. University of Antwerp, Faculty of Business & Economics. <br/> Responsible for the Python tutorials and the Data Science Challenge (in collaboration with AXA insurance).

* Co-organizer of [Summer School](https://www.uantwerpen.be/en/about-uantwerp/faculties/faculty-of-business-and-economics/studying-and-education/programmes/summer-schools/usa-washington/){:target="_blank"} *The American Business Environment* in Washington D.C. (USA) together with Jonas Vandenbruaene. <br/>
