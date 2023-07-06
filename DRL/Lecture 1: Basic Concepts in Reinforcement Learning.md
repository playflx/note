


> grid-world: Grid of cells:Accessible/forbidden/target cells, boundary![](/imgs/2023-07-06/8A6WD3XYNBiZVMYb.png)
> Forbidden area: At state s5, if we choose action a2, then what is the next state?
	> Case 1: the forbidden area is accessible but with penalty. Then, 
				s5 a2 −→ s6 
	• Case 2: the forbidden area is inaccessible (e.g., surrounded by a wall)
					s5 a2 −→ s5l
π(a1|s1) = 0  pi指策略，代表概率
![在action一直进行的情况下，使用一个折扣率，根据折扣率来判断结果值跟近处值有关还是远处值](/imgs/2023-07-06/r7mxq4mdagrLO4gl.png)
![MDP就是MDP本身，M代表Markov属性，具有历史无关性，dang](/imgs/2023-07-06/7I6mU0SeA495f5db.png)

<!--stackedit_data:
eyJoaXN0b3J5IjpbNzk5NDI4NjU2XX0=
-->