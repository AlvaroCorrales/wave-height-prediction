# Forecasting in the Age of Foundation Models
In this repo you can find the code that I used to write the blog [_Forecasting in the Age of Foundation Models_](https://medium.com/towards-data-science/forecasting-in-the-age-of-foundation-models-8cd4eea0079d), which was published in Towards Data Science on 20 July 2024. 

In the blog, I benchmark a foundation model for time series forecasting, [Lag-Llama](https://huggingface.co/time-series-foundation-models/Lag-Llama), against an XGBoost forecaster. 

The results show that Lag-Llama's performance is in line with, but  not significantly better than, more traditional approaches. These results are in line with previous literature, such as Shwartz-Ziv, R., & Armon, A. (2021).

## References
- Rasul, K., Ashok, A., Williams, A. R., Ghonia, H., Bhagwatkar, R., Khorasani, A., Bayazi, M. J. D., Adamopoulos, G., Riachi, R., Hassen, N., Biloš, M., Garg, S., Schneider, A., Chapados, N., Drouin, A., Zantedeschi, V., Nevmyvaka, Y., & Rish, I. (2024). _Lag-Llama: Towards foundation models for probabilistic time series forecasting._ arXiv. https://arxiv.org/abs/2310.08278

- Shwartz-Ziv, R., & Armon, A. (2021). _Tabular data: Deep learning is not all you need._ arXiv. https://arxiv.org/abs/2106.03253

- Puertos del Estado. (2024). _3106036 - Punto SIMAR Lon: -5.083 - Lat: 43.5, Oleaje_. Last accessed: 25/06/2024

- Amat Rodrigo, J., & Escobar Ortiz, J. (2024). _skforecast_ (Version 0.12.1) [Software]. BSD-3-Clause. https://doi.org/10.5281/zenodo.8382788
