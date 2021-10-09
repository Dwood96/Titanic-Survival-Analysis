# Titanic

My analysis of the titanic csv lead me down the path of looking at the differing surviva rates of passengers form the three ticket classes present on the titanic. 
Let's first look at the decriptive statistics and breakdown the numbers.

As we can see below there 891 passengers on the titanic. A count of ticket classes and survival show 891 entries meaning that our data is complete and will not need to be edited to complete our analysis.

<class 'pandas.core.frame.DataFrame'>
RangeIndex: 891 entries, 0 to 890
Data columns (total 15 columns):
 #   Column       Non-Null Count  Dtype  
---  ------       --------------  -----  
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
