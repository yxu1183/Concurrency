# Concurrency
### Operating System/Assignment-2: Created by [Dr. Trevor Bakker](https://github.com/trevorbakker-uta)

## Descirption
Prallel Programming to help professor schedule his office hours for two different classes- class A and B.

## Funtionality
* Use of multiple threads and parallel programming to impose several restrictions in office hours.
* No more than 3 students are allowed to simultaneously enter the professor's office.
* If students from class A are in the office, no students from class B are allowed to enter, and the other way around.
* Professor takes break after helping 10 students in a row.
* Professor will answer questions to atmost 5 consecutive students from a single class.
* If there is no student in the office and professor is not taking break, students should not be forced to wait.
* Code should not deadlock.
* Total students arriving to the office is read in from the file with three columns.
* First column is the number specifying whether the student is from class A(1) or B(2).
* Second column is the time between the arrival of a student and the previous student.
* Third column is the number of seconds student spends time with professor asking questions.

## Things I learned
* Handling multiple threads in an effective way.
* Correct use and placement of mutex. 
* Locking and unlocking the threads as per given conditions.

## Compilation Instructions
The application is builtin in an omega server at UTA.
In terminal:
```
gcc officehours.c -o office hours -lpthread
officehours.c sample.txt
```

## Acknowledgements
[Dr. Trevor Bakker](https://github.com/trevorbakker-uta) for providing small stub [program](https://github.com/CSE3320/Office-Hours-Assignment) to get started and his guidance throughout the assignment. 



