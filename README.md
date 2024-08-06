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



#### Humanitarian/Social Networks through the lens of a Finnish Citizen

![image](https://github.com/user-attachments/assets/4236f0d6-6833-467e-8148-b124f88ef970)



##### Welfare Systems
The Finnish welfare system is inclusive by design and offers extensive support to all citizens - which is evident in the variety of welfare-related nodes in the graph. It has also been found to make the well-being of citizens "largely independent of family structures and prevailing market conditions" (https://www.europarl.europa.eu/workingpapers/soci/w9/social_en.htm). It has also been found to be successful in reducing income inequalities (Social Protection in Europe, 1995, the European Commission, COM(95)0457.) The Social Insurance Institution of Finland (Kela) is at the heart of this network, providing a wide range of benefits including unemployment allowances, sickness benefits, and family benefits (Kela). Municipal Social Services, represented in the graph, are vital for delivering localized support - ensuring that needs of individuals in different communities are met. For example, social services respond to circumstances causing social exclusion and make an effort to promote inclusion across Finland - helping reduce feelings of oppression and racism around the country. (https://stm.fi/en/social-services)

##### Retirement Benefits
Finland has shown a strong commitment to supporting its elderly population, as reflected in its universal retirement benefits - managed by Kela and other pension institutions. Their system guarantees that all citizens have access to financial security in their old age - promoting independence and financial freedom in their older population. This is a possible major contributor to the overall happiness score for Finland, as individuals will most definitely have higher feelings of freedom to make life decisions with financial security later in life. Additionally, by having a universal retirement benefits system, there is a lack of possible class disparity and ethnic disparity for those retiring. The presence of nodes related to these universal retirement benefits highlights the importance of these services in the Finnish social fabric, and as a consequence the country's overall happiness score.

##### Access to Free Education
One of the most significant pillars of Finland's social support network is their education system. The graph shows nodes connected to institutions such as the Ministry of Education and the Finnish National Agency for Education (EDUFI). Finland provides free education at all levels, ensuring that every citizen - regardless of race, gender, class, or any other diversifying characters - has the opportunity to pursue academic and professional success. This policy not only promotes social equality and happiness, but also drives economic growth and innovation. These institions and the benefits they provide show clear correlation to factors within the Happiness Report. Specifically, "Freedom to make life decisions" and "GDP" should be significantly impacted by individuals being able to pursue higher education at no cost. 

##### Humanitarian Perspective
From a humanitarian lens, Finland's social structures and support networks exemplify a commitment to human rights and social justice. The comprehensive nature of their services ensures that all citizens, even the most vulnerable, are protected and support. Their approach not only addresses the immediate needs of citizens, but also contributes to long-term social stabiity and prosperity. Finland's extensive and inclusive social support networks, visualized in the Gephi graph, highlight the country's dedication to ensuring that all citizens have access to the resources and services they need to lead healthy, productive, and fulfilling lives. This commitment to social welfare and community engagement is likely a key factor in Finland's high levels of happiness and social cohesion. By comparing this to the support structures in Pakistan, we can gain valuable insights into how different countries approach social support and impact these approaches have on each country's population.



#### Economic Support through the lens of a small business owner in Finland

![image](https://github.com/user-attachments/assets/f66ea507-04b4-49ce-a67b-4a44fb2ed265)

Finland's governmental support for small business owners is extensive and well-structured, aiming to foster entrepreneurship, innovation, and economic growth. The network graph from Gephi visualizes the interconnected support systems available to a small business owner, showcasing the variety of programs and services designed to assist at different stages of business development.

##### Business Finland
Business Finland plays a central role in supporting small businesses through its innovation funding and export promotion programs (https://www.businessfinland.fi/). These services allow businesses to develop new products, access international markets, and grow their operations.

##### Intellectual Property Support
The Finnish patent and Registration Office (PRH) provides essential services related to trademarks and patents, helping businesses protect their intellectual property and innovate with confidence that their ideas will not be stolen. This allows individuals, even those in marginalized communities, to patent their ideas and pursue them in the form of small businesses.

##### TE Services
TE Services focus on enhancing entrepreneurial skills through training programs and providing grants to new startups. These services are essential for equipping entrepreneurs with the knowledge and financial support needed to navigate the challenges of starting and running a business - regardless of socioeconomic status. This program is unique, as it allows for any individual with no background in running a company to gain the skills and funding necessary to pursue their dreams in the form of a startup (toimistot.te-palvelut.f).

##### Humanitarian Perspective
From a humanitarian perspective, Finland's extensive support network for small business owners demonstrates the country's commitment to fostering economic inclusion and empowerment. By providing accessible financial, educational, and advisory services, the Finnish government ensurs entrepreneurs from diverse backgrounds have the opportunity to succeed. This inclusive approach not only drives economic growth, but also promotes social equality and inclusion of all citizens.

#### The Finnish Political System
![image](https://github.com/user-attachments/assets/69ff981e-90ec-4686-8709-d9eeb08f16b2)
From this network, it is clear that Finnish citizens have a significant role in the selection of their governing bodies and leadership. A single out-degree can be observed by each node starting with the Finnish Citizen, except for the Finnish Parliament which has an out-degree of two, connecting to both the President and the Prime Minister of Finland. Finnish citizens voting in the National Election determines members of the "Eduskunta," or the Finnish Parliament, which then consequently elects the Finnish Prime Minister. The President, on the other hand, is elected directly through a popular vote - giving complete control to the Finnish citizens. However, the edge between the Finnish Parliament and the President indicates the control that the Parliament has over the Finnish President through legislative action. By examining the pathway of these connections directly, a better idea of the political system can be obtained: 
##### Connections and Pathways:

1. Citizen (Finland) -> Voting in National Elections: Every Finnish citizen over the age of 18 has the right to vote in national elections. This is the primary way citizens participate in the democratic process and influence political decisions.
2. Voting in National Elections -> Finnish Parliament (Eduskunta): The Finnish Parliament, known as the Eduskunta, is elected through proportional representation. Citizens vote for their preferred party, and seats are allocated based on the proportion of votes each party receives.
3. Finnish Parliament (Eduskunta) -> Finnish President: The Finnish President is elected by direct popular vote. However, the Parliament plays a significant role in the functioning of the government and can influence the President’s policies through legislative actions.
4. Finnish Parliament (Eduskunta) -> Finnish Prime Minister: The Prime Minister is typically the leader of the party that holds the majority in Parliament or can form a coalition. The Prime Minister is appointed by the President and confirmed by the Parliament.

The Finnish political system allows great influence from each individual citizen, allowing them to vote in National Elections, determining the composition of the "Eduskunta." This parliament then directly elects the prime minister, which indicates a direct pathway from citizens to the choice of the Finnish Prime Minister. Furthermore, granting citizens the ability to elect a Finnish President solely through popular vote gives power to every Finnish citizen, regardless of socioeconomic background.


### The Least Happy Country - Pakistan
#### Humanitarian/Social Networks through the lens of a Pakistani Citizen
![image](https://github.com/user-attachments/assets/87bf1283-388f-4399-bc07-da3b2c860113)

##### Welfare Systems
The welfare system in Pakistan aims to provide basic support to its citizens, particularly the most vulnerable groups. The graph includes nodes such as the Benazir Support Programme (BISP) and Pakistan Bait-ul-Mal, which are pivotal in delivering financial assistance to low-income families. These programs are designed to reduce poverty and provide a safety net for those in need (https://bisp.gov.pk/).

##### Retirement Benefits
Retirement benefits are generally provided through various government schemes aimed at ensuring a level of financial security for the elder population in Pakistan. The scope and coverage are not as extensive as other countries, but programs like the Employees' Old-Age Benefits Institution offer pensions to registered workers (http://www.eobi.gov.pk/).

##### Access to Education
Education in Pakistan is a crucial area where significant efforts have been made to improve, but the country is still lacking in comparison to the rest of the world. The graph shows nodes connected to the Ministry of Federal Education and Professional Training - these programs help provide free education for primary education. Secondary and higher education, however, often require fees and are limited to those who can either afford attendance or earn scholarships to cover tuition. This contrasts with the Finnish education system, where every individual - regardless of socioeconomic status - can obtain a higher level education.

##### Humanitarian Perspective
From a humanitarian perspective, Pakistan's social structures and support networks are critical in addressing the basic needs of its population, particularly in the face of economic constraints and developmental challenges. The network graph in Gephi illustrates the government's efforts to provide essential services and support to its citizens - highlighting the achievements and the areas where further development is needed. While Finland's support networks are extensive and well-funded, Pakistan's efforts are characterized by targeted programs aimed at alleviating poverty and improving access to basic needs. A light is shed on possible reasons for Pakistan's low happiness score through this network analysis - showing fundamental problems that could lead to lower reported happiness by Pakistani citizens. 

  

#### Economic Support through the lens of a small business owner in Pakistan

  
![image](https://github.com/user-attachments/assets/2634aa7d-9399-42c3-9e35-bc1420fc863c)


Pakistan's governmental support for small business owners includes a range of programs aimed at fostering entrepreneurship, improving access to finance, and encouraging business growth. However, the Pakistani support network for small businesses shows certain limitations in scope and accessibility for all citizens. For example, a small business may be more likely to receive a loan with small interest rates rather than a grant for a new company. 

##### Small and Medium Enterprises Development Authority (SMEDA)
SMEDA is a central agency providing comprehensive business development services and funding support for SMEs in Pakistan. The nodes representing SMEDA in the graph higlight its key role in the small business ecosystem by offering advisory services, training, and financial assistance to small business owners.

##### State Bank of Pakistan
The State Bank of Pakistan facilitates access to finance for small businesses through schemes like the Refinance and Credit Guarantee Scheme (https://www.sbp.org.pk/). This program allows for businesses to obtain low-cost financing options and credit guarantees to small and medium businesses. 

##### Pakistan Poverty Alleviation Fund
PPAF supports small business owners through microfinance programs, which provides small loans to entrepreneurs who may not have access to banking services. This support is important for poverty alleviation and economic empowerment, particularly in underserved areas where they may not be a bank available (https://www.ppaf.org.pk/).

##### Humanitarian Perspective
Pakistan's support network for small business owners is designed to promote economic inclusion, alleviating poverty and empowering marginalized communities when possible. By providing access to finance, training, and regulatory support, the government creates an environment conducive for entrepreneurship and economic growth. However, the comprehensiveness of Pakistan's programs does not yet match the Finnish support programs. 

#### The Pakistani Political System
![image](https://github.com/user-attachments/assets/69ff981e-90ec-4686-8709-d9eeb08f16b2)
From this shared network observed earlier, it can be seen that Pakistan's governmental structure is very similar to the Finnish system on the surface. A single out-degree can be observed by each node starting with the Pakistani Citizen except for the National Assembly of Pakistan, which has an out-degree of two, connecting to both the President and the Prime Minister of Pakistan. Pakistani citizens voting in the General Election determines members of the National Assembly of Pakistan which then elects both the President and Prime Minister of Pakistan. This differs slightly from the Finnish system, where the Preisdent is elected solely by a popular vote. By again examining the pathway of these connections directly, a better idea of the political system can be obtained: 
##### Connections and Pathways:

1. Citizen (Pakistan) -> Voting in General Elections: Pakistani citizens aged 18 and above are eligible to vote in general elections. This is the primary method for citizens to participate in the political process and elect their representatives.
2. Voting in General Elections -> National Assembly of Pakistan: The National Assembly is elected through a mixed system of direct and reserved seats. Citizens vote for candidates in their constituencies, and seats are filled based on the first-past-the-post system.
3. National Assembly of Pakistan -> President of Pakistan: The President is elected by an Electoral College comprising members of the National Assembly, the Senate, and the provincial assemblies. While the President's role is largely ceremonial, the position holds some influence in the political system.
4. National Assembly of Pakistan -> Prime Minister of Pakistan: The Prime Minister is the head of government and is usually the leader of the majority party in the National Assembly. The Prime Minister is elected by the National Assembly and is responsible for running the government and implementing policies.

The Pakistani political system allows for some amount of influence from each individual citizen, granting them the ability to vote in General Elections, determining the composition of the Pakistani National Assembly. This parliament then directly elects both the president and the prime minister, idnicating a direct pathway from citizens to the selection of each leader. The government differs in the electing of a figurehead solely through popular vote - only existing in the Finnish political system. This could be interpreted as granting each Pakistani citizen slightly less power in the choice of who actually leads the country.


## Comparative Insights
* Key differences between the happiest and least happy countries
* Role of institutions and networks in influencing happiness

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


