
# Hi there, see what I can do in Python!


```python
print('Hello World')
```

    Hello World


### The Python version I am using is Python 3.6


```python
# Checking the Python version 
import sys
print (sys.version)
```

    3.6.9 |Anaconda, Inc.| (default, Jul 30 2019, 19:07:31) 
    [GCC 7.3.0]



```python
# Converting all characters in string to upper case characters
A = "I used to intern at Big Ten Network for two years in Iowa City"
print("before upper:", A)
B = A.upper()
print("After upper:", B)
```

    before upper: I used to intern at Big Ten Network for two years in Iowa City
    After upper: I USED TO INTERN AT BIG TEN NETWORK FOR TWO YEARS IN IOWA CITY



```python
# Replacing a string (value) with another one
A = "The University of Iowa was the best"
B = A.replace('best', 'best place to be for 4 years')
B
```




    'The University of Iowa was the best place to be for 4 years'




```python
# Finding the index of a value or substring
Name = "One of the coolest places I lived was Chicago. I loved the seasons and the architecture. I visit as much as possible because majority of my friends still live there."
Name.find('Chicago')
```




    38



# Introducing Tuples (Table Sets)
<img src="https://img.nbc.com/sites/nbcunbc/files/images/2016/1/19/MDot-TheOffice-640x360-MP.jpg" width="700" align="center" />

**Favorite TV Shows**
<font size="1">
<table font - size:medium style="width:80%">
    <tr>
    <th>TV Show</th>
    <th>Released</th>
    <th>Network</th>
    <th>Streaming</th>
    <th>Nominations</th>
    <th>Seasons</th>
    <th>Genre</th>
    <th>orgin</th>
    <th>no. eps</th>
    /<tr>
    <tr>
    <td>The Office</td>
    <td>March 2005</td>
    <td>NBC Universal</td>
    <td>Peacock,Netflix</td>
    <td>Golden Globe, Emmy</td>
    <td>9</td>
    <td>Mokumentary,Sitcom</td>
    <td>USA</td>
    <td>201</td>
    /<tr>
    <tr>
    <td>FRIENDS</td>
    <td>September 1994</td>
    <td>NBC</td>
    <td>Peacock, HBO Max</td>
    <td>Emmy</td>
    <td>10</td>
    <td>Sitcom</td>
    <td>USA</td>
    <td>236</td>
    /<tr>
    <tr>
    <td>The Fresh Prince of Bel-Air</td>
    <td>September 1990</td>
    <td>NBC</td>
    <td>HBO MAX</td>
    <td>Golden Globe, Emmy</td>
    <td>6</td>
    <td>Sitcom</td>
    <td>USA</td>
    <td>148</td>
    /<tr>
    <tr>
    <td>Sex and The City</td>
    <td>June 1998</td>
    <td>HBO</td>
    <td>Amazon Prime, Hulu,/
    YouTube TV/
    HBO Now,Sling</td>
    <td>Golden Globe, Emmy, SAGA</td>
    <td>6</td>
    <td>Romantic Comedy,
    Comedy-Drama,
    Sex Comedy</td>
    <td>USA</td>
    <td>94</td>
    /<tr>
    
    
    
    
    
    
    
    
