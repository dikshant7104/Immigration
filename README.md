# Immigration
FORECASTING UKRAINIAN REFUGEE EMPLOYMENT IN IRELAND'S ACCOMMODATION &amp; FOOD SERVICE SECTOR USING RANDOM FOREST, GRADIENT BOOSTING, AND NEURAL NETWORK MODELS.
* **Objective:** Predict employment levels of Ukrainian refugees in Ireland’s Accommodation & Food Service sector (2022–2024) using other NACE sectors as predictors.
* **Models compared:**
  * **Gradient Boosting**
    * R²: 0.9867
    * RMSE: 393.26
    * MAE: 332.78
    * Best training–validation convergence (≈0.99) → best generalization
      
  * **Random Forest**
    * R²: 0.9830
    * RMSE: 446.60
    * MAE: 283.04 (slightly better than GB)
    * Notable training–validation gap
      
  * **Neural Network**
    * R²: 0.6673
    * RMSE: 1968.29
    * MAE: 1527.97
    * Underperformed substantially
    
* **Best Model:** Gradient Boosting (highest R² & lowest RMSE; best learning-curve convergence)
  
* **Key predictors (GB feature importances):**
  1. **Manufacturing:** 0.2041
  2. **Information & Communication:** 0.1868
  3. **Education:** 0.1239
     
* **Implications:**
  * Manufacturing trends drive support-service demand
  * Digital/ICT growth affects hospitality employment
  * Education/skill development underpins refugee employment opportunities


