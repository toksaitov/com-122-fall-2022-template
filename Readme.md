# COM-122, Fall 2022: Course Directory

Here all the lab sources, online judges solutions, and projects should be stored
and submitted by the student to their private course repository. The repository
MUST be shared with the instructor and only with him. The student MUST commit
and push to GitHub periodically after finishing work on every lab problem, OJ
solution, or part of a project. The repository will be regularly checked by the
instructor or an automated script and graded. Ensure to keep the directory in
good order. Ensure to precisely follow the naming convention for directories,
files, and classes. Your grade will be lowered if the naming is incorrect and
the autograder fails to test your work. Do not share your work, and don't
plagiarize other people's work. Your repository will be checked for plagiarism
from time to time. In a case of a severe infraction, you will be reported to the
registrar's office and automatically fail the course.

## Checkpoint Grading

Your instructor will announce a periodic review of your work. You will be
awarded up to the following number of points for such checks:

* __Labs__: 10 point
* __Online Judges Solutions__: 10 points
* __Project 1__: 4 points
* __Project 2__: 4 points

In total, all the checkpoints cost *28 points* of your final grade.

## Required Software

Install the following software on your machine:

* [Adoptium Temurin JDK 17](https://adoptium.net/en-GB)
* [IntelliJ IDEA Community](https://www.jetbrains.com/idea/download)
* [Git SCM](https://git-scm.com)

After that, clone this repository to your computer with IDEA through Git.

## Required Libraries

The directory contains libraries extracted from the [Processing](https://processing.org)
project, distributed under the LGPL license. You will most likely need them in
Project 2.

## Code Style and Formatting

Points may be removed for not following the Java common stylistic traditions
(outlined [here](https://www.oracle.com/java/technologies/javase/codeconventions-namingconventions.html))
or your IDE's default code formatting rules.

## Naming Convention

Name files, directories and commits correctly. You may lose points if you do not
follow the naming rules.

### Commit Messages

Commit messages should briefly explain the nature of change. In addition,
project commits may contain a detailed commit description on a separate line.

#### Examples

```
Finish Problem 1 in Lab 1
Fix formatting in Problem 1 in Lab 1
Remove unnecessary files from Problem 1 in Lab 1
Finish Online Judge Problem 1 from <Name of the Online Judge System>
Add UI to select levels in Project 2
...
```

### Module Names

You MUST use the following names for project modules:

* `lab-01`
* `lab-02`
* `lab-03`
* `lab-04`
* `lab-05`
* `lab-06`
* `lab-07`
* `lab-08`
* `project-01`
* `project-02`
* `oj-midterm`
* `oj-final`

### Lab and Online Judge Solution File Names

Your source file names MUST be named `Problem<NN>.java` where NN is the problem
number with the leading 0 in front if less than one digit is used.

#### Example

```bash
Problem01.java
Problem02.java
...
```

### Project File Names

File naming for projects will be explained in the project requirements.
