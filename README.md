# Time-Table-Generator
A customized heuristic solution to the famous TimeTable problem involving the concepts of
combinatorial optimization using Genetic Algorithms and Fuzzy Logic methodologies in the
form of an application. This would be made with the intention of actually reducing the time
taken by our school for the timetable-making process.
The timetabling problem involves fixing a sequence of classes between professors and
students in a given period, satisfying a set of different constraints. The constraints can be
categorized as hard or soft based on their priorities. As the algorithm will be customized for
the School of Computer Science and Engineering, We would survey our faculties to get an
overview of the required constraints. This can also be further improved by making it
generalized for broader userbase.

## Project Objectives
The following are the objectives of this project:-
– 1. Minimizing the conflicts between constraints in Time-Table scheduling.
– 2. Automating and Optimizing the Time-Table generation processes cus-
tomized for the School of Computer Science and engineering, XIM Uni-
versity with the purpose of reducing the time taken in the manual process.
– 3. Hard Constraints or any other critical constraints should not be viol-
ated and soft constraints should be applied as much as possible.
– 4. Creating a usable GUI to provide input and view the time-tables.


Courses.csv and Falculty.csv are the inputs and Year 1,2,3,4 are some example outputs.
### Input :- Courses.csv For every batch the ”Courses.csv” file should contain

– Course ID - The respective ID of the courses.<br>
– Course Name - The respective name of the course <br>
– Course Code - The respective code of the course <br>
– Semester - The Semester to which the course is taught to <br>
– Faculty ID - The respective ID’s given to the faculties. <br>
– NOCW - Number of credit hours of the course <br>
– Type - Lab or Lectures.<br>
∗ Workshops are considered as lectures as they are conducted in classrooms
itself.<br>

### Input :- Faculty.csv For every faculty the ”Faculty.csv” file should contain

– ID - The respective ID of the faculty. <br>
– Faculty Name - The respective name of the Faculty <br>
– Visiting - If the corresponding Faculty is a visiting faculty or not <br>
The input would be taken with the help of a form format.
• Output : Four tables, One for each batch, satisfying some predefined con-
straints in the form of a structured timetable.<br>

### Constraints: The constraints for the timetable problem are as follows.
– A time slot cannot have more than one course of the same batch. <br>
– Courses taught by a single faculty cannot exist simultaneously in the <br>
same time slot for different batches as a faculty member cannot take 2
courses at the same time. <br>
– Lab classes should not clash within batches. <br>
– If one course has 2 time-slots in a day then the slots have to be consec-
utive.<br>
– Number of occupied time slots in a day cannot be more than 5.
– Lab classes are held in the second half. <br>
– Consecutive days cannot have the same courses. <br>
The constraints are ordered in the decreasing order of priority. <br>

![image](https://github.com/PandaSupremacy/Time-Table-Generator/assets/72810835/328cc010-2908-46cb-a90a-b4aab07e9e91)
![image](https://github.com/PandaSupremacy/Time-Table-Generator/assets/72810835/9f979c3a-e852-4cd2-878a-a52bad282b98)
![image](https://github.com/PandaSupremacy/Time-Table-Generator/assets/72810835/65f09397-ce4c-4665-b696-0d7467eabe0c)




