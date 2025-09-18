# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# Project Water Quality
## Introduction
The purpose of this project is to understand the water quality and how such concentrations of substances and elements impact on humans' ability to consume for the benefit of our health. Various water companies are investing in water infrastructure, such as sanitation, as it generates economic benefits for the respective regions. A cost-benefit analysis would suggest in this case that the benefit of the reduction in disease and health care costs outweighs the cost of water infrastructure. This is because societies as a whole benefit from sanitation interventions. In addition, it is very interesting when we think of the journey water takes from its source in the hills or mountains, reservoirs, and sanitation plants, then to our taps in our homes. 


## Dataset Content
* About the dataset
The dataset has been obtained from the Kaggle website and contains water quality metrics for 3276 water bodies. Therefore, it provides sufficient scope to understand whether the water quality meets the World Health Organization's standards. The WHO standard will be the benchmark for us to measure and comment on the water quality. The dataset is a csv file and is 512kb in size with 10 columns.











#### The table below outlines the measurements, substances,solids and elements that come to be found in the water source. The World Health Organisation's standard indicates what is acceptable for humnan consumption.






| Water Elements  | Description                                                                                                                                                                                                                                                                       | WHO Standard / Cause                                                                 |
|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|
| pH value        | Measures the acidity or alkalinity of the water.                                                                                                                                                                                                                                  | 6.5 – 8.5                                                                            |
| Hardness        | Calcium & magnesium salts. The longer the water is in contact with these salts, the harder the water.                                                                                                                                                                              | —                                                                                    |
| Solids          | Water can dissolve inorganic and organic minerals or salts. This can result in an unwanted taste and appearance of water.                                                                                                                                                          | TDS 500 mg/l – 1000 mg/l for drinking purposes.                                      |
| Chloramines     | Used to disinfect public water systems.                                                                                                                                                                                                                                           | Chlorine levels up to 4 mg/l are considered safe for drinking water.                 |
| Sulfates        | Natural substances found in minerals, soil, and rocks. Also in ambient air, groundwater, plants, and food. Higher concentrations are found in some geographic locations.                                                                                                           | Sulfate ranges from 3 to 30 mg/l.                                                   |
| Conductivity    | Pure water is not a good conductor of electric current but rather a good insulator. An increase in ion concentration enhances the electrical conductivity of water. Generally, the amount of dissolved solids in water determines the electrical conductivity.                        | EC value should not exceed 400 µS/cm.                                               |
| Organic carbon  | Total Organic Carbon (TOC) in source waters comes from decaying natural organic matter (NOM) as well as synthetic sources.                                                                                                                                                         | US EPA: < 2 mg/L TOC in treated/drinking water, < 4 mg/L in source water.            |
| Trihalomethanes | THMs are chemicals that may be found in water treated with chlorine. Levels vary based on organic material, chlorine used, and water temperature.                                                                                                                                    | THM levels up to 80 ppm are considered safe in drinking water.                       |
| Turbidity       | Depends on the quantity of suspended solid matter. It measures the light-emitting properties of water and indicates waste discharge quality regarding colloidal matter.                                                                                                              | WHO-recommended value: 5.00 NTU                                                     |
| Potability      | Indicates if water is safe for human consumption.                                                                                                                                                                                                                                  | 1 = Potable, 0 = Not potable                                                        |



















## Business Requirements
#### Purpose and Scope
* Objective: To assess and classify water samples as potable (safe to drink) or non-potable based on chemical and physical parameters.
* Scope: Applies to municipal water utilities, environmental agencies, or research institutions monitoring water quality.



## Hypothesis and validation

#### The hypotheses will be tested using the Shapiro-Wilk,Chi-square (χ²), and t-tests.

#### Ph levels
* Null hypothesis (H₀): There is no difference in pH between potable and non-potable water.
* Alternative hypothesis (H₁): Potable water has a higher average pH than non-potable water.
#### Chloramine levels 
* Null hypothesis (H₀): There is no difference in Chloramine levels between potable and non-potable water.
* Alternative hypothesis (H₁): Potable water has higher Chloramines concentrations on average than non-potable water.
#### Turbidity
* Null Hypothesis (H₀): There is no difference in turbidity between potable and non-potable samples.
* Alternative Hypothesis (H₁): Potable water has lower turbidity on average than non-potable water.




## Project Plan

* Objective: Analyze water quality parameters to identify factors affecting potability and build insights for decision-making.

* Dataset: water_potability.csv (3,276 records, 9 water quality parameters + potability label).

* Deliverables: Clean dataset, exploratory analysis, hypothesis testing, predictive, and final report.

**Project plan phases**

| Phase                      | Duration     |
|---------------------------|--------------|
| Planning & Setup          | 1 week       |
| Data Cleaning & Processing| 1–2 weeks    |
| EDA & Hypothesis Testing  | 2 weeks      |
| Interpretation & Reporting| 1 week       |








* Outline the high-level steps taken for the analysis.
* How was the data managed throughout the collection, processing, analysis and interpretation steps?
* Why did you choose the research methodologies you used?

## The rationale to map the business requirements to the Data Visualisations
* List your business requirements and a rationale to map them to the Data Visualisations

## Analysis techniques used
* List the data analysis methods used and explain limitations or alternative approaches.
* How did you structure the data analysis techniques. Justify your response.
* Did the data limit you, and did you use an alternative approach to meet these challenges?
* How did you use generative AI tools to help with ideation, design thinking and code optimisation?

## Ethical considerations
* Were there any data privacy, bias or fairness issues with the data?
* How did you overcome any legal or societal issues?

## Dashboard Design
* List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
* Later, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project you were confident you would use a given plot to display an insight but subsequently you used another plot type).
* How were data insights communicated to technical and non-technical audiences?
* Explain how the dashboard was designed to communicate complex data insights to different audiences. 

## Unfixed Bugs
* Please mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 

## Deployment
### Heroku

* The App live link is: https://YOUR_APP_NAME.herokuapp.com/ 
* Set the runtime.txt Python version to a [Heroku-20](https://devcenter.heroku.com/articles/python-support#supported-runtimes) stack currently supported version.
* The project was deployed to Heroku using the following steps.

1. Log in to Heroku and create an App
2. From the Deploy tab, select GitHub as the deployment method.
3. Select your repository name and click Search. Once it is found, click Connect.
4. Select the branch you want to deploy, then click Deploy Branch.
5. The deployment process should happen smoothly if all deployment files are fully functional. Click now the button Open App on the top of the page to access your App.
6. If the slug size is too large then add large files not required for the app to the .slugignore file.


## Main Data Analysis Libraries
* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.


## Credits 

* In this section, you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 
* You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site



## Acknowledgements (optional)
* Thank the people who provided support through this project.
