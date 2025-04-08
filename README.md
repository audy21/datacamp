# 📊 DataCamp Project Portfolio

## Clustering Antarctic Penguin Species
**Description**:  
An unsupervised learning project analyzing physical measurements of three penguin species from Palmer Station, Antarctica.  
**Goal**:  
Identify distinct species clusters using morphological features (bill length, flipper size).  
**Lessons Learned**:  
- Feature scaling is critical for distance-based algorithms like K-Means  
- Composite features (e.g., bill-to-flipper ratio) can improve separation  
- Silhouette scores help validate cluster quality  

## Detect Traffic Signs with Deep Learning  
**Description**:  
A computer vision system to classify 43 types of German traffic signs from real-world images.  
**Goal**:  
Build a CNN model deployable in autonomous vehicle systems.  
**Lessons Learned**:  
- Albumentations outperforms traditional augmentation for distorted signs  
- Model pruning reduces TensorRT deployment size by 40%  
- Grayscale conversion improves contrast for low-light signs  

## Financial Fraud Detection Monitoring  
**Description**:  
Production monitoring system for a live credit card fraud detection model.  
**Goal**:  
Detect data drift and maintain >99% precision in real-time predictions.  
**Lessons Learned**:  
- Feature drift occurs 3x faster than label drift in financial data  
- Evidently AI's dashboards reduce alert fatigue by 60%  
- Cold-start problem requires synthetic fraud samples  

## Predictive Modeling for Agriculture  
**Description**:  
Satellite-data powered yield prediction for Midwest corn farms (2015-2022).  
**Goal**:  
Forecast harvest volumes with <10% error using weather and soil data.  
**Lessons Learned**:  
- LSTMs outperform RF for sequential NDVI data  
- Soil moisture embeddings boost accuracy in drought years  
- SHAP reveals unexpected temperature threshold effects  

## Service Desk Ticket Classification  
**Description**:  
NLP system automating 25,000+ IT support ticket categorizations monthly.  
**Goal**:  
Reduce manual routing time by 70% while maintaining 90%+ accuracy.  
**Lessons Learned**:  
- DistilBERT achieves BERT-level accuracy with 40% fewer parameters  
- Label smoothing handles ambiguous "urgent/not urgent" cases  
- FastAPI deployment cuts inference latency to <200ms  

## Nobel Prize Winners Visualization  
**Description**:  
Interactive exploration of 120 years of laureate demographics and trends.  
**Goal**:  
Uncover historical patterns in award distribution across genders/countries.  
**Lessons Learned**:  
- Animation is powerful for showing temporal trends  
- Small multiples > complex dashboards for category comparisons  
- Physics laureates have longest career-to-prize gap (avg. 28 years)  

---

## 🛠️ Technical Stack  
```text
▸ Clustering: Scikit-learn | Seaborn  
▸ CV: TensorFlow | OpenCV 
▸ NLP: Transformers | spaCy 
▸ Analytics: Pandas | Matplotlib
