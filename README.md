# HeadHunterAnalysis
 [HH.ru](https://hh.ru) is the leader of job searching market in Russia.

 ## Task
 The goal of this task is analyse data of 44744 CVs and give a feedback about distribution of these CV depending on features from the dataset.

 ## Instructions
 To run the notebook:

 1. Download csv files from [google drive](https://drive.google.com/drive/folders/1PwT1cllWeKZ2oFbjjzu7_e6erpPAT2D6?usp=drive_link)
 2. Put these files to the 'data' folder in the same directory as .ipynb file
 3. Install dependencies `pip3 install -r requirements.txt`
 4. Open .ipynb file in your IDE and run all cells to see results

 ## Preview
 You can find a preview of the notebook on [github](https://github.com/DmitriyS1/HeadHunterAnalysis/blob/main/HeadHunterAnalysis._Dmitrii_Semenov.ipynb)

 Plotly doesn't appear in this preview, so here are some plots:

 - ### Age histogram ![age_h](/plots/AgeHistogram.png)
 - ### Age boxplot ![age_b](/plots/AgeBox.png)
 - ### Experience histogram ![exp_h](/plots/ExperienceHistogram.png)
 - ### Experience boxplot ![exp_b](/plots/ExperienceBox.png)
 - ### Salary histogram ![sal_h](/plots/SalaryHistogram.png)
 - ### Salary boxplot ![sal_b](/plots/SalaryBox.png)
 - ### Salary on education scatter plor ![sal_edu_s](/plots/SalaryOnEducationScatter.png)
 - ### Salary on city scatter ![sal_city_s](/plots/SalaryOnCityScatter.png)
 - ### Heatmap of salary depending on age and education ![sal_age_edu_hm](/plots/SalaryOnEducationAndAgeHeatmap.png)
 - ### Experience in years on age in years. Red line shows values where experience is equal to age, purple line shows values where experience starts at 15 years ![exp_age_s](/plots/ExperienceOnAgeScatter.png)

