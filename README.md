# 14.3.4_Reduce_Exercises
14.3.4 section of Springboard program - Exercises

# Instructions from Springboard:
# ****Reduce****
### **extractValue**

Write a function called extractValue which accepts an array of objects and a key and returns a new array with the value of each object at the key.

```jsx
const arr = [{name: 'Elie'}, {name: 'Tim'}, {name: 'Matt'}, {name: 'Colt'}]
extractValue(arr,'name') // ['Elie', 'Tim', 'Matt', 'Colt']
```

### **vowelCount**

Write a function called vowelCount which accepts a string and returns an object with the keys as the vowel and the values as the number of times the vowel appears in the string. This function should be case insensitive so a lowercase letter and uppercase letter should count

```jsx
vowelCount('Elie') // {e:2,i:1};
vowelCount('Tim') // {i:1};
vowelCount('Matt') // {a:1})
vowelCount('hmmm') // {};
vowelCount('I Am awesome and so are you') // {i: 1, a: 4, e: 3, o: 3, u: 1};
```

### **addKeyAndValue**

Write a function called addKeyAndValue which accepts an array of objects and returns the array of objects passed to it with each object now including the key and value passed to the function.

```jsx
const arr = [{name: 'Elie'}, {name: 'Tim'}, {name: 'Matt'}, {name: 'Colt'}];

addKeyAndValue(arr, 'title', 'Instructor') //

[
  {title: 'Instructor', name: 'Elie'},
  {title: 'Instructor', name: 'Tim'},
  {title: 'Instructor', name: 'Matt'},
  {title: 'Instructor', name: 'Colt'}
]
```

### **partition**

Write a function called partition which accepts an array and a callback and returns an array with two arrays inside of it. The partition function should run the callback function on each value in the array and if the result of the callback function at that specific value is true, the value should be placed in the first subarray. If the result of the callback function at that specific value is false, the value should be placed in the second subarray.
