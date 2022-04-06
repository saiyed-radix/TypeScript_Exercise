
## Exercise 6

- Define the `role` variable type which accept the only following roles as `super-admin`, `admin`, `user`.

- Create another function that accepts numeric array (like `[10, 20, 30, 40]`) values and return sum of all array element.

- In database previously we don't had field of role the leter on we have added role field, so fix the type of below program

```
interface User {
    name: string;
    age: number;
    occupation: string;
}
interface Admin {
    name: string;
    age: number;
    role: string;
}

export type Person = unknown;
export const persons: User[] /* <- Person[] */ = [
    {
        name: 'Max Mustermann',
        age: 25,
        occupation: 'Chimney sweep'
    },
    {
        name: 'Jane Doe',
        age: 32,
        role: 'Administrator',
    },
    {
        name: 'Kate Müller',
        age: 23,
        occupation: 'Astronaut',
    },
    {
        name: 'Bruce Willis',
        age: 64,
        role: 'World saver'
    }

];

export function logPerson(user: User) {
console.log(` - ${user.name}, ${user.age}`);
}
```
