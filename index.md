## About me

I am a Doctoral Researcher in the Applied Data Mining research group at the University of Antwerp (Engineering Department) (PhD fellowship granted by the [Research Foundation-Flanders](https://www.fwo.be/en/the-fwo/){:target="_blank"}). My PhD supervisor is [Prof. dr. ir. David Martens](https://www.uantwerpen.be/nl/personeel/david-martens/){:target="_blank"}. In my research, I am working on *Explaining Prediction Models on High-dimensional, Sparse data*. More precisely, I am investigating interpretation techniques for explaining decisions of prediction models trained on ultra-high-dimensional data, like humanly-generated behavioral data (web browsing data, location data, payments data, and so on) and textual data (online reviews, news articles, and so on). <br/> <br/> In my first project, I've proposed two model-agnostic algorithms for computing *counterfactual explanations* by aligning additive feature attribution explanation methods with the notion of counterfactuals. These hybrid algorithms are called [LIME-C](https://github.com/yramon/LimeCounterfactual) and [SHAP-C](https://github.com/yramon/ShapCounterfactual). Counterfactual explanations are tailored to a single model decision and show a set of features such that, when removing them (setting their values to zero), the predicted class changes. (Read my blogpost on the Evidence Counterfactual [here](https://www.kdnuggets.com/2020/05/evidence-counterfactuals-predictive-models-big-data.html)). Martens & Provost (2013) have proposed a heuristic algorithm [SEDC](pages.stern.nyu.edu/~fprovost/Papers/MartensProvost_Explaining.pdf){:target="_blank"} based on local improvement, originally in the context of explaining document classifications (find the open-source code [here](https://github.com/yramon/edc){:target="_blank"}). In this [paper](https://arxiv.org/abs/1912.01819){:target="_blank"}, I compared the effectiveness and efficiency of the two novel algorithms against the existing SEDC algorithm, and found that LIME-C seems a suitable alternative to SEDC, especially for data with large instances. <br/> <br/> In my second project, I've worked on global explanations for prediction models using so-called "metafeatures". We used rule-extraction as the global explanation model, where the goal is to extract a set of rules that mimic the decisions of the "black-box" model, of which the inner workings are not interpretable. "Metafeatures" are higher-level features that cluster fine-grained features: for example, Facebook pages can be grouped into categories (e.g., "Fashion" and "Entrepreneurship") and credit card transactions can be grouped into spending categories (e.g.,"Charity" and "Coffee Shops"). In this [paper](https://arxiv.org/abs/2003.04792){:target="_blank"}, we show that using metafeatures to approximate the behaviour of a prediction model on big data improves a key "cost of explainability", which we define as the loss in fidelity when replacing the black-box with a set of explanation rules. We show how explanations using metafeatures are better at mimicking the underlying model than explanations using the fine-grained features, while also resulting in better tradeoffs between fidelity, stability, accuracy, and comprehensibility.

In 2018 (2016), I've obtained a Master's (Bachelor's) degree in Business Engineering (spec. Financial Engineering) from the University of Antwerp. As part of my Master's program, I studied at the Toulouse School of Management (TSM) during the Fall 2017 semester. 

Click here to download my [CV](https://yramon.github.io/files/YanouRamon_CV_2020_Academic.pdf){:target="_blank"}.

## Publications

* Deep Learning on Big, Sparse, Behavioral Data. (2019). <br/>Sofie De Cnudde, Yanou Ramon, David Martens, and Foster Provost.<br/> Big Data, 7:4, p.286-307. Available [online](https://www.liebertpub.com/doi/abs/10.1089/big.2019.0095){:target="_blank"}.

* Instance-level explanation algorithms for textual and behavioral data: a counterfactual-oriented comparison. (2020). <br/> Yanou Ramon, David Martens, Foster Provost, and Theodoros Evgeniou. <br/> *Forthcoming in Advances in Data Analysis and Classification.* <br/>
Preprint available on the [arXiv](https://arxiv.org/abs/1912.01819){:target="_blank"}.

* Metafeatures-based Rule-Extraction for Classifiers on Behavioral and Textual Data. (2020). <br/> Yanou Ramon, David Martens, Theodoros Evgeniou and Stiene Praet. <br/> *Manuscript under review.* <br/>
Preprint available on the [arXiv](https://arxiv.org/abs/2003.04792){:target="_blank"}.


## Talks & Blogposts
* [Towards Explainable Prediction Models on Behavioral and Textual Data.](https://yramon.github.io/files/researchseminar_YR_19june2020.pdf){:target="_blank"} 
<br/> Online Research Seminar, Dpt. of Engineering Management, Antwerp (Belgium), June 2020

* [Evidence Counterfactuals for explaining predictive models on Big Data.](https://www.kdnuggets.com/2020/05/evidence-counterfactuals-predictive-models-big-data.html){:target="_blank"} 
<br/> KDnuggets blogpost, May 2020

* [Counterfactual explanations for models built from behavioral and textual data.](https://yramon.github.io/files/NYC_presentation_YRamon_oct2019_short.pdf){:target="_blank"} <br/> Invited Talk at LenddoEFL (Knowledge Sharing), New York City (USA), October 2019

* [Comparative study of instance-level explanations for big, sparse data.](https://yramon.github.io/files/EURO_presentation_Dublin_June19_YanouRamon.pdf){:target="_blank"} <br/> EURO Conference, Dublin (Ireland), June 2019

* [Instance-based explanations: motivation, overview, and the evidence counterfactual approach.](https://yramon.github.io/files/ECDA_presentation_Bayreuth_YanouRamon.pdf){:target="_blank"} <br/> European Conference on Data Analysis, Bayreuth (Germany), March 2019 <br/> [book of abstracts](http://www.gfkl.org/ecda2019/wp-content/uploads/sites/7/2019/03/Book_of_Abstracts_FINAL.pdf){:target="_blank"} / [ECDA 2019](http://www.gfkl.org/ecda2019/){:target="_blank"}

## Teaching & Other projects
* Assistant of *Data Mining*, *Ethics in Data Science*, *Data Engineering* taught by Prof. David Martens. <br/> University of Antwerp, Faculty of Business & Economics. <br/> Responsible for the Data Science Challenge (in collaboration with AXA Bank) and the Python tutorials.

* Co-organizer of [Summer School](https://www.uantwerpen.be/en/about-uantwerp/faculties/faculty-of-business-and-economics/studying-and-education/programmes/summer-schools/usa-washington/){:target="_blank"} *The American Business Environment* in Washington D.C. (USA) together with Jonas Vandenbruaene. <br/>
