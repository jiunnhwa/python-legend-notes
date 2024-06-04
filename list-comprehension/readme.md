## Collection of List Comprehension code used.
List comprehension is one of the neat feature of Python, allowing concise expression of code, in a functional programming style.

#### Categories Count for Items
Grouping a list of items by it's category.
```
def calc_categories(items):
  fish = bird = 0
  fish = len([1 for n in items if n in ['shark','tuna']])           
  bird = len([1 for n in items if n in ['eagle']]) 
  return {'fish': fish,'birds': bird}

print(calc_categories(['shark','tuna','eagle']))  
```
