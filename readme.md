# Control flow statments

# Problems

## control_flow001
Given 'z' an integer number.\
execute the following expression


<img src="https://latex.codecogs.com/svg.image?\left\{\begin{matrix}-1%20,%20\%20z%3C0\\%200,\%20z=0%20%20&%20%20&%20%20&%20%20\\%201,\%20z%3E0&%20%20&%20%20&%20%20&%20%20\\\end{matrix}\right." />.
 

**Example :**

**Input**: *z (int)*.\
**Output**: *Return answer (int)*.

|   **Input**   |   **Output**    |
|---------------|-----------------|
|4              |1                |
|-12            |-1               |
|0              |0                |

**Constraints:** 

 -10^9 < z, b < 10^9
## control_flow002
Given 'z' an integer number.\
execute the following expression


<img src="https://latex.codecogs.com/svg.image?\left\{\begin{matrix}z%3E0,%20\%20z=z-10\\z=0,%20\%20z=z%20%20\\z%3C0,%20\%20z=z+10&%20%20&%20%20&%20%20&%20%20\\\end{matrix}\right." />.
 

**Example :**

**Input**: *z (int)*.\
**Output**: *Return answer (int)*.

|   **Input**   |   **Output**    |
|---------------|-----------------|
|8              |-2               |
|-0             |0                |
|-5             |5                |

**Constraints:** 

 -10^9 < z, b < 10^9

## control_flow003


Given 'z' an integer number.\
execute the following expression


<img src="https://latex.codecogs.com/svg.image?\left\{\begin{matrix}z%3C99,%20\%20z=10\\z=0,\%20z=0%20\\z%3E99,%20\%20z=100\\\end{matrix}\right." />.
 

**Example :**

**Input**: *z (int)*.\
**Output**: *Return answer (int)*.

|   **Input**   |   **Output**    |
|---------------|-----------------|
|52             |10               |
|0              |0                |
|120            |100              |

**Constraints:** 

 -10^9 < z, b < 10^9


## control_flow004
Given 'z' an integer number.\
execute the following expression


<img src="https://latex.codecogs.com/svg.image?\left\{\begin{matrix}z%3C999,%20\%20z=z-100\\z=0,\%20z=0%20\\z%3E999,%20\%20z=z+100\\\end{matrix}\right." />.
 

**Example :**

**Input**: *z (int)*.\
**Output**: *Return answer (int)*.

|   **Input**   |   **Output**    |
|---------------|-----------------|
|50             |-50              |
|0              |0                |
|1600           |1700             |

**Constraints:** 

 -10^9 < z, b < 10^9









## control_flow005
Given 'z' an integer number.\
execute the following expression


<img src="https://latex.codecogs.com/svg.image?\left\{\begin{matrix}z%3C150,%20\%20z=z-50\\z=0,\%20z=0%20\\z%3E999,%20\%20z=z+20\\\end{matrix}\right." />.
 

**Example :**

**Input**: *z (int)*.\
**Output**: *Return answer (int)*.

|   **Input**   |   **Output**    |
|---------------|-----------------|
|40             |-10              |
|0              |0                |
|1000           |1020             |

**Constraints:** 

 -10^9 < z, b < 10^9
## control_flow006
Given 'z' an integer number.\
execute the following expression


<img src="https://latex.codecogs.com/svg.image?\begin{Bmatrix}%200%3Cz%3C10%20%20z=5%20\\%20-10%3Cz%3C0%20z=-5%20\\%20%20else\%20z=0%20\\\end{Bmatrix}" />.
 

**Example :**

**Input**: *z (int)*.\
**Output**: *Return answer (int)*.

|   **Input**   |   **Output**    |
|---------------|-----------------|
|8              |5                |
|0              |0                |
|-55            |0                |
|-3             |-5               |

**Constraints:** 

 -10^9 < z, b < 10^9
## control_flow007
Given 'z' an integer number.\
execute the following expression


<img src="https://latex.codecogs.com/svg.image?\begin{Bmatrix}%200%3Cz%3C10,\%20%20z=5%20\\%2010%3Cz%3C20,%20\%20z15\\%20%20-10%3Cz%3C0,\%20z=-5%20\\%20%20-20%3Cz%3C-10,\%20z=-15\\%20%20else\%20z=0%20\\\end{Bmatrix}" />.
 

**Example :**

**Input**: *z (int)*.\
**Output**: *Return answer (int)*.

|   **Input**   |   **Output**    |
|---------------|-----------------|
|18             |15               |
|8              |5                |
|0              |0                |
|-18            |-15              |
|-3             |-5               |

**Constraints:** 

 -10^9 < z, b < 10^9
## control_flow008
Given 'z' and 'b' integers number.\
execute the following expression


<img src="https://latex.codecogs.com/svg.image?\begin{Bmatrix}%20b%3Cz,\%20%20z%20\\%20z%3Cb,%20\%20b\\%20\end{Bmatrix}" />.
 

**Example :**

**Input**: *z, *b (int)*.\
**Output**: *Return answer (int)*.

|   **Input**   |   **Output**    |
|---------------|-----------------|
|18 , 7         |18               |
|8 ,7           |7                |


**Constraints:** 

 -10^9 < z, b < 10^9
## control_flow009
Given 'z' and 'b' integers number.\
execute the following expression


<img src="https://latex.codecogs.com/svg.image?\begin{Bmatrix}%20b%20-%20z%20%3Cz%20-%20b%20,\%20%20z%20\\%20z%20-%20b%20%3C%20b%20-%20z,%20\%20b\\%20\end{Bmatrix}" />.
 

**Example :**

**Input**: *z, *b (int)*.\
**Output**: *Return answer (int)*.

|   **Input**   |   **Output**    |
|---------------|-----------------|
|18 , 7         |18               |
|8 ,17          |17               |


**Constraints:** 

 -10^9 < z, b < 10^9 
## control_flow010
Given 'z' and 'b' integers number.\
execute the following expression


<img src="https://latex.codecogs.com/svg.image?\begin{Bmatrix}%20b%20:%20z%20%3Cz%20:%20b%20,\%20%20z%20\\%20z%20:%20b%20%3C%20b%20:%20z,%20\%20b\\%20%20else%200\end{Bmatrix}" />.
 

**Example :**

**Input**: *z, *b (int)*.\
**Output**: *Return answer (int)*.

|   **Input**   |   **Output**    |
|---------------|-----------------|
|18 , 2         |18               |
|2 ,18          |18               |


**Constraints:** 

 -10^9 < z, b < 10^9 
## control_flow010
Given 'z' integers number.\
execute the following expression


<img src="https://latex.codecogs.com/svg.image?\begin{Bmatrix}z\geqslant%2015,%20\%20z\\z\leqslant%20-15,%20\%20z+5\\else\%20z=0\end{Bmatrix}" />.
 

**Example :**

**Input**: *z, *b (int)*.\
**Output**: *Return answer (int)*.

|   **Input**   |   **Output**    |
|---------------|-----------------|
|18             |18               |
|2              |7                |


**Constraints:** 

 -10^9 < z, b < 10^9 
  