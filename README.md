# Marketing_Analytics
The package is created to implement CLV analysis.

# Features
Make the data ready to use making it a categorical data.

Find the best model based on the minimum AIC score out of 3 models: LogNormalAFTFitter, LogLogisticAFTFitter, CoxPHFitter.

Calculate the CLV.

Visualize the CLV.

Hypothesis testing.

# Usage

data = prepare_data("Sample_data.xlsx")

data.head()

best_model(data)

calculate_CLV(data)

visualize_CLV(data, 'gender')

hyp_test(data, "gender")
