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


---
#### Economic Support through the lens of a small business owner in Finland

![image](https://github.com/user-attachments/assets/f66ea507-04b4-49ce-a67b-4a44fb2ed265)

Finland's governmental support for small business owners is extensive and well-structured, aiming to foster entrepreneurship, innovation, and economic growth. The network graph from Gephi visualizes the interconnected support systems available to a small business owner, showcasing the variety of programs and services designed to assist at different stages of business development.

##### Business Finland
Business Finland plays a central role in supporting small businesses through its innovation funding and export promotion programs (https://www.businessfinland.fi/). These services allow businesses to develop new products, access international markets, and grow their operations.

##### Intellectual Property Support
The Finnish patent and Registration Office (PRH) provides essential services related to trademarks and patents, helping businesses protect their intellectual property and innovate with confidence that their ideas will not be stolen. This allows individuals, even those in marginalized communities, to patent their ideas and pursue them in the form of small businesses.

##### TE Services
TE Services focus on enhancing entrepreneurial skills through training programs and providing grants to new startups. These services are essential for equipping entrepreneurs with the knowledge and financial support needed to navigate the challenges of starting and running a business - regardless of socioeconomic status. This program is unique, as it allows for any individual with no background in running a company to gain the skills and funding necessary to pursue their dreams in the form of a startup (toimistot.te-palvelut.fi).

##### Humanitarian Perspective
From a humanitarian perspective, Finland's extensive support network for small business owners demonstrates the country's commitment to fostering economic inclusion and empowerment. By providing accessible financial, educational, and advisory services, the Finnish government ensurs entrepreneurs from diverse backgrounds have the opportunity to succeed. This inclusive approach not only drives economic growth, but also promotes social equality and inclusion of all citizens.

---
#### The Finnish Political System
![image](https://github.com/user-attachments/assets/642aeddd-08f0-4aef-a358-62217d52f7db)

From this network, it is clear that Finnish citizens have a significant role in the selection of their governing bodies and leadership. An out-degree of two can be observed in both the Finnish Citizen node and the Finnish Parliament node, both connecting to the President and the Prime Minister of Finland. Finnish citizens voting in the National Election determines members of the "Eduskunta," or the Finnish Parliament, which then consequently elects the Finnish Prime Minister (eduskunta.fi). The President, on the other hand, is elected directly through a popular vote - giving complete control to the Finnish citizens. However, the edge between the Finnish Parliament and the President indicates the control that the Parliament has over the Finnish President through legislative action. By examining the pathway of these connections directly, a better idea of the political system can be obtained: 
##### Connections and Pathways:

1. Citizen (Finland) -> Voting in National Elections: Every Finnish citizen over the age of 18 has the right to vote in national elections. This is the primary way citizens participate in the democratic process and influence political decisions.
2. Voting in National Elections -> Finnish Parliament (Eduskunta): The Finnish Parliament, known as the Eduskunta, is elected through proportional representation. Citizens vote for their preferred party, and seats are allocated based on the proportion of votes each party receives.
3. Finnish Parliament (Eduskunta) -> Finnish President: The Finnish President is elected by direct popular vote. However, the Parliament plays a significant role in the functioning of the government and can influence the President’s policies through legislative actions.
4. Finnish Parliament (Eduskunta) -> Finnish Prime Minister: The Prime Minister is typically the leader of the party that holds the majority in Parliament or can form a coalition. The Prime Minister is appointed by the President and confirmed by the Parliament.

The Finnish political system allows great influence from each individual citizen, allowing them to vote in National Elections, determining the composition of the "Eduskunta." This parliament then directly elects the prime minister, which indicates a direct pathway from citizens to the choice of the Finnish Prime Minister. Furthermore, granting citizens the ability to elect a Finnish President solely through popular vote gives power to every Finnish citizen, regardless of socioeconomic background.

##### Network Analysis
In Finland's political network, the citizen node is central and highly connected, reflecting the importance of citizen participation in the democratic process. By analyzing the network metrics, we can gain insights into the functioning of this system. The out-degree of the citizen node in Finland’s network is higher than in Pakistan, indicating that citizens have multiple direct pathways to influence political outcomes. Specifically, citizens can vote in National Elections to choose members of the Finnish Parliament, and they can directly vote for the Finnish President - exemplifying their connectedness across the entire network. This breadth of connections demonstrates the empowerment given to each citizen and their direct influence on the composition and consequently the actions of the Finnish government. Finland also hasn't shown signs up corruption in history - with no reports of injust influence on governing bodies by those in power. This indicates that the Finnish citizen holds uninfluenced sway in the political elections, truly allowing them a say in the direction of the government.

---
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

  
---
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

---
#### The Pakistani Political System
![image](https://github.com/user-attachments/assets/b5a6eefa-ede1-4255-a92b-5a88df74043e)

From this shared network observed earlier, it can be seen that Pakistan's governmental structure is very similar to the Finnish system on the surface. A single out-degree can be observed by each node starting with the Pakistani Citizen except for the National Assembly of Pakistan, which has an out-degree of two, connecting to both the President and the Prime Minister of Pakistan. Pakistani citizens voting in the General Election determines members of the National Assembly of Pakistan which then elects both the President and Prime Minister of Pakistan. This differs slightly from the Finnish system, where the Preisdent is elected solely by a popular vote. By again examining the pathway of these connections directly, a better idea of the political system can be obtained: 
##### Connections and Pathways:

1. Citizen (Pakistan) -> Voting in General Elections: Pakistani citizens aged 18 and above are eligible to vote in general elections. This is the primary method for citizens to participate in the political process and elect their representatives.
2. Voting in General Elections -> National Assembly of Pakistan: The National Assembly is elected through a mixed system of direct and reserved seats. Citizens vote for candidates in their constituencies, and seats are filled based on the first-past-the-post system.
3. National Assembly of Pakistan -> President of Pakistan: The President is elected by an Electoral College comprising members of the National Assembly, the Senate, and the provincial assemblies. While the President's role is largely ceremonial, the position holds some influence in the political system.
4. National Assembly of Pakistan -> Prime Minister of Pakistan: The Prime Minister is the head of government and is usually the leader of the majority party in the National Assembly. The Prime Minister is elected by the National Assembly and is responsible for running the government and implementing policies.

The Pakistani political system allows for some amount of influence from each individual citizen, granting them the ability to vote in General Elections, determining the composition of the Pakistani National Assembly. This parliament then directly elects both the president and the prime minister, idnicating a direct pathway from citizens to the selection of each leader. The government differs in the electing of a figurehead solely through popular vote - only existing in the Finnish political system. This could be interpreted as granting each Pakistani citizen slightly less power in the choice of who actually leads the country.

##### Network Analysis
In contrast to Finland, Pakistan’s political network tells a different story. While on the surface the network may appear similar, with citizens having direct pathways to government leaders, a deeper analysis reveals significant issues with corruption and the manipulation of political power. The out-degree of the citizen node in Pakistan’s network is lower than that in Finland, which shows an initial idea of the citizen holding less power. However, the most significant findings are found when looking into Pakistan's history of interfering with political elections. For instance, military and judicial institutions have historically played a significant role in shaping political outcomes, having a history of imprisoning possible prime minister or presidential elects. To showcase this, a new network can be formed - attempting to illustrate the true nature of Pakistan's governmental selection process. 

![image](https://github.com/user-attachments/assets/d6dba41b-242e-4194-9222-2a90c491697b)
In this network, the judiciary and military nodes have high betweenness centrality, showcasing their role as gatekeepers in the political process. Decisions made by the judiciary can determine the eligibility of candidates for Prime Minister, and the military's influence can shape the actions of the National Assembly. This central positioning allows them to control the flow of power and information, often bypassing the citizen's influence. Additionally, the judiciary and military nodes have higher closeness centrality to the president, prime minister, and National Assembly than the citizen node, signifying their proximity to key political bodies. This proximity showcases the possibility of their exerted influence bypassing the desires of the Pakistani citizens. Through this network analysis it is evident that there is a disproportionate influence by Pakistan's judiciary system and military in the political system. While the citizen should ideally have a direct and influential role in elections, as seen in Finland, their power is significantly lessened by the intervention of the other powerful entities in Pakistan. The judiciary's ability to disqualify candidates or delay elections allows it to control political outcomes that could otherwise be determined by citizens - lessening the power of each vote. Additionally, the military has previously directly influenced the direction of the government through coups, with the most recent attempt failing in 1995. 


---
## Discussion + Conclusion
The comparative analysis of Finland and Pakistan across different domains, citizen support structures, small business support, and political systems, highlights significant disparities in how these two countries function. In Finland, both the citizen and the small business owner benefit from a robust network of support systems. The high out-degree centrality in Finland's networks reflects the accessibility and availability of various government programs aimed at ensuring the well-being of its citizens and the success of its businesses. These include comprehensive welfare systems, free education, extensive retirement benefits, and strong business support services. The political system in Finland also shows a high degree of transparency and citizen participation, with the citizen node playing a vital role in governance, as indicated by the centrality metrics. Additionally, the network graphs largely show the reality of how the Finnish governmental systems function - with no underlying corruption or deceit in the political process for example. 

In contrast, Pakistan's networks reveal a slightly more constrained support structure. The out-degree centrality for both the citizen and the small business owner is  lower, indicating fewer accessible support systems. This is reflected in limited welfare programs, challenges in accessing quality education, and less comprehensive business support. Furthermore, the political network analysis shows that citizen influence is undermined by the disproportionate power of the judiciary and military, leading to a system that does not operate as transparently or effectively as it should. The high betweenness centrality of these institutions in Pakistan's political network highlights their role as gatekeepers, often preventing citizens from having a direct impact on political outcomes.

The findings exemplify the need for policy reforms in Pakistan to enhance citizen and small business support systems. Strengthening the welfare system, expanding educational access, and improving business support mechanisms are critical steps that can help lessen the divide between the two countries. Additionally, reducing the influence of non-elected bodies like the judiciary and military in political processes is essential for fostering a more transparent and democratic political process. For Finland, the results validate the effectiveness of its current policies but also suggest that continuous monitoring and adaptation are necessary to maintain these high standards.

While this study provides valuable insights, it is not without limitations. The analysis was constrained by the availability and scope of data, particularly regarding Pakistan's support systems. Future research could benefit from a more granular approach, including qualitative data on citizen experiences and a deeper exploration of regional differences within each country. Additionally, the study could be expanded to include more countries, providing a broader comparative perspective that could further illuminate the strengths and weaknesses of different governance models.

Another area for future research could focus on the impact of these support systems on specific demographics, such as women, minorities, or rural populations, to understand how equitable these networks are within each country. Moreover, examining the long-term effects of these support systems on economic growth, political stability, and overall happiness would provide a more comprehensive understanding of their effectiveness.

### The role of network analysis
This project utilized network analysis to explore and compare the social support systems, political structures, and business environments in Finland and Pakistan, shedding light on the underlying factors contributing to the stark differences in their happiness scores. By mapping out and analyzing the connections between citizens, governmental support structures, and political institutions, network analysis provided a powerful tool for visualizing and understanding the complexities of each country's governmental systems and political processes.

The findings suggest that the effectiveness and accessibility of support systems, as well as the transparency and inclusivity of political processes, are critical factors in determining a nation's happiness. This project demonstrates the value of network analysis as a tool for policymakers and researchers, offering insights that can guide efforts to improve governance and social well-being in countries facing challenges similar to those identified in Pakistan.



## References/Annotated Bibliography
Graciyal, D. Guna, and Deepa Viswam. “Social Media and Emotional Well-Being: Pursuit of
Happiness or Pleasure.” Asia Pacific Media Educator 31, no. 1 (April 23, 2021): 99–115.
https://doi.org/10.1177/1326365x211003737.
 This resource provides insight into the addictive nature of social media and descent into social
dysfunction occurring when our real life is replaced by a virtual one. It is a very important study
as social media usage could be a factor heavily contributing to a country’s overall happiness
score and it gives a deeper look into the mental health impacts. The discussion of social media
will be prevalent in my work – especially how its effects may diversify among different ethnic
groups and vulnerable individuals. The article also discusses at length different types of “ties,”
mentioning how tie strength can determine emotional well-being of an individual – this will be
very helpful as I conduct network analysis of social media and social interactions as a whole.


Kyriacou, Andreas P. “Ethnic Group Inequalities and Governance: Evidence from Developing
Countries.” Kyklos 66, no. 1 (January 7, 2013): 78–101.
https://doi.org/10.1111/kykl.12012.
 Kyriacou’s article introduces the idea of ethnic heterogeneity or ethnic fractionalization,
which is “measured as the probability that two randomly selected people from a given country do
not belong to the same ethnic group.” She expounds upon this probability, mentioning that ethnic
heterogeneity has been negatively associated with a “range of governance indicators across
countries.” This idea of ethnic heterogeneity can be utilized as a major talking point in my
exploration of the World Happiness Report, as ethnic diversity among countries can be directly
related to factors contributing to happiness through Kyriacou’s explorations. This allows me to
take a more humanitarian approach to analyzing the World Happiness Report, using ethnicity as
a major talking point for governance around the globe.


Tan, Chee‐Seng, Sew‐Kim Low, and Glory Nancy Viapude. “Extraversion and Happiness: The
Mediating Role of Social Support and Hope.” PsyCh Journal 7, no. 3 (July 17, 2018): 133–
43. https://doi.org/10.1002/pchj.220.
 This article delves into the role of social support and individual hope in a person’s overall
happiness. Specifically, the authors dive into the idea that extraversion is related to happiness –
providing research showing that extraverts usually have positive relationships with perceived
social support. This is an interesting article as it could be combined with more research seeking
how “extraverted” individuals in different countries are, and observations could be made that
hint at influencing varying “Social Support” scores across countries. It would also be interesting
to delve into whether specific ethnic groups tend to report themselves as more extroverted. There
could also be an analysis done on social networks of extraverts vs introverts as a supporting
diagram for this exploration.


Ye, Dezhu, Yew-Kwang Ng, and Yujun Lian. “Culture and Happiness.” Social Indicators
Research 123, no. 2 (September 6, 2014): 519–47. https://doi.org/10.1007/s11205-014-
0747-y.
 “Culture and Hapiness” explores one of the most important underlying factors to a country’s
happiness score: culture. The article “examines the predictive power of cultural factors on
the cross-country differences in happiness.” The researchers utilize R^2 scores to compare
relative importance of different cultural factors in a country’s happiness. They examine
dimensions of the GLOBE cultural indices, containing topics including Power Distance
and Gender Egalitarianism. This article will be fundamental in my analysis of what
contributes to each country’s happiness score – and what underlying societal factors are
influencing it. It will also provide a basis on which network analysis at a country-level
granularity can be done, providing insights into cultural factors that may weigh towards a
higher overall happiness score.


Dorius, Shawn F. “The Rise and Fall of Worldwide Education Inequality from 1870 to 2010.”
Sociology of Education 86, no. 2 (August 9, 2012): 158–73.
https://doi.org/10.1177/0038040712456558.
Shawn Dorius’s research seeks to explore and analyze long-run trends in country education
inequality over a 140-year period. Additionally, he brings up the idea of a “world education
revolution,” which relates to the mass expansion of the western model of mass education. He
mentions the primary goal of his research as exploring the effect of a worldwide education
revolution on intercountry education inequalities. This source will help me expand upon the
“Freedom to make life choices” factor detailed as part of the World Happiness Report. Education
has been proven to play a major role in how much power an individual feels they have to make
decisions and exploring the inequalities between countries will be an insightful addition to my
research. Additionally, exploring the impact of a continually spreading western education system
on different ethnic groups and societies across countries will create a meaningful discussion.
This also provides a strong basis for a network analysis – seeing countries as nodes continually
added into a network comprised of those utilizing a western education system.

## Annotated Bibliography

