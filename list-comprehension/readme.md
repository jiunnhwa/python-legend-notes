

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
