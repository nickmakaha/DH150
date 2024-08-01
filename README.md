# Analyzing the World Happiness Report 2022

## Introduction
The World Happiness Report 2022 provides a comprehensive analysis of happiness across different countries, ranking them based on factors like social support, income, and health. This project aims to explore the societal and humanitarian networks within the happiest and least happy country, identifying the key instutions that contribute to their respective happiness scores. By utilizing network analysis, through comprehensive visualizations and supporting text, insights can be gained into the underlying factors that promote or hinder happiness. The World Happiness Report offers a broad overview of happiness in each country - missing out on the nuanced experience of individual citizens from each nation, a perspective this project aims to capture. 


## Connections to Literature

Graciyal and Viswam (2021) discuss the impact of social media on emotional well-being, highlighting how it can contribute to social dysfunction when real-life interactions are replaced by those in the virtual space. This is relevant to the World Happiness Report as social media usage could heavily influence a country's happiness score. Kyriacou (2013) explores the concept of ethnic heterogeneity and its negative association with governance indicators, providing a foundation for analyzing how ethnic diversity affects happiness. Tan, Low, and Viapude (2018) investigate the role of extraversion and social support in individual happiness, suggesting that countries with higher levels of social support may have higher happiness scores - this provides foundational work upon which example social support networks can be built and analyzed. Ye, Ng, and Lian (2014) examine the impact of cultural factors on happiness, utilizing the GLOBE cultural indices to compare the relative importance of different cultural dimensions.

These studies provide a multifaceted views into the more societal and humanistic  factors influencing happiness, highlighting the importance of social support, governance, culture, and education. However, there are still gaps in understanding how these elements interact and influence overall happiness; this project, through network analysis, aims to address this.


## Significance

Understanding the determinants of happiness is crucial for developing policies that improve the well-being of citizens. This project provides a detailed comparison of the happiest and least happy countries, offering insights into the specific institutions and networks that can enhance or diminish happiness. By identifying these factors, policymakers and citizens can be more informed and hopefully foster environments that support higher happiness levels.

## Methodology
Data for this project is sourced from the World Happiness Report 2022, the World Health Organization, and other various sources (WIP), supplemented by academic articles and reports from humanitarian organizations. The high-level overview involves comparing high-level key metrics such as social support, economic stability, and health indices between the happiest and least happy country. The true analysis, however, occurs in the magnification of the lower level social and humanitarian networks within each country, seeking the underlying infrastructures that may explain the varying happiness scores. To do this, the project aims to explore fundamental support networks within each country through the lens of a citizen and a small business owner. By comparing and contrasting the differences for each of these entitites between the countries, insights can be made into what may be contributing to overall happiness scores.

## Comparative Analysis

### The Happiest Country - Finland



#### Humanitarian/Social

![image](https://github.com/user-attachments/assets/4236f0d6-6833-467e-8148-b124f88ef970)



##### Welfare Systems
The Finnish welfare system is inclusive by design and offers extensive support to all citizens - which is evident in the variety of welfare-related nodes in the graph. It has also been found to make the well-being of citizens "largely independent of family structures and prevailing market conditions" (https://www.europarl.europa.eu/workingpapers/soci/w9/social_en.htm). It has also been found to be successful in reducing income inequalities (Social Protection in Europe, 1995, the European Commission, COM(95)0457.) The Social Insurance Institution of Finland (Kela) is at the heart of this network, providing a wide range of benefits including unemployment allowances, sickness benefits, and family benefits (Kela). Municipal Social Services, represented in the graph, are vital for delivering localized support - ensuring that needs of individuals in different communities are met. For example, social services respond to circumstances causing social exclusion and make an effort to promote inclusion across Finland - helping reduce feelings of oppression and racism around the country. (https://stm.fi/en/social-services)

##### Retirement Benefits
Finland has shown a strong commitment to supporting its elderly population, as reflected in its universal retirement benefits - managed by Kela and other pension institutions. Their system guarantees that all citizens have access to financial security in their old age - promoting independence and financial freedom in their older population. This is a possible major contributor to the overall happiness score for Finland, as individuals will most definitely have higher feelings of freedom to make life decisions with financial security later in life. Additionally, by having a universal retirement benefits system, there is a lack of possible class disparity and ethnic disparity for those retiring. The presence of nodes related to these universal retirement benefits highlights the importance of these services in the Finnish social fabric, and as a consequence the country's overall happiness score.

##### Access to Free Education
One of the most significant pillars of Finland's social support network is their education system. The graph shows nodes connected to institutions such as the Ministry of Education and the Finnish National Agency for Education (EDUFI). Finland provides free education at all levels, ensuring that every citizen - regardless of race, gender, class, or any other diversifying characters - has the opportunity to pursue academic and professional success. This policy not only promotes social equality and happiness, but also drives economic growth and innovation. These institions and the benefits they provide show clear correlation to factors within the Happiness Report. Specifically, "Freedom to make life decisions" and "GDP" should be significantly impacted by individuals being able to pursue higher education at no cost. 

##### Humanitarian Perspective
From a humanitarian lens, Finland's social structures and support networks exemplify a commitment to human rights and social justice. The comprehensive nature of their services ensures that all citizens, even the most vulnerable, are protected and support. Their approach not only addresses the immediate needs of citizens, but also contributes to long-term social stabiity and prosperity. Finland's extensive and inclusive social support networks, visualized in the Gephi graph, highlight the country's dedication to ensuring that all citizens have access to the resources and services they need to lead healthy, productive, and fulfilling lives. This commitment to social welfare and community engagement is likely a key factor in Finland's high levels of happiness and social cohesion. By comparing this to the support structures in Pakistan, we can gain valuable insights into how different countries approach social support and impact these approaches have on each country's population.



#### Economy
* Economic and Institutional Factors
* GDP and economic stability
* Government policies and corruption levels

[Visualization: Network graph of economic indicators, with GDP as a central node and connections to other economic factors]

##### Supporting discussion on how the economy is structured/functions in this country.

#### Health/Education
* Health and Education
* Healthcare systems
* Education quality and accessibility

[Visualization: Network graph of healthcare and education systems, illustrating connections between institutions and outcomes]

##### Supporting discussion on the healthcare system in this country.

### The Least Happy Country - Pakistan
#### Humanitarian/Social
* Social and Humanitarian Networks
* Community engagement
* Welfare systems
![image](https://github.com/user-attachments/assets/87bf1283-388f-4399-bc07-da3b2c860113)

##### Welfare Systems
The welfare system in Pakistan aims to provide basic support to its citizens, particularly the most vulnerable groups. The graph includes nodes such as the Benazir Support Programme (BISP) and Pakistan Bait-ul-Mal, which are pivotal in delivering financial assistance to low-income families. These programs are designed to reduce poverty and provide a safety net for those in need (https://bisp.gov.pk/).

##### Retirement Benefits
Retirement benefits are generally provided through various government schemes aimed at ensuring a level of financial security for the elder population in Pakistan. The scope and coverage are not as extensive as other countries, but programs like the Employees' Old-Age Benefits Institution offer pensions to registered workers (http://www.eobi.gov.pk/).

##### Access to Education
Education in Pakistan is a crucial area where significant efforts have been made to improve, but the country is still lacking in comparison to the rest of the world. The graph shows nodes connected to the Ministry of Federal Education and Professional Training - these programs help provide free education for primary education. Secondary and higher education, however, often require fees and are limited to those who can either afford attendance or earn scholarships to cover tuition. This contrasts with the Finnish education system, where every individual - regardless of socioeconomic status - can obtain a higher level education.

##### Humanitarian Perspective
From a humanitarian perspective, Pakistan's social structures and support networks are critical in addressing the basic needs of its population, particularly in the face of economic constraints and developmental challenges. The network graph in Gephi illustrates the government's efforts to provide essential services and support to its citizens - highlighting the achievements and the areas where further development is needed. While Finland's support networks are extensive and well-funded, Pakistan's efforts are characterized by targeted programs aimed at alleviating poverty and improving access to basic needs. A light is shed on possible reasons for Pakistan's low happiness score through this network analysis - showing fundamental problems that could lead to lower reported happiness by Pakistani citizens. 

  

#### Economy
* Economic and Institutional Factors
* GDP and economic stability
* Government policies and corruption levels
  
[Visualization: Network graph of economic indicators, with GDP as a weak central node and sparse connections to other factors]

##### Supporting discussion on how the economy is structured/functions in this country.

#### Health/Education
* Health and Education
* Healthcare systems
* Education quality and accessibility

[Visualization: Network graph of healthcare and education systems, highlighting weak connections and isolated institutions]

##### Supporting discussion on the healthcare system in this country.


## Comparative Insights
* Key differences between the happiest and least happy countries
* Role of institutions and networks in influencing happiness

[Visualization: Comparative network graph highlighting key differences in social, economic, and institutional connections]
## Discussion
* Interpretation of findings
* Implications for policy and practice
* Limitations of the study and areas for future research
## Conclusion
* Summary of key findings
* Final thoughts on the significance of social and humanitarian networks in determining happiness
* Recommendations for policymakers

## References
Graciyal, D. Guna, and Deepa Viswam. “Social Media and Emotional Well-Being: Pursuit of Happiness or Pleasure.” Asia Pacific Media Educator 31, no. 1 (April 23, 2021): 99–115. https://doi.org/10.1177/1326365x211003737.

Kyriacou, Andreas P. “Ethnic Group Inequalities and Governance: Evidence from Developing Countries.” Kyklos 66, no. 1 (January 7, 2013): 78–101. https://doi.org/10.1111/kykl.12012.

Tan, Chee‐Seng, Sew‐Kim Low, and Glory Nancy Viapude. “Extraversion and Happiness: The Mediating Role of Social Support and Hope.” PsyCh Journal 7, no. 3 (July 17, 2018): 133–43. https://doi.org/10.1002/pchj.220.

Ye, Dezhu, Yew-Kwang Ng, and Yujun Lian. “Culture and Happiness.” Social Indicators Research 123, no. 2 (September 6, 2014): 519–47. https://doi.org/10.1007/s11205-014-0747-y.

Dorius, Shawn F. “The Rise and Fall of Worldwide Education Inequality from 1870 to 2010.” Sociology of Education 86, no. 2 (August 9, 2012): 158–73. https://doi.org/10.1177/003804071245655


## Ideas for Network Graphs
Example thoughts for network & discussion in relation to social support/humanitarian graph
* Citizen A & B on a single graph as nodes, have rest of nodes be support structures.

Support Structure Ideas:
* Welfare
* Retirement benefits
* Veterans benefits?
* Access to free education
* Ability to vote
* Insurance


---
Example thoughts for network & discussion in relation to GDP
* Small business A & B on single graph, showing connections to possible resources and support programs?

Economic support ideas:
* Small business support (Government policies, aid programs)
* Overall GDP of countries (Could I make a node be larger based on a higher value? Have the bigger GDP as a larger node to show a stark difference)
* Distribution of wealth?
* Number of small businesses (Use similar larger node idea for higher number?)

---
Example thoughts for network & discussion in relation to Health/Education
* Create network graph of citizens A & B, have edges be access to resources

Ideas:
* Access to free healthcare
* Access to free education (could go under support/humanitarian section or here)
* Average amount spent on medical care by a citzen each year in respective country (Have a higher number correlate to a larger node to show possible stark difference?)


--- 
Example thoughts for network & discussion in relation to Politics
* Create network graph showing the political system and where a citizen fits in

Ideas:
* Discuss centrality of the network (i.e. is a dictator at the center and the citizen has no edge into the network?)
* A democratic nation shouldn't show much centrality around a single node, it should be well-connected
* This could tie into ideas of corruption in the World Happiness Report

