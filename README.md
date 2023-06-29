# Modular End-to-End ML Project Pipeline

Welcome to the Modular End-to-End ML Project Pipeline! This GitHub project aims to revolutionize the way you develop and deploy machine learning (ML) models. By providing a flexible and modular pipeline, it simplifies the complexities of ML workflows, enabling you to focus on what matters most – building accurate and reliable models.

## Features

- **Modularity**: Our pipeline is designed with modularity in mind, allowing you to easily manage and execute various components of the ML workflow. Whether it's data ingestion, transformation, or model training, each module can be customized to fit your project's specific requirements.

- **Efficiency**: With optimized data processing and model training pipelines, you can save valuable time and resources. Our pipeline incorporates state-of-the-art algorithms and libraries, ensuring efficient execution and high-performance models.

- **Insights from Data Analysis**: Our included Jupyter Notebook (`data_analysis.ipynb`) empowers you to gain deep insights into your data. Explore statistical analyses, visualize trends, and unlock the hidden patterns that drive model performance.

- **Model Comparison and Selection**: Evaluate and compare various regression models, including Linear Regression, Lasso, Ridge, and more. The provided Jupyter Notebook enables you to assess performance metrics such as RMSE, MAE, and R2, helping you select the best model for your needs.

- **Deployment Made Easy**: Seamlessly deploy your ML models on cloud platforms like AWS and Azure. Whether you choose an EC2 instance or leverage the power of GitHub Actions, our project provides step-by-step guidance to simplify deployment.

## Example Dataset and Results

To showcase the capabilities of our pipeline, we have utilized the "Student Performance" dataset to predict math exam performance. Our data analysis revealed fascinating insights, uncovering the impact of factors like gender, parental education level, lunch type, and race/ethnicity on student outcomes.

![Distribution by gender](notebook/Graphs/by_gender.jpg) ![Distribution by lunch](notebook/Graphs/by_lunch.jpg) 
![Distribution by parental education](notebook/Graphs/by_parental_education.jpg) ![Distribution by race ethnicity](notebook/Graphs/by_race_ethnicity.jpg) 

![Score Distribution](notebook/Graphs/score_distribution.jpg) 
![Population Distribution across categories](notebook/Graphs/distribution_across_categories.jpg)

By comparing various regression models, including Decision Trees, Random Forest, and XGBoost, we identified the best-performing model based on key metrics such as RMSE, MAE, and R2. This ensures that your predictions are accurate and reliable, giving you the confidence to make informed decisions.

## Getting Started

Getting started with our project is quick and straightforward. Follow these steps to harness the power of the Modular End-to-End ML Project Pipeline:

1. **Installation**: Clone the repository and install the required dependencies using `pip install -r requirements.txt`.

2. **Data Analysis**: Dive into the provided Jupyter Notebook (`data_analysis.ipynb`) to gain insights into your dataset, understand its characteristics, and identify key features that impact your predictions.

3. **Customization**: Customize the data ingestion, transformation, and model training components according to your specific project requirements. Our modular design empowers you to tailor the pipeline to your unique needs.

4. **Execution**: Execute the pipeline by running the main script or invoking specific module functions. Witness the seamless flow of data ingestion, transformation, and model training that brings your ML project to life.

## Deployment

### AWS

To deploy the Modular End-to-End ML Project Pipeline on AWS using an EC2 instance, follow these steps:

1. **EC2 Instance Setup**: Launch an EC2 instance with the desired specifications and ensure that it has the necessary permissions and security configurations.

2. **Repository Setup**: Clone this repository onto your EC2 instance and navigate to the project directory.

3. **Configuration**: Set up the required AWS credentials and configuration on your EC2 instance. This will enable the pipeline to access AWS services.

4. **EB Extensions**: Update the `python.config` file located inside the `.ebextensions` directory with your specific project configurations, such as the required Python version and any additional environment setup.

5. **Deployment**: Execute the pipeline by running the main script or invoking specific module functions on your EC2 instance. Ensure that the required dependencies and data files are accessible.

### Azure

To deploy the Modular End-to-End ML Project Pipeline on Azure using GitHub Actions, follow these steps:

1. **Azure Setup**: Set up an Azure account and create a new Azure Machine Learning Workspace.

2. **Repository Setup**: Fork this repository and clone it onto your local machine or Azure cloud environment.

3. **GitHub Actions**: Set up GitHub Actions for your forked repository. Configure the required secrets and workflows to trigger the pipeline execution.

4. **Azure Resources**: Create the necessary Azure resources (such as compute instances, storage accounts, and containers) required for your specific ML project. Update the pipeline configuration accordingly.

5. **Pipeline Execution**: With the GitHub Actions workflow set up, the pipeline will be automatically triggered based on your defined conditions. Monitor the workflow execution and access the results.

## Contribute and Collaborate

We value the contribution and collaboration of the open-source community. By joining us in this journey, you can help enhance the capabilities, add new features, and drive innovation in the Modular End-to-End ML Project Pipeline.

- Found a bug? Have a brilliant idea? Visit the [issue tracker](https://github.com/jkp2599/MLprojecte2e/issues) to report bugs, suggest improvements, or share your thoughts.

- Ready to contribute? Fork the project, create a new branch, and submit a pull request. We appreciate your valuable contributions!


