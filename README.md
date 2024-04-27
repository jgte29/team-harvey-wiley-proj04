# EEP 153 Spring 2024 - Project 04 (Team Harvey Wiley)

## Team Members
Jordan Taqi-Eddin - jgte29@berkeley.edu; GitHub: jgte29

Samantha Wu - samanthawu@berkeley.edu; GitHub: wusamantha

Kimberley Fan - kimberley.fan123@berkeley.edu; GitHub: kimberleyfan

Taylor Lacey - taylorlacey@berkeley.edu; GitHub: tlacey17

Bolor Erdene-Ochir - bolorerdene@berkeley.edu; GitHub: bolorerdene

## Welcome

Welcome to the Project 04 GitHub Repository for Team Harvey Wiley. Our code for the project is organized in the following format:
- master_notebook.ipynb: In this notebook, we compile all of the finished products of code for this project. <br>
**Note:** To test the functionality of all our code, only this notebook needs to be run. If it works, it indicates that all of the code in the other notebooks are properly running.
- nutritional_adequacy.ipynb: In this notebook, we examine the nutritional adequacy of the diets of the households in our analysis.
- demand.ipynb: In this notebook, we examine a system of demands for various food products, and examine heterogeneity in household consumption.
- nutrient_system.ipynb: In this notebook, we explore how demands for various quantities can be expressed as functions of prices, budgets, and household characteristics. Then, illustrate how these quantities can be translated into nutritional components.
- cost_experiments.ipynb: In this notebook, we explore the relationship between costs, budgets, & consumption.

## How to Use
1. Option A: Access Our Repository Via DataHub (*Highly Recommended*)
   - You can access all of the code in our repository via DataHub using this [link](https://datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fjgte29%2Fteam-harvey-wiley-proj04.git&urlpath=lab%2Ftree%2Fteam-harvey-wiley-proj04.git%2F&branch=main).
2. Option B: Clone the repository on your local device:
   ```bash
   git clone https://github.com/jgte29/team-harvey-wiley-proj04.git
   ```

### Notebook Specific Notes:
- master_notebook.ipynb:
     1) To test the functionality of all our code, only this notebook needs to be run. If it works, it indicates that all of the code in the other notebooks are properly running.
     2) Understanding Nutritional Adequacy
We choose take adopted a nuanced approach to examing Nutritonal Adequacy in our project. The best way to explain our approach is through an example. Suppose we have the following nutritional requirements and consumption data for some arbitrary household.

| **Nutrient** | A | B | C | D | Adequacy Share
|:-----------:|:----------:|:-----------:|:----------:|:-----------:|:-----------:|
| **Intake** | 105 kg |53 kg|75 kg|29 kg||
| **Requirement** | 100 kg |100 kg|100 kg|100 kg| |
| **100% Adequacy** | $\times$ | | | | 0.25 |
| **75% Adequacy** | $\times$ | | $\times$ | | 0.50 |
| **50% Adequacy** | $\times$ | $\times$ | $\times$ | | 0.75 |

As we see in the able above, Adequacy Share at some Adequacy Level $\alpha$ is the proportion of nutrients for which a housholds total intake of the nutrient is greater than or equal to $\alpha$.
