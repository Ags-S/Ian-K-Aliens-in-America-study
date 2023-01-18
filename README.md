****<h1 align = "center"> Aliens in America case study </h1>****

<h4 align = "left"> Agnieszka Karolina Szewczyk</h4><br><br>

<h3> SCENARIO </h3>
<P>You play a role as a newly hired Data Analyst for a pharmaceutical company. <br>
It's the year 2022 and aliens are well known to be living amongst us. Unfortunately, some of the aliens are a bit... too alien... and would like to fit into society a bit more.<br>
So, it's up to you to find the best state(s) we should market our new prescription.<br>
It would be helpful to know If these aliens are hostile, Their diet, Their age. It’s up to you to clean up the data and report back.
 </P>
<br>
<H2> ASK </H2>
<h4> 1. Business task: </h4>
<p> To analyse the data about Aliens living in America and find a way to market ne prescription for hostile Aliens wanting to better assimilate. </p>

<h4> 2. Questions for the analysis:</h4>
<ul>
  <li> Is there any correlation between key characteristics and the alien hostality? </li>
<li> What is the distribution of hostile and non-hostile aliens in the whole population? </li>
  </ul>

<h2> PREPARE </h2>
<ul>
<li> The data was prepared by Ian Klosowicz, was published on Kaggle and contains three csv files:
<br>
aliens.csv, contains the name, gender, age, type, contact information of the aliens. <br>
details.csv, contains the favourite food, feeding frequency, and aggressivity of the aliens. <br>
location.csv, contains the city, state, country, and job of the aliens. <br>
 </li>
 <br>
 
<h4> ROCCC analysis </h4>
<ul>
<li> Reliability : HIGH – dataset has a moderately sized alien population and comes from reliable source. </li>
<li> Originality : HIGH </li>
  <li> Comprehensive : HIGH – There are only 2 files, the data is not repeating and the dataset not exceeding the limit of cells and columns taken by Excel </li>
<li> Current : HIGH – Data is up to date. Cited: HIGH – data collector and source is properly documented.. </li>
  <li> Cited : HIGH – data collector and source is properly documented.</li> </ul>
  <br>
  
<h2> PROCESS </h2>
<h3> Data selection & Cleaning</h3> <br>
<p>Firstly, I have merged all 3 files into 1 spreadsheet for easier access</p>
<ul>
  <li> I have created new tab with combined information that I will need by using VLOOKUP function and copied it onto new workbook.</li>
  <li> Data was checked for the duplicates and empty values. </li>
  <li>I have created multiple pivot tables with information about hostile aliens living in America for easier interpretation of the data..</li>
  <li>The information obtained by performing the 2 last steps was transferred to separate spreadsheet.</li>
  </ul>
  <br>
<p>49% of aliens in USA are hostile.
<br>
Firstly, I had a look at population of aliens categorised by their type and the hostility distribution to see if there is correlation
<br>
The distribution between hostile and non-hostile aliens of each type is pretty much even. There is also no access to how the population was changing across the years to forecast how these values may grow in the future. </p>
 <br> 
 <br>
<img src = "https://github.com/Ags-S/Iank-K-Aliens-in-America-study/blob/main/pivot_tables/Type.png"> 
 <br>
<p>By looking at the gender distribution I can see the leading genders among aliens are by far Female and male, but the spread on hostile and non-hostile in all groups is nearly even.</p>
<br>
<img src = "https://github.com/Ags-S/Iank-K-Aliens-in-America-study/blob/main/pivot_tables/Gender.png">
  <br>
<p> I had a look at distribution grouped by age range and once again there was no leading group to state correlation between age and hostility. The most aggressive aliens are amongst 300-350 years range with 8.45 % out of 16.80 % of population belonging to this age range. </p>
<br>
<img src = "https://github.com/Ags-S/Iank-K-Aliens-in-America-study/blob/main/pivot_tables/age.png">
<br>
<p> I had no luck in finding obvious correlation in preference of feeding frequency and hostality in comparison to non-aggressive aliens. Although most of aggressive individuals tend to feed once or never while the not aggressive ones lean towards once or daily feeding frequency. </p>
<br>
<img src = "https://github.com/Ags-S/Iank-K-Aliens-in-America-study/blob/main/pivot_tables/feeding.png">
<br>
<h2> SHARE</h2>
  <br>
  <p> After collecting and summarising the statistics for aggressive aliens I have created dashboard using pivot charts. </p>
  <br>
  <img src = "https://github.com/Ags-S/Iank-K-Aliens-in-America-study/blob/main/dashboard.png">
  <br>
  
  <h2> ACT</h2>
  <br>
 
<ul>
  <li> After concluding analysis of the alien data with no visible relationship between hostility and any of the characteristics provided, I would recommend Starting marketing campaigns in the top 3 most populated states: Texas, California and Florida. </li>
  <li> It would be also recommended to consider the launching the campaigns in the most populated cities by aggressive aliens outside of the above states: Washington (33.70%) and New York City (16.67%)
  <br>
  This could give feedback on improvement before introducing the nationwide marketing.</li>
  <li> The recommended strategy would be inclusivity towards all the genders and age ranges in marketing campaigns this will help accessing a much bigger group of potential customers as well as building customer trust and authenticity. With people around the world being more aware of discrimination and alienation of minority groups and more actively fighting for equal treatment the lack of diversity can make or break the brand. In recent research performed by YouGov over 60% of consumers taking part in the poll declared that they would more likely make a purchase from a brand that includes diversity in the advertisement. </li>
  </ul>
