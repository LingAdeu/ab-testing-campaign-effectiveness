![header](header.png)

# Evaluating Marketing Campaign Effectiveness for New Menu Items: An A/B Testing Approach

## About
Since a fast-food company plans to launch its new menu items to the public, which campaign strategy to choose by the Marketing Manager to promote the new products becomes crucial issue. This project aims to find which promotional campaign performs the best in generating sales during the trial phase. To this end, statistical analyses were performed. Prior to examining the campaigns, a series of tests on parametric assumptions were carried out to inform suitable statistical tools. These initial tests suggest that the distributions of sales by promotional campaigns are not normally distributed. Some outliers are present in all promotional campaigns. Furthermore, Levene's test indicates that the variances across promotional campaigns are roughly equal. While one assumption was met, the rest assumptions of parametric assumptions were violated. For this reason, non-parametric test, particularly Kruskal-Wallis *H* test, followed by Dunn's post-hoc test, was used to examine the difference between three promotional campaigns. An effect size along with confidence intervals were also supplemented to investigate the practical significance of the difference.

The main analysis revealed that the first out of three promotion has successfully generated the largest amount of sales based on the median values. Despite finding the significant difference between promotional campaigns, the practical difference is not big enough. This small impact implies that while the campaigns do affect sales, the impact is relatively small.

Based on these results, reviewing the current marketing strategies, including considering more relevant target customers, is the key recommendation to the Marketing Manager of the fast-food company.

## Dataset
The dataset for this project was obtained from [Kaggle](https://www.kaggle.com/datasets/chebotinaa/fast-food-marketing-campaign-ab-test). In general, this dataset contains seven variables, extracted from IBM Watsons Analytics. 

## Usage
To replicate my analysis or explore the data further, kindly follow the following steps:
1. Clone this repository to your local machine.
```bash
git clone https://github.com/LingAdeu/ab-testing-campaign-effectiveness.git
```
2. Ensure that all necessary dependencies are installed, especially Python and Jupyter Notebook. Other than these, all libraries are specified on file requirements.txt which can be executed by running the following script on the terminal.

```bash
pip install numpy==1.23.5 pandas==1.5.3 ptitprince==0.2.7 scikit-posthocs==0.9.0 scipy==1.10.1 seaborn==0.11.0 statsmodels==0.14.2
```
3. Run my Jupyter Notebook file (`*.ipynb`) in notebook folder to reproduce the analysis.

## Feedback
If you have suggestions for improvements, I will be happy to receive them here:

<a href="https://www.linkedin.com/in/adelia-januarto/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="linkedin logo"/>
  </a>
<a href="mailto:januartoadelia@gmail.com" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg"  width="52" height="40" alt="gmail logo"/>
  </a>