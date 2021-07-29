### Task 1 description

There is the 'file1.txt' with temporary statistics of the work of assessors on the same type of task.

#### Explanation of the file format:

- login - the login of the assessor;
- tid - id of the task under assessment (task id);
- Microtasks - the number of microtasks in one task;
- assigned_ts - task reserving time by the system reserved for the assessor;
- closed_ts - exact time of finishing work on the task

A task can consist of one or several microtasks. The task reserving time (assigned_ts) indicates the moment when the system appointed a certain assessor as the executor of this task. This moment may coincide with the start time of the assessor's work on the task, or may not coincide (the assessor can leave for tea, and then proceed to the task, the assessor can perform the previous task, while new ones are reserved for him).  

Suppose that the assessor receives N rubles in 30 seconds of his working time. What payment do you think is fair for the assessor to complete one microtask from this file?  

Describe in detail all the stages of your solution. Please attach the source code of the solution to the task or provide examples of parts of the code in the description of the solution.  

### Task 2 description
There is the 'file2.csv' with different assessors' assessments.

#### Explanation of the file format:

- login - the login of the assessor;
- uid - assessor’s id (user id);
- ocid - the id of the document under assessment (document id);
- jud - assessment of the assessor (judgment);
- cjud - correct judgment

The grades can take the value [0, 1], i.e. the task, which was done by the assessors, has a binary scale. 

Using the grade data, determine which assessors performed the worst on the assignment.

Describe in detail all the stages of your solution.
