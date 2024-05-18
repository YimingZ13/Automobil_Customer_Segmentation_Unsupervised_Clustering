# Automobil Customer Segmentation

## Table of Contents
1. [Introduction](#Introduction)
2. [File Structure](#FileStructure)
3. [Installing](#Installing)
4. [Feature Documentations](#FeatureDocumentations)
5. [Cluster Profiles](#ClusterProfiles)
6. [Authors](#Authors)
7. [License](#License)

<a name="Introduction"></a>
## Introduction
For an automobile company aiming to enhance its marketing strategies and tailor its product offerings, understanding diverse customer needs is crucial. To achieve this, we are embarking on a customer segmentation project utilizing clustering techniques, specifically KMeans and hierarchical clustering. These methods will allow us to dissect our extensive customer base into distinct groups based on various behavioral and demographic traits. By identifying unique customer segments, we can deliver more personalized marketing messages, optimize our product development, and ultimately foster stronger customer relationships. This strategic approach will not only help in precisely targeting potential buyers but also in maximizing customer satisfaction and loyalty in a competitive market. Through this project, we aim to leverage data-driven insights to drive decisions that align closely with consumer preferences and market trends.

The [original datasets](https://www.kaggle.com/datasets/vetrirah/customer?select=Train.csv), encapsulates customer data of an automobile company.

<a name="FileStructure"></a>
## File Structure
Each of the following project steps is completed in a separate notebook:
- [Data Cleaning and EDA](https://github.com/YimingZ13/Automobil_Customer_Unsupervised_Segmentation/blob/main/customer_segmentation_cleaning_EDA.ipynb): `customer_segmentation_cleaning_EDA.ipynb`
- [Modelling and Cluster Profiling](https://github.com/YimingZ13/Automobil_Customer_Unsupervised_Segmentation/blob/main/customer_segmentation_modelling.ipynb): `customer_segmentation_modelling.ipynb`

<a name="Installing"></a>
## Installing
There are no special packages needed for this project, most of packages come with the Anaconda distribution of Python 3.

<a name="FeatureDocumentations"></a>
## Feature Documentations
- `ID`: Unique customer IDs
- `Gender`: Gender of the customer
- `Ever_Married`: Marital status of the customer
- `Age`: Age of the customer
- `Graduated`: Is the customer a graduate
- `Profession`: Profession of the customer
- `Work_Experience`: Recent work experience in years
- `Spending_Score`: Spending score of the customer
- `Family_Size`: Number of family members for the customer (including the customer)
- `Var_1`: Anonymised Category for the customer

<a name="ClusterProfiles"></a>
## Cluster Profiles
**Cluster 0: Seasoned Mid-Career Individuals**
- **Demographics**: Comprised mainly of middle-aged people, often with small families, such as young couples or families with one child.
- **Economic Profile**: With a moderate spending score and solid work experience, this group demonstrates financial stability but avoids lavish spending. They typically seek out vehicles that are both practical and dependable, offering a good balance of cost and quality.
- **Professional Background**: This cluster includes a mix of creative professionals like artists and entertainers, as well as technical and healthcare workers, indicating a preference for cars that combine style with functionality. They likely favor cars with distinct designs that also serve well for daily commutes and family trips.

**Cluster 1: Elder Professionals and Retirees**
- **Demographics**: Generally older individuals, including retirees or those close to retirement, whose children have moved out.
- **Economic Profile**: Despite a recent decrease in work experience, this cluster shows the highest spending scores, suggesting they have substantial disposable income from sources like savings or retirement plans. They tend to prefer luxury or higher-end vehicles.
- **Professional Background**: Predominantly made up of high-level professionals such as lawyers and executives, this group leans towards luxury vehicle brands that provide enhanced comfort, prestige, and cutting-edge features.

**Cluster 2: Emerging Young Professionals**
- **Demographics**: Largely younger adults, often with large or extended families, which might require vehicles with more space.
- **Economic Profile**: Exhibits the lowest spending scores, indicative of a conservative approach to spending, likely influenced by early career stages and significant family obligations.
- **Professional Background**: A notable presence of healthcare professionals and those with generally lower levels of formal education points to a preference for vehicles that are affordable, durable, and efficient.

<a name="Authors"></a>
## Authors
Yiming Zhao | [LinkedIn](https://www.linkedin.com/in/yiming-zhao13/)

<a name="License"></a>
## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

The project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
