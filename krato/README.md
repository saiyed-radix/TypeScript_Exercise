
## Exercise 4

- Convert below Javascript function in TypeScript
  ```
    //this function which x and y are number:

    function logPoint(arg) {
        console.log("x = " + arg.x + ", y = " + arg.y);
    }
    logPoint({x: 10, y:20}): // this is the void function
  ```

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