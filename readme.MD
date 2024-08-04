

# Introduction
  

This repository contains code and data for my article "[Estimate House Price in Tokyo: the AutoML and MLOps Approach](https://dgg32.medium.com/estimate-house-price-in-tokyo-the-automl-and-mlops-approach-0ee0d9156fd6)". 



# Prerequisite

H2O, Sklearn

Wandb account

  

# Run
1. Download the "land only" and "land and building" datasets from [reinfolib](https://www.reinfolib.mlit.go.jp/realEstatePrices/)
  

2. Run the reinfolib.ipynb. It preprocesses the data, uses H2O AutoML to create models, and upload the run data to Wandb. Wandb will ask for your Wandb API credential.


## Authors

  

*  **Sixing Huang** - *Concept and Coding*

  

## License

  

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
