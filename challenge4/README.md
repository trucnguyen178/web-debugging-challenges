### The purpose of this challenge is to assess your : 

#### toy problem debugging skills

This toy problem should work and give the correct result.

## Nguyen Thi Thanh Truc

### 1. Randomize the given array
- `randomNumber()` function returns values from 0 to 11, but the end point in the `slice()` method is 1, so it return undefined, cannot get first value from undefined.
- The `slice()` method does not change the original array, so the `while (arr.length >= 0)` runs indefinitely.
&#8594; Use `splice()` method instead of `slide()`, fix the loop to `while (arr.length > 0)`

### 2. Random the new puppy name
I added `console.log()` to the **name** and **name1** variables to print puppy name. 
As a result, **name** and **name1** have the same value because the `copyPuppy()` function changed the name of puppy.