# Ecommerce Purchases Exercise


<hr>

### As usual, you need to import pandas into your notebook before begin this exercise

```python
import pandas as pd
```
- store your imported data into a variable `ecom`

```python
ecom = pd.read_csv(r'filepath') #filepath depends on where you save your csv file
```


✅ Check the head of the DataFrame

<hr>

```
ecom.head()
```
![ss1](/ss1.png)  


✅ How many rows and columns are there?
```python

```
__Expected Output__ : 
```python
(10000, 14)
```

✅ What is the average Purchase Price? ? 
```python

```
__Expected Output__ :  
```python
50.34730200000025
```

✅ What were the highest and lowest purchase prices?
```python

```
__Expected Output__ :  
```python
99.99
```
__Expected Output__ :  
```python
0
```

✅ How many people have English 'en' as their Language of choice on the website?
```python

```
__Expected Output__ :  
![ss](/ss2.png)  

<br/>

✅ How many people have the job title of "Lawyer" ?
```python

```
__Expected Output__ :  
![ss](/ss3.png)  

<br/>

✅ How many people made the purchase during the AM and how many people made the purchase during PM ? 
*(Hint: Check out value_counts()) 
```python

```
__Expected Output__ :  
```python
PM    5068
AM    4932
Name: AM or PM, dtype: int64
```

✅What are the 5 most common Job Titles?
```python

```
__Expected Output__ :  

```python
Interior and spatial designer    31
Lawyer                           30
Social researcher                28
Purchasing manager               27
Designer, jewellery              27
Name: Job, dtype: int64
```

✅ Someone made a purchase that came from Lot: "45 JN" , what was the Purchase Price for this transaction?

```python

```
__Expected Output__ :  

```python
8    59.54
Name: Purchase Price, dtype: float64
```

✅ What is the email of the person with the following Credit Card Number: 4926535242672853?  
```python

```
__Expected Output__ :  

```python
1234    bondellen@williams-garza.com
Name: Email, dtype: object
```

✅ How many people have American Express as their Credit Card Provider *and made a purchase above $95 ?  
```python

```
__Expected Output__ :  

```python
Address             39
Lot                 39
AM or PM            39
Browser Info        39
Company             39
Credit Card         39
CC Exp Date         39
CC Security Code    39
CC Provider         39
Email               39
Job                 39
IP Address          39
Language            39
Purchase Price      39
dtype: int64
```
✅ Hard: How many people have a credit card that expires in 2025?  
```python

```
__Expected Output__ :  

```python
1033
```

✅ Hard: What are the top 5 most popular email providers/hosts (e.g. gmail.com, yahoo.com, etc...)  
*Hint (Use loop or lambda expression to get the data) 
```python

```
__Expected Output__ :   

```python
hotmail.com     1638
yahoo.com       1616
gmail.com       1605
smith.com         42
williams.com      37
Name: Email, dtype: int64
```

### You Finished All The Exercise!

## GOOD JOB!
