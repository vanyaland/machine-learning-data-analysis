# Supervised Learning

[Supervised learning](https://en.wikipedia.org/wiki/Supervised_learning) is the machine learning task of inferring a function from labeled training data. The training data consist of a set of training examples. In supervised learning, each example is a pair consisting of an input object (typically a vector) and a desired output value (also called the supervisory signal).
A supervised learning algorithm analyzes the training data and produces an inferred function, which can be used for mapping new examples. An optimal scenario will allow for the algorithm to correctly determine the class labels for unseen instances. This requires the learning algorithm to generalize from the training data to unseen situations in a "reasonable" way (see inductive bias).

- [Notes](./NOTES.md)

#### Curriculum:

- Week 1
	- Introduction to Machine Learning:
		- [Slides](./slides/1-1.Znakomstvo_s_machinym_obucheniem-Slides.pdf)
		- [Syllabus](./syllabus/1-1.Znakomstvo_s_mashinnym_obucheniem.pdf)
	- Linear Models:
		- [Slides](./slides/1-2.Lineynye_modeli-Slides.pdf)
		- [Syllabus](./syllabus/1-2.Linejnye_modeli.pdf)
	- Tasks:
		- [Linreg: Height/Weight](./linreg-height-weight/peer_review_linreg_height_weight.ipynb)
- Week 2
	- Prevent Overfitting and Measure Quality:
		- [Slides](./slides/2-1.Problema_pereobucheniya-Slides.pdf)
		- [Syllabus](./syllabus/2-1.Problema_pereobucheniya_i_bor_ba_s_nej.pdf)
	- Measure Quality:
		- [Slides](./slides/2-2.Metriki_kachestva-Slides.pdf)
		- [Syllabus](./syllabus/2-2.Metriki_kachestva.pdf)
	- Intro to *scikit-learn*:
		- [Datasets](./sklearn-datasets/sklearn-datasets.ipynb)
		- [Cross-Validation](./sklearn-cross-validation/sklearn-cross-validation.ipynb)
		- [Linear Model: 1](./sklearn-linear-model-1/sklearn-linear-model-1.ipynb)
		- [Linear Model: 2](./sklearn-linear-model-2/sklearn-linear-model-2.ipynb)
		- [Metrics](./sklearn-metrics/sklearn-metrics.ipynb)
	- Tasks:
		- [Overfitting: Bikes Rent](./overfitting-task/overfitting-task.ipynb)
		- [Metrics](./metrics-pa/metrics.ipynb)
- Week 3
	- Linear Models: Statistics
		- [Slides](./slides/3-1.Linejnye_modeli_statisticheskij_vzgljad-Slides.pdf)
		- [Syllabus](./syllabus/3-1.Linejnye_modeli_statisticheskij_vzglyad.pdf)
	- Linear Models: Practical Advice
		- [Slides](./slides/3-2.Prakticheskii_rekomendacii_po_linejnym_modeljam-Slides.pdf)
		- [Syllabus](./syllabus/3-2.Prakticheskie_rekomendacii_po_linejnym_modelyam.pdf)
	- Continuing Intro to the *scikit-learn*:
		- [Grid Search](./sklearn-grid-search/sklearn-grid-search.ipynb)
		- [Bike Sharing Demand: Part 1](./sklearn-case-part-1/sklearn-case-part-1.ipynb)
		- [Bike Sharing Demand: Part 2](./sklearn-case-part-2/sklearn-case-part-2.ipynb)
	- Tasks:
		- [Preprocessing](./preprocessing-lr/preprocessing-lr.ipynb)
- Week 4
	- Decision Trees
		- [sklearn: Decision Trees](./sklearn-decision-trees/sklearn-decision-trees.ipynb)
		- [Slides](./slides/4-1.Reshayushchie_derev_ya-Slides.pdf)
		- [Syllabus](./syllabus/4-1.Reshayushchie_derev_ya.pdf)
	- Random Forests
		- [Slides](./slides/4-2.Kompozicii-derev_ev-Slides.pdf)
		- [Syllabus](./syllabus/4-2.Sluchajnye_lesa.pdf)
		- [sklearn: Random Forest](./sklearn-random-forest/sklearn-random-forest.ipynb)
	- Gradient Boosting
		- [XGBoost](./syllabus/xgboost.pdf)
		- [sklearn: Random Forest vs Gradient Boosting](./sklearn-rf-vs-gb/sklearn-rf-vs-gb.ipynb)
		- [Slides](./slides/4-3.Boosting-Slides.pdf)
		- [Syllabus](./syllabus/4-3.Gradientnyj_busting.pdf)
	- Tasks:
		- [Bagging, Random Forest](./bagging-random-forest/solution.ipynb)
		- [Gradient Boosting](./grad-boosting/grad-boosting.ipynb)
- Week 5
	- Neural Nets
		- [Slides](./slides/5-1.Nejronnaya-set_-Slides.pdf)
		- [Syllabus](./syllabus/5-1.Nejronnye_seti.pdf)
		- [Neural Nets](./neural-nets/task-nn.ipynb)
	- Bayes Classification
	    - [Slides](./slides/5-2.Bayes_classification-Slides.pdf)
		- [Syllabus](./syllabus/5-2.Bajesovskaya_klassifikaciya_i_regressiya.pdf)
		- [Assignment: Bayes Classification](./bayes-clf/solution.ipynb)
	- Metrics and SVM
		- [Slides](./slides/5-3.KNN-Slides.pdf)
		- [Syllabus](./syllabus/5-3.Metricheskie_algoritmy_i_SVM.pdf)
		- [1NN против RandomForest](./1nn-protiv-randomforest/solution.ipynb)
	- Bayes Theorem
		- [Slides](./slides/5-4.Bayes_theorem-Slides.pdf)
		- [Syllabus](./syllabus/5-4.Teorema_Bajesa_v_mashinnom_obuchenii.pdf)
	- Bonus
		- [imdb](./imdb/imdb.ipynb)
		