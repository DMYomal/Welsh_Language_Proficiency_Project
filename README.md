<h1> Descriptive Analysis for Welsh Language Proficiency </h1>

Please check the script folder for the Analysis
https://github.com/DMYomal/Welsh_Language_Proficiency_Project/blob/main/script/main.Rmd

Tools : R Studio

<h2>Background to the research</h2>

The client is the Welsh Government who are interested in what impacts current residents' self-assessed confidence using the Welsh language.
Data has been obtained from residents of North Wales and South Wales, where respondents were asked a series of questions about themselves, and also to take an assessment of their reading, writing, speaking and listening abilities.

<h2>Data structure</h2>

The variables collected for a sample of residents are:
<ul>
<li>resident - If respondent is 'Current' or 'Former' resident of Wales</li>
<li>area - Resident of 'North' Wales or 'South' Wales</li>
<li>hyder - Self-assessed level of proficiency with the Welsh language, selected using a sliding scale (higher values mean higher confidence)</li>
<li>friends - Estimated number of friends or family members proficient with the Welsh language</li>
<li>year - Year of birth</li>
<li>gender - Gender</li>
<li>read - Reading ability score</li>
<li>write - Writing ability score</li>
<li>speak - Speaking ability score</li>
<li>listen - Listening ability score</li>
</ul>

<h2>Data Analysis Findings</h2>

Differences between North Wales and South Wales: The analysis revealed that there were more participants from South Wales compared to North Wales. 
However, there is a significant difference in language proficiency mean scores between the two regions. 
This means that North Wales participants have higher language proficiency than South Wales participants. But when considering the female and male language proficiency, there is no significant difference between genders in each region. The same is applied to the mean of the average of survey results in listening, speaking, writing, and reading.
Patterns in Proficiency (Hyder): The analysis shows a moderate positive correlation (0.596) between language proficiency (Hyder) and the writing ability score. 
This suggests that individuals with higher writing ability tend to have greater self-assessed confidence in the Welsh language. 
Apart from that, reading and friend factors also have a positive correlation with language proficiency respectively.
Also, the writing score shows that most of the participants have achieved marks between 76 and 90. 
Which means the majority of the selected geographic group has a similar level of writing skills. 
Suggestions for Statistical Model: Based on the analysis, it is recommended to consider additional variables or predictors that could enhance the model's predictive power. 
Here, the writing score is the only considered variable as the main factor due to its strong relationship to language proficiency. Further, exploring factors such as speaking ability, listening ability, and the number of friends or family members proficient in Welsh may provide valuable insights into language proficiency. These variables can be included in future research models and it may give a better outcome.
Apart from the selected variables, the initial data collection team can add variables like educational background, Cultural and Social Factors, etc which may give better results.

<h2>Limitations and Conclusion:</h2>

1. The analysis identified missing values and outliers in the dataset, which were handled accordingly.
2. The sample predominantly consisted of females and further investigation into gender-related differences in language proficiency could be explored.
3. The statistical model explained approximately 35.54% of the variability in language proficiency, indicating room for improvement.
4. Most of the participants were born in the 80’s. If the data can be collected from various age groups, language proficiency could be explored by age differences.

In conclusion, this study shed light on the factors influencing language proficiency in North Wales and South Wales. The findings suggest that writing ability plays a significant role in self-assessed confidence in the Welsh language. However, further research considering additional variables and a more balanced gender and age representation would provide a comprehensive understanding of language proficiency in Wales. These insights can be used to assist in developing targeted initiatives to enhance language skills and promote linguistic diversity.


