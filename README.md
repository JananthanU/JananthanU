**MSE Student Data Science @ HSLU** | RPA Developer @ Luzerner Kantonalbank
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
Effect of right heart catheterization on 30-day mortality in 5,735 ICU patients from the SUPPORT study, estimated with a causal forest, doubly robust AIPW and overlap weights. Adjustment halves the raw difference from 7.4 to 3.5 percentage points, and a sensitivity analysis benchmarked against randomized trials shows that a hidden confounder 1.2 times as strong as all recorded diagnosis variables together would close the remaining gap.

**[time-series-forecasting-pipeline](https://github.com/JananthanU/time-series-forecasting-pipeline)**  
End-to-end time-series forecasting pipeline with a feature selection comparison (RFE, Lasso, Random Forest), expanding-window validation and five models: linear regression, Ridge, Lasso, SARIMAX and XGBoost, with hyperparameters tuned in Optuna. The tuned Ridge model reaches R² 0.764.

**[causal-inference-smoking-weight](https://github.com/JananthanU/causal-inference-smoking-weight)**  
Causal effect of quitting smoking on 11-year weight gain in the NHEFS cohort, estimated with a causal forest, IPW and AIPW along an eight-step pipeline. The adjusted effect is 3.4 kg compared to 2.5 kg from the naive comparison, with IPW reproducing the published Hernán and Robins estimate and 5 of 5 robustness checks passed.

**[image-captioning-flickr8k](https://github.com/JananthanU/image-captioning-flickr8k)**  
Five captioning architectures from CNN-LSTM to Transformer decoder on Flickr8k, evaluated with BLEU and METEOR across greedy and beam search, with attention visualisation.

**[cnn-architecture-study](https://github.com/JananthanU/cnn-architecture-study)**  
Eight controlled CNN experiments covering depth, regularization, optimizer comparison, and transfer learning. Pretrained ResNet18 reaches 94.7% validation accuracy, compared to 77.7% for the same network trained from scratch.
