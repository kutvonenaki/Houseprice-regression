# Houseprice-regression

The set consists of 4 different notebooks and the attached files. In the first notebook named EDA I do explanatory data analysis, transform categorical nominal variables to ordinal, check correlations, perform ANOVA and mutual information tests, fill in missing values etc.

The second notebook is based on baseline linear regression, which I ensembled from Lasso and Ridge regressors. Includes also some feature reduction and parameter tuning.

In the feature selection notebook I try improve the baseline linear prediction by feature selection and engineering, find possible clusters for segmential regressiona, and I also experimented with an automated feature engineering based on tripartitive mutual information. The method seemed to work in some cases but one should be careful of overfitting with those new variables.

In the segmential regression I predict price bins for the houses and perform predictions with different methods, stack and ensemble and also investigate the residuals a bit.

The final result could be improved, mainly by improving the method of binnig, predictor parameters and the set of used features could be re-examined. But since that sounds quite boring, I will move on to other projects.
