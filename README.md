# TypeScript_Exercise

# TypeScript Exercise

## Exercise 1

Create a typescript function which accept matrix as per Input and return the matrix as per Output.

Input:

```
[
[9, 8, 7],
[6, 5, 4],
[1, 2, 3],
]
```

Output:

```
[
[9, 6, 1]
[8, 5, 2]
[7, 4, 3]
]
```

## Exercise 2

Create a typescript function as per following:

- Function should accepts three parameters like `name`,`age` and `collegeName` with suitable type
- Function should print log based on following conditions

  - If `collegeName` is provided then print :

    - "Your name is {`name`}, your are {`age`} old you go to college."

  - If `collegeName` is not provided then print:
    - "Your name is {`name`}, your are {`age`} old, you don't go to college"
  - If `age` is null then print:
    - "Your age is null"
  - If `age` is undefined then print:
    - "your age is undefined"
  - If `age` is string then print:
    - "Invalid age"
  - If age is number then plus three to age and print: - "your current age is number
    you will complete your graduation at {`age` + 3}
    your graduation year will be {`age` + 3}

## Exercise 3

- Create a type script function which returns an async function which prints the following pattern after some interval of time

  ```
  *
  ***
  *****
  *******
  *********
  *******
  *****
  ***
  *
  ```

- The time interval and printing length of pattern should be passed in function arguments

## Exercise 4

Convert below Javascript function in TypeScript

```
//this function which x and y are number:

function logPoint(arg) {
    console.log("x = " + arg.x + ", y = " + arg.y);
}
logPoint({x: 10, y:20}): // this is the void function
```

## Exercise 5

Create read only interface for employee code only using typescript

```
   let emp = {
   empCode: 001,
   name: 'Ashwin',
   city: "Bhuj",
   }
```

- We can able to change the `name` and `city` but not able to change the `empCode` when I declare emp.empCode = 100;

## Exercise 6

- Define the `role` variable type which accept the only following roles as `super-admin`, `admin`, `user`.

- Create another function that accepts numeric array (like `[10, 20, 30, 40]`) values and return sum of all array element.
