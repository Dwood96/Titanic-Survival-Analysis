# Titanic

My analysis of the titanic csv lead me down the path of looking at the differing surviva rates of passengers form the three ticket classes present on the titanic. 
Let's first look at the decriptive statistics and breakdown the numbers.

As we can see below there 891 passengers on the titanic. A count of ticket classes and survival show 891 entries meaning that our data is complete and will not need to be edited to complete our analysis.
   
 0   survived     891 non-null    int64  
 1   pclass       891 non-null    int64  
 2   sex          891 non-null    object 
 3   age          714 non-null    float64
 4   sibsp        891 non-null    int64  
 5   parch        891 non-null    int64  
 6   fare         891 non-null    float64
 7   embarked     889 non-null    object 
 8   class        891 non-null    object 
 9   who          891 non-null    object 
 10  adult_male   891 non-null    bool   
 11  deck         203 non-null    object 
 12  embark_town  889 non-null    object 
 13  alive        891 non-null    object 
 14  alone        891 non-null    bool   
dtypes: bool(2), float64(2), int64(4), object(7)
memory usage: 92.4+ KB

Using Python to create a bar chart we can now see the survival rates from the three different classes of tcket (First, Second and Third) 

![image](https://user-images.githubusercontent.com/92208530/136661676-ab11d6ab-06b9-460c-8194-160964f94543.png)

As you can see there are clear decsrepancies between classes and survival rates. The majority of passengers travelling first class survived the disaster with a fairly balanced distribution in second class. Third class has the highest mortality rate with almost 300 more detahs than the otehr two classes. 

An initial reaction to this graph would be to suspect that the evacuation policy of the titanic meant that it favoured the first, and second class passengers over third. However, this may not be the case. The first issue with this interpretation is that third class clearly has the highest sample size. It has more than triple the number of passengers in first or second class so the likelihood of mrtaily may have been higher. However the more even spread between first and second may suggest that the evacuation policy did favour those in first and second class to some degree. 
The second point to consider is that despite a policy that may appear to favour the the higher ticket class this did not mean they avoided significant mortaily rates due to the disaster. There were still a substantial number of deaths in all classes. The amount of deaths in third class may initially detract attention from this view given the discrepancy. 
Anothre factor to consider is that while the policy may have favoured thos in higher classes it's likely that thos in third were positioned lower down in the boat so when the ship began to sink they were the ones who would have met the water first resulting in death by drowning sooner than those whose living quarters were positioned higher up the ship. So the discrepancy may not be due to policy and rather the positioning of living quarters and facilities.
