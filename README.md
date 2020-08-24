# Coronavirus Pandemic Analysis

The analysis addresses the misleading numbers of countries acclaiming their handle of the pandemic.\
The analysis led to a very interesting conclusion which is that if we took the ratio between the number of patients and total number of tests instead of
considering only the number of patients, we will find that the order of countries will definitely change. 
Many countries at the bottom of the list will be at the top and vice versa.

I called this ratio the P/T ratio.

<p>The code implements the following:</p>
<ul>
<li> Collects information from several datasets from keras.The information mainly represent the number of patients that are recorded daily for each country.</li>
<li> The code calculates the total number of patients till the most recent day.</li>
<li> The code divides the total number of patietns per the total number of tests.</li>
</ul>


<p>Dependencies:</p>
<ul>
<li> Pandas.</li>
<li> Numpy.</li>
</ul>

# Outcome
![Plot](https://github.com/AhmedFakhry47/CoronaVirus-DataAnalysis/blob/master/Plot.png)
