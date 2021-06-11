# Some Python Code Snippets
## The second largest heading
###### The smallest heading


Loop through arrays, return with array:
```
def twoNumberSum(array, targetSum):
   resultArray=[]
   for i in range(len(array)-1):
      for j in range(i+1, len(array)):
	     if (array[i] + array[j]) == targetSum:
            return [array[i], array[j]]
   return []
```

- George Washington
- John Adams
- Thomas Jefferson