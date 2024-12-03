# End of Term Portfolio - Jack Sutton
## The "Gossip Girl" in Popular Culture
  Films and television have made us all aware of the gossip girl stereotype. When we think of rumors, giving the cold shoulder, excluding people from friend groups, we subconsciously ascribe these qualities to young women. A long history of media has instilled this cliché that high schools are run by the popular girls whose conniving tactics keep everyone under their thumb. But it can't be that simple right? 
## Researching the "Gossip Girl" Stereotype
  Indeed, the gossip girl stereotype has interested psychologists. Researchers have explored gossip as its own behavior as well as a part of a bigger umbrella of related behaviors. This umbrella is called relational aggression, a non-physical form of aggression including interpersonal manipulation, harming another's social standing and, of course, forms of gossip.
  
  Previous research does find that relational aggression is higher in women compared to men (Archer et al., 2005). But why this is the case is not well explored! Some researchers point to the nature of female friend groups compared to males'. They find that the smaller and closer social networks of female friend groups result in more peer influence compared to the larger networks that males tend to associate with (Kreager et al., 2011). So should we expect differing peer influence for these male and female social groups? And does relational aggression necessarily follow from that peer influence?

  This study will address the gaps outlined above, asking...
  
### ___Is relational aggression correlated with peer influence and does this relationship differ between men and women?___

## My Approach
### Participants
- I used an open source dataset surverying the experiences of 723 North Carolina teens from different schools around the state. 
- They were 14.1 years old on average
- 327 male teens and 396 female teens
- 223 were non-white and 500 were white

### Variables and Questionnaires
- Resistance to Peer Influence (RESPEER)
  -  This questionnaire assessed to what extent teens were resistant to peer influence. Higher scores indicate greater resistance (less prone) to peer influence (Steinberg & Monahan, 2007)
  -  Cronbach's _a_ = 0.794 (good reliability)
  -  Factor Loadings = 0.337 - 0.677
  -  Example Question:
    -  A. Some people go along with their friends just to keep their friends happy. 
<sub>1 = A is really true for me, 2 = A is sort of true for me<sub> 
    -  B. Others refuse to go along with their friends, even if it makes those friends unhappy
<sub>3 = B is sort of true for me, 4 = B is really true for me<sub>

- Relational Aggression (RELAGG)
  -   In the dataset, this measure was compiled across questions assessing relationally aggressive problem behaviors (Multisite Violence Prevention Project, 2004)
  -   Cronbach's _a_ = 0.766 (acceptable reliability)
  -   Factor Loadings = 0.477 - 0.717
  -   Example Question:
    -   How many times in the last month have you tried to keep someone from liking another by saying mean things about them?
<sub>0 = never - 5 = 20 times<sub>

## Results

![graph1](/image/corrmatrix.png/)

- Initial analysis revealed that __low resistance to peer influence was related to a significant increase in relational aggression__ (r = -.25***)
- In addition, I found that __male teens were generally slightly more relationally aggressive than female teens__ (r=-.09*)
- Other exploratory analyses revealed slightly higher relational aggression in non-white teens compared to white teens (r=-.10**), but there was no difference in relational aggression by age

![graph1](/image/moderation.png/)

- The most important results from my research come from the moderation analysis, showing that gender changes the strength of the peer influence + relational aggression relationship
- Surprisingly - __male teens showed a stronger relationship between peer influence and relational aggression than female teens did!__ (indicated by a steeper line for men)
- This means that, under the the influence of their peers, male teens were more relationally aggressive than female teens!
- __Remarkably - the cultural stereotype was turned on its head__


## Analysis and Discussion
- Our findings reveal that, even in their larger and typically more impersonal groups, male teens showed a greater propensity to be relationally aggressive under the influence of their peers
- Again, previous research has firmly held that female teens show more relational aggression
- We also expect that female teens' closer social spaces should predict an even greater extent of relational aggression through higher peer influence in these spaces
- But my results run against these usual patterns and hypotheses in the literature
- These mixed results across the field indicate that this may be a more complex issue than gender
- For now, it is not possible to say once and for all that men are more gossipy than women
- My findings only imply that more research is needed to uncover the precise dynamics driving these differences in relational aggression

## Sources and References

### Dataset:
Hoyle, Rick H. Research on adaptive interests, skills, and environments (RAISE) study, North Carolina, 2015-  
  2019. _Inter-university Consortium for Political and Social Research,_ 2024-09-09.     
  https://doi.org/10.3886/ICPSR36850.v3

### Scales and Questionnaires
Steinberg, L., & Monahan, K. C. (2007). Age differences in resistance to peer influence. _Developmental psychology, 43_(6), 1531–1543. https://doi.org/10.1037/0012-1649.43.6.1531

Miller-Johnson, S., Sullivan, T. N., Simon, T. R., & Multisite Violence Prevention Project (2004). Evaluating the impact of interventions in the Multisite Violence Prevention Study: Samples, procedures, and measures. _American journal of preventive medicine, 26_(1 Suppl), 48–61. https://doi.org/10.1016/j.amepre.2003.09.015

### Background:
Archer, J., & Coyne, S. M. (2005). An integrated review of indirect, relational, and social aggression. 
  _Personality and social psychology review : an official journal of the Society for Personality and Social    
  Psychology, Inc, 9_(3), 212–230. https://doi.org/10.1207/s15327957pspr0903_2

Kreager, D. A., Rulison, K., & Moody, J. (2011). Delinquency and the structure of adolescent peer groups.   
  _Criminology : an interdisciplinary journal, 49_(1), 95–127. https://doi.org/10.1111/j.1745-9125.2010.00219.x

### Source Code:
https://github.com/ajs20021/myproject/blob/main/myproject.Rmd






