# 0x04. Typescript

## Description

TypeScript is a super set of JavaScript that adds optional static typing to the language. It is not a new programming language, but rather an extension of JavaScript that can be used in any JavaScript codebase.

---

+ [x] [0. Creating an interface for a student](./task_0/js/main.ts)

+ Copy the following configuration files (provided above) into the task_0 directory: package.json, .eslintrc.js, tsconfig.json, webpack.config.js

+ [x] [1. Let's build a Teacher interface](./task_1/js/main.ts)

+ Create a directory task_1 and copy these configuration files into this folder: package.json, tsconfig.json, webpack.config.js
**Example:
```
const teacher3: Teacher = {
  firstName: 'John',
  fullTimeEmployee: false,
  lastName: 'Doe',
  location: 'London',
  contract: false,
};

console.log(teacher3);

// should print
// Object
// contract: false
// firstName: "John"
// fullTimeEmployee: false
// lastName: "Doe"
// location: "London"
```
+ [x] [2. Extending the Teacher class](./task_1/js/main.ts)

+ Write an interface named Directors that extends Teacher. It requires an attribute named numberOfReports(number)

**Example:**
```
const director1: Directors = {
  firstName: 'John',
  lastName: 'Doe',
  location: 'London',
  fullTimeEmployee: true,
  numberOfReports: 17,
};
console.log(director1);

// should print
// Object
// firstName: "John"
// fullTimeEmployee: true
// lastName: "Doe"
// location: "London"
// numberOfReports: 17
```
+ [x] [3. Printing teachers](./task_1/js/main.ts)

+ Write a function printTeacher
  + It accepts two arguments firstName and lastName
   It returns the first letter of the firstName and the full lastName
**Example**:
```
printTeacher("John", "Doe") -> J. Doe
```
   + Write an interface for the function named printTeacherFunction.
+ [x] [4. Writing a class](./task_1/js/main.ts)

+ Write a Class named StudentClass

+ [x] [5. Advanced types Part 1](./task_2/js/main.ts)

+ Create the DirectorInterface interface with the 3 expected methods:
```
workFromHome() returning a string
getCoffeeBreak() returning a string
workDirectorTasks() returning a string
Create the TeacherInterface interface with the 3 expected methods:

workFromHome() returning a string
getCoffeeBreak() returning a string
workTeacherTasks() returning a string
Create a class Director that will implement DirectorInterface

workFromHome should return the string Working from home
getToWork should return the string Getting a coffee break
workDirectorTasks should return the string Getting to director tasks
Create a class Teacher that will implement TeacherInterface

workFromHome should return the string Cannot work from home
getCoffeeBreak should return the string Cannot have a break
workTeacherTasks should return the string Getting to work
Create a function createEmployee with the following requirements:

It can return either a Director or a Teacher instance
It accepts 1 arguments:
salary(either number or string)
if salary is a number and less than 500 - It should return a new Teacher. Otherwise it should return a Director
```
**Expected result:**:
```
console.log(createEmployee(200));
Teacher
console.log(createEmployee(1000));
Director
console.log(createEmployee('$500'));
Director
```

+ [x] [6. Creating functions specific to employees](./task_2/js/main.ts)

+ Write a function isDirector:

+ [x] [7. String literal types](./task_2/js/main.ts)

+ Write a String literal type named Subjects allowing a variable to have the value Math or History only.
Write a function named teachClass:

+ [x] [8. Ambient Namespaces](./task_3/js/main.ts)

+ Create a directory called task_3 and copy these configuration files into it: package.json, webpack.config.js, tsconfig.json.

+ [x] [9. Namespace & Declaration merging](./task_4/package.json)

+ Create a new directory task_4 and copy the above tsconfig.json and put this package.json in there

+ [x] [10. Update task_4/js/main.ts](./task_4/js/main.ts)

* create and export a constant cpp for Cpp Subjects
* create and export a constant java for Java Subjects
* create and export a constant react for React Subjects
* create and export one Teacher object cTeacher with experienceTeachingC = 10
* for Cpp subject, log to the console C++, set cTeacher as the teacher, call the two methods getRequirements and getAvailableTeacher and print the strings they return
* for Java subject, log to the console Java, set cTeacher as the teacher, call the two methods getRequirements and getAvailableTeacher, and print the strings they return
* for React subject, log to the console React, set cTeacher as the teacher, call the two methods getRequirements and getAvailableTeacher, and print the strings they return

+ [x] [11. Brand convention & Nominal typing](./task_5/js/main.ts)

* Create a directory task_5 and copy these configuration files into the root of task_5: package.json, tsconfig.json, webpack.config.js

---

## Author

[**Lawrence Adams**](./https://github.com/theclubfoot)
