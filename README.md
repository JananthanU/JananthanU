**MSE Student in Data Science @ HSLU | Machine Learning · Causal Inference · Deep Learning**
---

I’m interested in how data can uncover hidden patterns, explain outcomes, and support better decisions. My work focuses on machine learning, causal inference, and deep learning, with an emphasis on rigorous experimentation, model evaluation, and understanding the strengths and limitations of different approaches.

**Data Science Portfolio:** [Explore my projects](https://jananthanu.github.io/)

---

### Core Areas

**Machine Learning:** scikit-learn | XGBoost | pandas | NumPy  
**Causal Inference:** EconML | Causal Forests | IPW / AIPW  
**Deep Learning:** PyTorch | CNNs | RNNs | Transformers | Transfer Learning

---

### Selected Projects

**[causal-inference-heart-catheter-mortality](https://github.com/JananthanU/causal-inference-heart-catheter-mortality)**   
Estimated effect of right heart catheterization on 30-day mortality in 5'735 ICU patients from the SUPPORT study, using a causal forest, doubly robust AIPW and overlap weights. Adjustment reduces the raw difference from 7.4 to 3.5 percentage points. A sensitivity analysis benchmarked against randomized trials estimates that an unmeasured confounder 1.2 times as strong as all recorded diagnosis variables combined could explain the remaining difference.

**[time-series-forecasting-pipeline](https://github.com/JananthanU/time-series-forecasting-pipeline)**  
End-to-end time-series forecasting pipeline with a feature selection comparison (RFE, Lasso, Random Forest), expanding-window validation and five models: linear regression, Ridge, Lasso, SARIMAX and XGBoost, with hyperparameters tuned in Optuna. The tuned Ridge model reaches R² 0.764.

**[causal-inference-smoking-weight](https://github.com/JananthanU/causal-inference-smoking-weight)**  
Estimated causal effect of smoking cessation on 11-year weight gain in the NHEFS cohort, using a causal forest, IPW and AIPW in an eight-step pipeline. The adjusted estimate is 3.4 kg compared to 2.5 kg in the naive comparison. IPW reproduces the published Hernán and Robins estimate, and the findings are consistent across five robustness checks.

**[image-captioning-flickr8k](https://github.com/JananthanU/image-captioning-flickr8k)**  
Five captioning architectures from CNN-LSTM to Transformer decoder on Flickr8k, evaluated with BLEU and METEOR across greedy and beam search, with attention visualisation.

**[cnn-architecture-study](https://github.com/JananthanU/cnn-architecture-study)**  
Eight controlled CNN experiments covering depth, regularization, optimizer comparison, and transfer learning. Pretrained ResNet18 reaches 94.7% validation accuracy, compared to 77.7% for the same network trained from scratch.
