# Chapter 1: The Role of Group Action
1. What is **space**: We call a set with some structure a space. Like topological space( 拓扑空间 ), metric space( 矩阵空间 ).etc.
2. Quotient set: Think of if we do the action of quotient $12 / 3=4$, we put 12 items into four packs. Actually, in real, if we sorted some items by recognizing their same future, we are doing the same thing as quotient. So we call we make a set which some items with clear similarities, we call it **quotient set** and the elements of this quotient set are called **equivalence classes**. And this set of equivalent classes is called **quotient space**.
3. But it's not as easy as we construct a new set with set operations like union( 并集 ) and intersection( 交集 ). Because if we make group action by equivalence, it not like what we category some same thing, but need to define it  more precisely and maybe we use it intuitively.
4. Before we come into the true definition of it, here is an example of its result. The London is the equivalence class of all events along a straight line. Actually, we successfully created a new quotient space, the London from a dot in 3-dimension to a line in 4-dimension space.
5. So now we need to give some precious **definitions**.
6. **Equivalence relation**: On a set $X$, an equivalence relation is a relation, that concerns a subset $R subset X times X$, or we usually write instead of $$(x, x') ∈R:x ~x'$$
	-  Maybe we need to explain the symbols. $X times X$ means all possible ordered pairs, like $X= {1,2,3}$, $X times X= { (1,1)(1,2),(1,3),(2,1),dots}$
	-  $(x,x') in R$ means the same 
	-  What's more, the relation $~$ is an equivalence relation if it is:
	- **Reflexive( 自反性 )**: $x ~ x$ ( I must ensure i'm myself )
	- **Symmetric( 对称性 )** : $x ~x' <=> x' ~x$ ( If you and I are in the relation, I and you are in the relation, like lyouomoi, instead of kataomoi )
	- **Transitivity( 传递性 )**: $x ~y "and "y ~ z => x ~ z$ (A and B are in the relation, A and C are in the relation, then B and C must be category the same relation )
7. **Equivalence class**: We can easily define the equivalence class as $$[chi] := {x' : x' ∼ x, x ∈ X } ⊂ X$$
	- The $[chi]$ means the class, $chi$ is the symbol of this class.
	-  $:=$ means *is defined as*.
	- $x'$ means any element we want to check.
	- $:$ means it is *which Meet the following conditions*.
	-  $x' ~ x$ is the first condition, they are equivalent.
	- $x in X$ means it belongs the original huge space.
	-  $[chi] subset X$ means the class is the subset of the original space.
	- So the definition means all the elements which meet the condition, they can be called as Equivalence class.
8. **Quotient space**: $$X\/ ∼ := {[x] : x ∈ X }$ the $\/ ~$$ is the specific symbol of the quotient space.
	- The difference between the *class* and the *space* is that, the space treat all the class a single dot. 
9. We also have a canonical map, which is defined as $pi : X → X\/∼$
	- The pi is only the name of this map, which is standing for *Projection*
	- The rest means is the function from the space $X$ to space $X \/ ~$
	- We automatically get a built-in sorting machine ($\pi$) that takes any original point ($x$) and drops it into its corresponding box ($[x]$). This machine perfectly covers the whole new space with no empty boxes (surjective), and we call it the quotient map or projection.
10. Also, we can get the origin space from the quotient space by finding the *fiber*, it's easy to understand but the mathematical definition is too hard to understand.
11. In quotient space, we can do some outrages things, just like we can consider the different point though they have properties into the same thing.
12. Before we come into the notion of group, here are some other notion can be mentioned help us to understand the true group.
13. **Bijective map**. An action we can perfectly disturb it and recover it, just like a cube. Then we call the action like rotate the cube as **Transformations( 变换 )**
14. Then we can give the true definition of the **Group**. A group is a set $G$ and a binary operation.
	1. The first operation is  *associativity( 结合律 )*. $(a * b) * c = a * (b * c)$
	2. Then there must be the existence of a neutral element $e$ with: $e ∗ a = a ∗ e = a$
	3. And the existence of inverse elements: for every $a in G$ there exists an element $a^(-1) ∈ G$ such that $a ∗ a^(-1) = a^(-1) ∗ a = e$ . A group is abelian or commutative if $a ∗ b = b ∗ a$.
	4. A group is abelian( 阿贝尔群 ) or commutative if $a * b = b * a$.
15. But we usually use group to make some transformation, usually we use the **left group** action 