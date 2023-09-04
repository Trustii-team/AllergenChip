![trustii logo](/HeroImage.png)

# Allergen Chip data challenge result
This repository contains the [Allergen Chip](https://www.trustii.io/post/allergen-chip) data challenge result including best notebooks source code and documentation.

The Allergen Chip Challenge, a collaborative project led by the French Society of Allergology (SFA) in partnership with the Health Data Hub, focuses on personalized medicine through exploring the antibody profile (immunoglobulin E) developed by each patient in response to their environment. 

The goal of the competition was to develop Machine Learning models that can predict the presence and severity of an allergic disease based on this personalized profile. 
* Understand the relationship between exposome, IgE, and clinical expression of allergy, in particular : 
* Efficiently diagnose and stratify allergic patients
* Gain a better understanding of IgE clusters in relation to age, symptoms, and climate area
* Tackle the complexity of immune response using AI methods

# The Challenge Results

* 292 participants from multiple countries around the world
* 3135 submissions during the 3 months of the challenge
* Best F1 Macro score 0.786 on the private portion of the test set

# The Development Environment 

All the models of the Allergen Chip challenge were built on trustii.io hosted Jupyterhub environnement, each team had access to a notebook session holding 4 vCPU and 16GB RAM and 20GB persistent storage.

# Best Notebooks

| Ranking    | Team               | Score Public Leaderboard | Score Private Leaderboard | Winning model summary |
| -----------|:------------------:| ------------------------:|:-------------------------:|:---------------------:|
| 1          | newbee             | 0.7729301468421065       | 0.7861260189304708        | Check out the report  |
| 2          | Rakesh Jarupula    | 0.7708679388728454       | 0.7748704702609973        | Check out the report  |
| 3          | Mithil             | 0.7670351199543314       | 0.7719777154823506        | Check out the report  |

# The Dataset

The dataset has been provided by Société Française of Allergology (SFA) and prepared with Trustii.io data scientists. The dataset has been constructed from data of more than 4,000 patients includes tabular data associated with image files.

If you are interested by accessing the dataset or collaborating with Trustii.io and SFA on this project, please reach out to us at contact@trustii.io.

# More information

To access the challenge forum discussions and the dataset description, check out the challenge webpage at https://app.trustii.io.


