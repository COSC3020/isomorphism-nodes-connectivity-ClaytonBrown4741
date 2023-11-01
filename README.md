[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12547980&assignment_repo_type=AssignmentRepo)
# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.  

**Answer:**  
First off, as we proved in the last isomorphism proof, two graphs must have the  
same number of nodes before we can even *consider* the possibility of them being  
isomorphic. Because A and B have the same amount of nodes, and we know that this is,  
indeed, a property that potentially isomorphic graphs must share, that means that we  
can focus on the next detail of the proof: The idea of all the nodes being completely  
connected in both graphs.  
Completely connected graphs (along with graphs that are not connected at all) hold a  
rather special property when it comes to isomorphism. Because every node has the same  
number of edges *and* these edges connect to every other possible node, then that means  
that it doesn't really matter what elements the bijective function that maps between A and B  
chooses as they are all essentially the same isomorphically speaking.  
This can be further supported by looking at the definition that was provided above. It  
states that isomorphic graphs must have a bijective function where $f: V_1 \rightarrow V_2$ such  
that $(u,v) \in E_1$ iff $(f(u),f(v)) \in E_2$. Looking at this definition, it becomes  
clear to see that it really doesn't matter what element is chosen, as every node has an equal amount  
of edges. *And* because these edges connect to every possible node, it means that there  
can't be any differing combinations between them. For instance, let's say we have two graphs  
called A and B that each have three nodes. We can't simply say that the graphs must  
have an equal number of edges per node, because that can lead to combinations that aren't isomorphic.  
An example of this is if A had the following edges: (1, 2), (2, 3), (3, 1), and B had these  
edges: (1, 2), (2, 1), (3, 2). As you can see, even though each node has only 1 edge originating  
from it, this is not isomorphic. However, if you were to change this so the graphs were both  
completely connected, then there would be no room for separate unique combinations, so  
the two graphs would *have* to be isomorphic.  
Now of course, a single case does not make a proof. This was simply done to illustrate my point  
when I said that there can be no differing combinations of edges per node if two graphs are both  
completely connected and have the same number of nodes.  
So, in the end, because the number of nodes is the same and the graph is completely connected  
(which rules out differing combinations of edges), that means that the proof must be true.  
(Please note that if anything is wrong with my reasoning or if I was too vague at some  
point, please don't hesitate to let me know what I did wrong and I will fix it right away.  
Also, I apologize if I talked a bit too much in some places. I just wanted to make sure I wasn't  
leaving anything out. Thank you).
