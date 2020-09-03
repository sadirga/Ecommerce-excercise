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
```python

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

✅ How many people have the job title of "Lawyer" ?
```python

```
__Expected Output__ :
![ss](/ss3.png)
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
✅

✅

✅

✅

✅

✅

✅

✅