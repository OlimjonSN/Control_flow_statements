# Control flow statments

# Problems

## control_flow001
Given 'a' an integer number.\
execute the following expression


<img src="https://latex.codecogs.com/svg.image?\left\{\begin{matrix}-1%20,%20\%20z%3C0\\%200,\%20z=0%20%20&%20%20&%20%20&%20%20\\%201,\%20z%3E0&%20%20&%20%20&%20%20&%20%20\\\end{matrix}\right." />.
 

**Example :**

**Input**: *a (int)*.\
**Output**: *Return answer (int)*.

|   **Input**   |   **Output**    |
|---------------|-----------------|
|4              |1                |
|-12            |-1               |
|0              |0                |

**Constraints:** 

 -10^9 < a, b < 10^9
## control_flow002
Given 'a' an integer number.\
execute the following expression


<img src="https://latex.codecogs.com/svg.image?\left\{\begin{matrix}z%3E0,%20\%20z=z-10\\z=0,%20\%20z=z%20%20\\z%3C0,%20\%20z=z+10&%20%20&%20%20&%20%20&%20%20\\\end{matrix}\right." />.
 

**Example :**

**Input**: *a (int)*.\
**Output**: *Return answer (int)*.

|   **Input**   |   **Output**    |
|---------------|-----------------|
|8              |-2               |
|-0             |0                |
|-5             |5                |

**Constraints:** 

 -10^9 < a, b < 10^9

## control_flow003
Given 'a' an integer number.\
execute the following expression


<img src="https://latex.codecogs.com/svg.image?\left\{\begin{matrix}z%3C99,%20\%20z=10\\z=0,\%20z=0%20\\z%3E99,%20\%20z=100\\\end{matrix}\right." />.
 

**Example :**

**Input**: *a (int)*.\
**Output**: *Return answer (int)*.

|   **Input**   |   **Output**    |
|---------------|-----------------|
|52             |10               |
|0              |0                |
|120            |100              |

**Constraints:** 

 -10^9 < a, b < 10^9