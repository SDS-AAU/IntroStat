# Gruppeopgave

Den opgave må gerne laves sammen med din gruppe.

I 'stocks.csv' finder du priser for Apple, Google, Ford, Vestas og SNP500 index.
Din opgave er at bruge kovarians of korrelation som værktøj til at se på sammenhæng i disse data.
I din gruppe skal der dindes 3 spørgsmål og besvares ved bruget af statistik og python

Brug dato til index når du læser ind
```python
pd.read_csv('stocks.csv', index_col='date')
````

Ellers:

```.diff() ``` 
funktionen i Pandas giver dig en nem mulighed at beregne ændringer fra dag til dag for alle variable.

Brug seaborn til at visualisere.

Du kan finde en rigtig god tutorial om det her:

- https://www.interviewqs.com/blog/py_stock_correlation
- https://alpaca.markets/learn/correlation-portfolio-python/
