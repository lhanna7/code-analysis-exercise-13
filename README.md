# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (firstName, lastName, age){
  const person = {
    firstName: firstName,
    lastName: lastName,
    age: age,
  }

  return person
}
```

| Input | Output |
| ----- | ------ |
| Lauren, Hanna, 24      |  [firstName: "Lauren", lastName: "Hanna", age: "24"]     | 
|  Joe, Shmoe, 50     |  [firstName: "Joe", lastName: "Shmoe", age: "50"]       | 
|   John, Deer, 18    |  [firstName: "John", lastName: "Dear", age: "18"]        | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>It looks like this program allows you to take a couple of individual inputs and combine them into one output, person. This is probably something commonly used anytime you create an account somewhere and there's areas within your profile that are personalized. So entering the inputs, firstName, lastName, and age will be called upon by const person =. That way you can always call on person to get the output of firstName, lastName, and age.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
