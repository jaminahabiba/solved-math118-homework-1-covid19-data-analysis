Download Link: https://assignmentchef.com/product/solved-math118-homework-1-covid19-data-analysis
<br>
<strong>Problem 1                                                                                                                                                                     </strong>

Homework 1 considers a Covid-19 dataset which is published on <a href="https://github.com/owid/covid-19-data/tree/master/public/data">Github</a><a href="https://github.com/owid/covid-19-data/tree/master/public/data">.</a> Please download any document type that you prefer of the dataset from the links which are shown in Figure 1. The dataset is updated daily and

Figure 1: The complete dataset links

includes data on confirmed cases, deaths, hospitalizations, testing, and vaccinations as well as other variables of potential interest. The data set has the following basic columns:

<ul>

 <li>iso code: Short name of the country</li>

 <li>continent: The continent where the country exists</li>

 <li>location: The country name</li>

 <li>date: The date when the data about various variables are taken.</li>

</ul>

You are responsible to implement a program which reads the given dataset from the file and computes the data for the following questions. Any programming language that you prefer will be accepted. Putting comments on your functions that you implement is must. Each question must be appended to a file which is called ”output{.csv, .txt}”. The file contains the first 18 questions listed below. The 18th question will be written in this document.

<ol>

 <li>How many countries the dataset has?</li>

 <li>When is the earliest date data are taken for a country? Which country is it?</li>

</ol>

1

<em>– Homework #1                                                                                                                                                                                        </em>2

<ol start="3">

 <li>How many cases are confirmed for each country so far? Print pairwise results of country and total cases. 4. How many deaths are confirmed for each country so far? Print pairwise results of country and total deaths. 5. What are the average, minimum, maximum and variation values of the reproduction rates for each country? Table 1: The format of the output for the questions 5, 6, 7, 8, 9, 10, 12, 13.</li>

</ol>

<table width="335">

 <tbody>

  <tr>

   <td width="72">Country</td>

   <td width="71">minimum</td>

   <td width="74">maximum</td>

   <td width="59">average</td>

   <td width="59">variation</td>

  </tr>

  <tr>

   <td width="72">value</td>

   <td width="71">value</td>

   <td width="74">value</td>

   <td width="59">value</td>

   <td width="59">value</td>

  </tr>

 </tbody>

</table>

<ol start="6">

 <li>What are the average, minimum, maximum and variation values of the icu patients (intensive care unit patients) for each country?</li>

 <li>What are the average, minimum, maximum and variation values of the hosp patients (hospital patients) for each country?</li>

 <li>What are the average, minimum, maximum and variation values of the weekly icu (intensive care unit) admissions for each country?</li>

 <li>What are the average, minimum, maximum and variation values of the weekly hospital admissions for each country?</li>

 <li>What are the average, minimum, maximum and variation values of new tests per day for each country?</li>

 <li>How many tests are conducted in total for each country so far?</li>

 <li>What are the average, minimum, maximum and variation values of the positive rates of the tests for each country?</li>

 <li>What are the average, minimum, maximum and variation values of the tests per case for each country?</li>

 <li>How many people are vaccinated by at least one dose in each country?</li>

 <li>How many people are vaccinated fully in each country?</li>

 <li>How many vaccinations are administered in each country so far?</li>

 <li>List information about population, median age, # of people aged 65 older, # of people aged 70 older, economic performance, death rates due to heart disease, diabetes prevalence, # of female smokers, # of male smokers, handwashing facilities, hospital beds per thousand people, life expectancy and human development index.</li>

</ol>

Table 2: The format of the output for the question 17

<table width="390">

 <tbody>

  <tr>

   <td width="72">Country</td>

   <td width="78">population</td>

   <td width="82">median age</td>

   <td width="158"># of people aged 65 older</td>

  </tr>

  <tr>

   <td width="72">value</td>

   <td width="78">value</td>

   <td width="82">value</td>

   <td width="158">value</td>

  </tr>

 </tbody>

</table>

<ol start="18">

 <li>Summarize all the results that you obtain by the first 17 questions (except question 2).</li>

</ol>

Table 3: The format of the output for the question 18

<table width="422">

 <tbody>

  <tr>

   <td width="72">Country</td>

   <td width="46">q#3</td>

   <td width="46">q#4</td>

   <td width="68">q#5 min</td>

   <td width="70">q#5 max</td>

   <td width="65">q#5 avg</td>

   <td width="56">q#5 var</td>

  </tr>

  <tr>

   <td width="72">value</td>

   <td width="46">value</td>

   <td width="46">value</td>

   <td width="68">value</td>

   <td width="70">value</td>

   <td width="65">value</td>

   <td width="56">value</td>

  </tr>

 </tbody>

</table>

<ol start="19">

 <li>Comment the results based on your observations. Write your opinions about the reasons of increasing infection rates by giving examples from the results. Feel free to explain any situation that you observe.</li>

</ol>

More observations more opportunities will bring you for the second homework.

<em>(Solution) </em>(Write your observations here.)