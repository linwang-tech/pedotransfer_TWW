# Pedotransfer Functions to Predict Soil Water Retention for Treated Wastewater Irrigated Soil

This repository contains pedotransfer functions (PTFs) used to predict soil water retention for treated wastewater (TWW) irrigated soil. The project is divided into three main parts:

1. **Evaluation of the existing PTFs**: Assessing how well current pedotransfer functions perform for TWW-irrigated soils.
2. **Development of new PTFs considering the effects of TWW**: Creating new PTFs that account for the influence of treated wastewater on soil properties.
3. **Evaluation and development of SAR-PTFs**: Developing new SAR (Sodium Adsorption Ratio) PTFs and integrating them with the PTFs developed in step 2.

## Repository Contents

- [soil_data.xlsx](./soil_data.xlsx): The dataset used in this study.
- [Pedo_TWW.ipynb](./Pedo_TWW.ipynb): The Python script used for all calculations and model evaluations in this study.
- [predicted_vs_measured_water_content_colored.png](./predicted_vs_measured_water_content_colored.png): A visualization of predicted vs. measured soil water content based on the existing PTFs.
- [model_performance.csv](./model_performance.csv): Performance metrics for the predictive models evaluated during the study.
- [vif_data.csv](./vif_data.csv): Results of the Variance Inflation Factor (VIF) analysis, which evaluates multicollinearity between the predictor variables.
- [significant_correlation_matrix.csv](./significant_correlation_matrix.csv):Results of the correlation matrix of the selected soil properties used for existing PTFs in the study.
- [correlation_heatmap.png](./correlation_heatmap.png): A heatmap visualizing the correlation matrix of the soil properties used in the study.
- [pedo_all.png](./pedo_all.png): A graphic representing the development of new PTFs, including the effect of TWW on soil properties.
- [EC_SAR.png](./EC_SAR.png): Results of the evaluation and development of SAR-PTFs, showing the relationship between Electrical Conductivity (EC) and SAR.

## Citation
If you use this repository, please cite it as follows:
Lin, W. et al., 2024. Evaluation and development of soil water retention pedotransfer for treated wastewater-irrigated soils.
