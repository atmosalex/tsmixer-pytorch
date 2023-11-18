https://github.com/marcopeix/time-series-analysis/blob/master/TSMixer.ipynb
https://arxiv.org/pdf/2303.06053.pdf

> For multivariate long-term forecasting datasets, we follow the settings in recent research (Liu et al., 2022b; Zhou et al., 2022a; Nie et al., 2023). We set the input length L = 512 as suggested in Nie et al. (2023) and evaluate the results for prediction lengths of T = {96, 192, 336, 720}. We use the Adam optimization algorithm (Kingma & Ba, 2015) to minimize the mean square error (MSE) training objective, and consider MSE and mean absolute error (MAE) as the evaluation metrics. We apply reversible instance normalization (Kim et al., 2022) to ensure a fair comparison with the state-of-the-art PatchTST (Nie et al., 2023).

> For the M5 dataset, we mostly follow the data processing from Alexandrov et al. (2020). We consider the prediction length of T = 28 (same as the competition), and set the input length to L = 35. We optimize log-likelihood of negative binomial distribution as suggested by Salinas et al. (2020). We follow the competition’s protocol (Makridakis et al., 2022) to aggregate the predictions at different levels and evaluate them using the weighted root mean squared scaled error (WRMSSE). More details about the experimental setup and hyperparameter tuning can be found in Appendices C and E.