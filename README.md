# MIU-CS568-Homework04
#  Homework 4: useState, useEffect
## Implement the HR system again as followings
1. Create a React project from scratch
2. Implement a class `Employee` which has properties: name, phone, position, salary, started.
3. Create a data file `employees.json` which contains the below data. You can import this data using the statement `import employess from './employees.json'` (I pretend that you put this file and your source file in the same directory).
[
  {
    "name": "John",
    "phone": "012345656",
    "position": "SWE I",
    "salary": 10000,
    "started": "07-20-2023"
  }
]
4. Implement the component `EmployeeDetail` which displays the information of an employee. This component will receive the data from `props` and then copy all this data to its internal state and display this state.
5. Impment the component `EmployeeList` which contains the list of `EmployeeDetails`. This component has an internal state which is the list of employees. When this component is mounted, this state will be assigned to the list of employees loading from the data file. When this component is unmounted, this state will be empty.
6. `EmployeeList` also contains a button `sort by name`. When users click on this button, this component shows the sorted list.

## Please submit this homework before 10:00 PM today
