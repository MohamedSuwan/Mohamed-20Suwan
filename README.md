
<link rel="stylesheet" href="style.css">

<!-- ...................................................................................................... first main div -->

<div class="card">
<br>
<h1><a href="https://github.com/MohamedSuwan/Weather-Data">Historical Weather Data Analysis</a></h1>
 
 <h3>
As an avid gardener I had to know the best time of year for agricultural activites, for example when grafting citrus trees, the best temperature at which citrus wounds heal is between (21°C and 29°C) according to fruitmentor.com<br>
<br>
knowing what the temperature and weather is like where I live gives me an idea in what I can or can't plant, graft, grow. I cant grow mangoes where i live because mangoes are freeze sensitive and require humid and warm weather all year round
  
 <br>
  <br>
  The following are the steps I took to make this project from aquiring the data to visualizing
 </h3>
 
<h3>
 <ul>
  <li>Web Scraping: scraping the historical hourly data from a website using
Selenium</li>
  <li>Data cleansing: cleaning, modifying using regular expression, and
converting the data into a CSV file for better handling</li>
  <li>Data Visualization: more cleaning and analysis of the data to get the
useful data for visualization and reporting using pandas and Matplotlib</li>
  <li>Power BI Dashboard: telling the story through visuals</li>
</ul> 
 

<br>
    </h3>

<!-- ....................................................................................... sub div 1.1 -->
  <center>  
      
<div class="cardimg">
  
  <iframe src="notebook/data Visualization.html" class="thumbnail" title="Weather Notebook" width="100%" height="350" style="border:0-moz-border-radius: 10px;border-radius: 10px;">
</iframe>
  <div class="container">
    <h4><b>Weather Analysis Jupyter Notebook</b></h4> 
      <h4><b>Hover or Click to Enlarge and Scroll Through the Notebook</b></h4>
  </div>
</div>
      <br>
    <br>
 <!-- ..................................................................................... sub div 1.2 -->
    
<div class="cardimg">
  <img src="wd.png" alt="Desktop" class="thumbnail" style="width:100%">
  <div class="container">
    <h4><b>Power BI Desktop View</b></h4> 
  </div>
</div>
    <br>
    <br>
      
 <!-- ...................................................................................... sub div 1.3 -->
      
      
 <div class="cardimg">
  <img src="wa.jpg" alt="Android" class="thumbnail" style="width:25%">
  <div class="container">
    <h4><b>Power BI Android View</b></h4> 
  </div>
</div>
    <br>
    <br>
    </center>
   
   
</div>
    

<br>
<br>
<hr>
<br>
<br>


<!-- ...................................................................................................... second main div -->

<div class="card">
    <br>
<h1><a href="https://github.com/MohamedSuwan/leaked-FB-data-analysis">Leaked Facebook Data Analysis</a></h1>

<h3>
On April 2021 the data of more than half a billion Facebook user from 106 countries have been leaked, around three million belong to Jordanians, the data was puublished on a hacking forum and Facebook said the data was old, from a previously reported leak in 2019. It has denied any wrongdoing, saying that the data was scraped from publicly available information on the site!
<br>
<br>
Although the sample is huge it doesn't reflect the real world in some aspects, males are two times the females and there's apattern for birthdays growing almost exponentially with birthdays that ocuured in 1995 being at the top, maybe there was a pattern in how the data was leaked.
 
 <br>
 Mohamed is the most common name, which is highly likely considering Mohamed is one of the most common names worldwide, most used carrier is Zain at 46.6%, what i find hard to believe is that Yahoo is the top email domain name.
 <br>
 <br>
This repo was made to analyze the data, the data was in a good clean shape mostly, just required some touches and modification.
<br>
 <br>
the exploratory analysis will not show sensitive data like the emails or phone numbers, just a simple analysis like phone carrier,email domain,religion and gender.

</h3>
 <br>

 <!-- ...................................................................................... sub div 2.1 -->

      <center>  
      
<div class="cardimg">
  
  <iframe src="notebook/Jordan FB analysis.html" class="thumbnail" title="Facebook notebook" width="100%" height="350" style="border:0-moz-border-radius: 10px;border-radius: 10px;">
</iframe>
  <div class="container">
    <h4><b>Facebook data analysis Notebook</b></h4> 
  </div>
</div>
      <br>
    <br>
    
  <!-- ...................................................................................... sub div 2.2 -->
          
   <div class="cardimg">
  <img src="images/FB.png" alt="Facebook BI" class="thumbnail" style="width:100%">
  <div class="container">
    <h4><b>Power Bi Dashboard</b></h4> 

  </div>
</div>
    <br>
    <br> 
    </center>

<br>
    </div>
   

 <br>
<br>
<hr>
<br>
<br>

 <!-- ...................................................................................................... third main div -->

 <div class="card">
    <br>
<h1><a href="https://github.com/MohamedSuwan/codewars">Python</a></h1>

<h3>
this repository contains solutions to problems “katas” from Codewars website, the solutions are written in
Python. relied on libraries and researching to come up with solutions.
<br>
 <br>
Used mathematical theorems, generators, list comprehension, dictionaries, and one-
liners “Pythonic way”
    <br>
 

</h3>
 <br>

<br>
  <!-- ...................................................................................... sub div 3.1 -->
<center>
 <div class="cardimg">
  <!-- HTML generated using hilite.me --><div style="background: #272822; overflow:auto;width:auto"><pre style="margin: 0; line-height: 125%"><span style="color: #f92672">import</span> <span style="color: #f8f8f2">re</span>
<span style="color: #66d9ef">def</span> <span style="color: #a6e22e">is_pangram</span><span style="color: #f8f8f2">(s):</span>
    <span style="color: #66d9ef">return</span> <span style="color: #f8f8f2">len(set(re</span><span style="color: #f92672">.</span><span style="color: #f8f8f2">findall(</span><span style="color: #e6db74">&quot;[a-z]&quot;</span><span style="color: #f8f8f2">,s</span><span style="color: #f92672">.</span><span style="color: #f8f8f2">lower())))</span><span style="color: #f92672">==</span><span style="color: #ae81ff">26</span>
</pre></div>
  <div class="container">
    <h4><b>Power BI Desktop View</b></h4> 
 
  </div>
 </div>
 <br>
  <!-- ...................................................................................... sub div 3.2 -->
  <div class="cardimg">
 <!-- HTML generated using hilite.me --><div style="background: #272822; overflow:auto;width:auto"><pre style="margin: 0; line-height: 125%"><span style="color: #66d9ef">def</span> <span style="color: #a6e22e">is_triangle</span><span style="color: #f8f8f2">(a,</span> <span style="color: #f8f8f2">b,</span> <span style="color: #f8f8f2">c):</span>
    <span style="color: #f8f8f2">tl</span><span style="color: #f92672">=</span><span style="color: #f8f8f2">(sorted([a,b,c]))</span>
    <span style="color: #66d9ef">if</span> <span style="color: #f92672">not</span><span style="color: #f8f8f2">(any(tl)</span><span style="color: #f92672">&gt;</span><span style="color: #ae81ff">1</span><span style="color: #f8f8f2">):</span>
        <span style="color: #66d9ef">if</span> <span style="color: #f8f8f2">tl[</span><span style="color: #ae81ff">0</span><span style="color: #f8f8f2">]</span><span style="color: #f92672">+</span><span style="color: #f8f8f2">tl[</span><span style="color: #ae81ff">1</span><span style="color: #f8f8f2">]</span><span style="color: #f92672">&gt;</span><span style="color: #f8f8f2">tl[</span><span style="color: #ae81ff">2</span><span style="color: #f8f8f2">]:</span>
            <span style="color: #ffb300">return</span> <span style="color: #66d9ef">True</span>
        <span style="color: #66d9ef">else</span><span style="color: #f8f8f2">:</span>
            <span style="color: #ffb300">return</span> <span style="color: #66d9ef">False</span>
    <span style="color: #66d9ef">else</span><span style="color: #f8f8f2">:</span>
        <span style="color: #ffb300">return</span> <span style="color: #66d9ef">False</span>
</pre></div>
   <div class="container">
    <h4><b>Power BI Desktop View</b></h4> 
  </div>
 </div>
 
  <br>
    
</div>

</center>
<br>
```python
import re
def is_pangram(s):
    return len(set(re.findall("[a-z]",s.lower())))==26
```
<h3>the code above checks if the given sentence is pangram or not -meaning does the sentence contain all the letters in a language- ; first the letters are converted to all lower case, then only the letters are taken from this sentence into a list, we can get unique values by using set, finally if the unique values count is 26 then it is a pangram.
    </h3>
```python
def is_triangle(a, b, c):
    tl=(sorted([a,b,c]))
    if not(any(tl)>1):
        if tl[0]+tl[1]>tl[2]:
            return True
        else:
            return False
    else:
        return False
```
<h3>
This code is a solution for the triangle inequality theorem which describes the relationship between the three sides of a triangle. According to this theorem, for any triangle, the sum of lengths of two sides is always greater than the third side
</h3>

<br>
<br>
<hr>
<br>
<br>
<!-- ...................................................................................................... fourth main div -->
<div class="card">
    <br>
<h1><a href="https://github.com/MohamedSuwan/Web-Scraping-Automation">Web Scraping and Automation</a></h1>

<h3>scraping different content,data and elements from the web quickly and efficiently, cleaning and organizing the data in different ways and formats.
<br>
 <br>
Autoamtion, controlling the computer, mouse, keyboard, making a macro-like procedures with minimal human intervention.
 <br>
 <br>
 The gif below is an axample of web scraping it is the execution of <a href="https://github.com/MohamedSuwan/Web-Scraping-Automation/blob/main/historical%20wether%20data.py">this</a> code, where the program collects all the data for a whole year.
 
    </h3>
 <br>
<center>
<!-- ...................................................................................... sub div 4.1 -->
<div class="cardimg">
  
  <img src="scraping.gif" alt="gif" class="thumbnail" style="width:100%">
  <div class="container">
    <h4><b>GIF Showing Web Scrapin In Action </b></h4> 
    
  </div>
 
</div>
    </center>
   
    <br>
    <br>
</div>
     



<br>
<br>
<br>
<h3>Thank you for your time  &#10084;&#65039;
<br>
                        
