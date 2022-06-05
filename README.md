
<link rel="stylesheet" href="style.css">

<!-- ...................................................................................................... first main div -->

<div class="card">
<br>
<h1><a href="https://github.com/MohamedSuwan/Weather-Data">Historical Weather Data Analysis</a></h1>
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
    <h4><b>Jupyter Notebook</b></h4> 
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
    <br>
    <br>
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

<h3>- 
On April 2021 more than half a billion Facebook user's data have been leaked.
around three million belong to Jordanians.
<br>
this repo was made to analyze the data, the data was in a good clean shape, just required some touches and modification.
<br>
the analysis will not show sensitive data like the emails or phone numbers, just a simple analysis like phone carrier,email domain,religion and gender.

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

<h3>- 
Solutions to problems “katas” from Codewars website, the solutions are written in
Python. relied on libraries and researching to come up with solutions.
<br>
Used mathematical theorems, generators, list comprehension, dictionaries, and one-
liners “Pythonic way”
    

</h3>
 <br>

<br>
    

    
</div>
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

<h3>scraping different elements from the web, cleaning and organizing the data in different ways and formats.
<br>
autoamtion like controling the computer, making a macro-like procedures.
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
<br>
                        
