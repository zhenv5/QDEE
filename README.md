# QDEE: Question Difficulty and Expertise Estimation in Community Question Answering Sites

> In this paper, we present a framework for Question Difficulty and Expertise Estimation (QDEE) in Community Question Answering sites (CQAs) such as Yahoo! Answers and Stack Overflow, which tackles a fundamental challenge in crowdsourcing: how to appropriately route and assign questions to users with the suitable expertise. This problem domain has been the subject of much research and includes both language-agnostic as well as language conscious solutions. We bring to bear a key language-agnostic insight: that users gain expertise and therefore tend to ask as well as answer more difficult questions over time. We use this insight within the popular competition (directed) graph model to estimate question difficulty and user expertise by identifying key hierarchical structure within said model. An important and novel contribution here is the application of "social agony" to this problem domain. Difficulty levels of newly posted questions (the cold-start problem) are estimated by using our QDEE framework and additional textual features. We also propose a model to route newly posted questions to appropriate users based on the difficulty level of the question and the expertise of the user. Extensive experiments on real world CQAs such as Yahoo! Answers and Stack Overflow data demonstrate the improved efficacy of our approach over contemporary state-of-the-art models. The QDEE framework also allows us to characterize user expertise in novel ways by identifying interesting patterns and roles played by different users in such CQAs.

* Last update: 25, June, 2018 
* Corresponding Paper: [QDEE: Question Difficulty and Expertise Estimation in Community Question Answering Sites](https://arxiv.org/abs/1804.00109) has been accepted to The 12th International AAAI Conference on Web and Social Media (ICWSM 2018)
* If you use this code, please consider to cite this paper: [BibTex Download](http://adsabs.harvard.edu/cgi-bin/nph-bib_query?bibcode=2018arXiv180400109S&data_type=BIBTEX&db_key=PRE&nocookieset=1)
* [Slides](https://github.com/zhenv5/homepage/blob/master/documents/Slides_ICWSM_2018_QDEE.pdf)
* [Author Homepage](http://web.cse.ohio-state.edu/~sun.1306)

## Code

Some parts of our QDEE framework leverage our previous work. For example, if you are interested in inferring graph hierarchy via social agony and TrueSkill, you can check [breaking cycles in noisy hierarchies](https://github.com/zhenv5/breaking_cycles_in_noisy_hierarchies), which can reduce a directed graph to a DAG while maintaining the graph structure (hierarchy) as much as possible. 

We are actively working on publishing other parts of our framework. 








