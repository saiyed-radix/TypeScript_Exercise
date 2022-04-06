## Exercise 5

- Create read only interface for employee code only using typescript

       let emp = {
           empCode: 001,
           name: 'Ashwin',
           city: "Bhuj",
       }

- We can able to change the `name` and `city` but not able to change the `empCode` when I declare emp.empCode = 100;

- Create typescript function as per following:
  - There is one array like:
  ```
    const employees = [
        {name:'Manish',age:25,salary:15000},
        {name:'Yogesh',age:25,salary:30000},
        {name:'Deepak',age:25,salary:25000}
    ]
  ```
  - Write a typescript function that accept the array and returns array in transform like:
  ```
    [
        "your name is Manish, and you are 25 years old' and you earn 15000 per month",
        "your name is {name}, and you are {age} years old' and you earn {salary} per month",
        "your name is {name}, and you are {age} years old' and you earn {salary} per month",
    ]
  ```
