# csor-w4231-homework-4-solved
**TO GET THIS SOLUTION VISIT:** [CSOR-W4231 Homework 4 Solved](https://www.ankitcodinghub.com/product/csor-w4231-homework-4-85-points-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119751&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSOR-W4231 Homework 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Homework Instructions.

1. For all algorithms that you are asked to “give” or “design”, you should

• Describe your algorithm clearly in English.

• Give pseudocode.

• Provide, with an explanation, the best (smallest) upper bound that you can for the running time. All bounds should be worst-case bounds, unless explicitly stated otherwise.

2. For every randomized algorithm that you design, you must either argue that it always terminates with the correct answer or analyze its success probability, that is, the probability it terminates with the correct answer. You must argue whether its running time is deterministic or a random variable and give the best upper bound that you can for it (if the running time is a random variable, you should upper bound its expectation). You are also encouraged to analyze the space required by your

algorithm.

• If a randomized algorithm is provided to you, follow carefully the instructions in the problem statement to analyze it.

4. You should submit this assignment as a pdf file to Gradescope. Other file formats will not be graded, and will automatically receive a score of 0.

5. I recommend you type your solutions using LaTeX. For every assignment, you will earn 5 extra credit points if you type your solutions using LaTeX or other software that prints equations and algorithms neatly. If you do not type your solutions, make sure that your handwriting is very clear and that your scan is high quality.

Homework Problems

1. (30 points) Consider a directed graph constructed by the following discrete-time process. You start with a single node v1. At every time step t with 1 &lt; t ≤ n, a single node vt is added to the graph, together with a single outgoing edge; the destination of the edge is a node chosen uniformly at random among the existing nodes in the graph.

Let G be the graph at the end of time step n.

(a) (15 pts) What is the expected number of edges entering node vj in G? Give an exact formula in terms of n and j, as well as an asymptotic expression using Θ notation.

(b) (15 pts) What is the expected number of nodes with no incoming edges in G?

2. (25 pts) Consider the following online auction system. There are n bidding agents; agent i has an integer bid bi &gt; 0. All bids are distinct. The bidding agents appear in an order chosen uniformly at random. Each agent proposes its bid bi in turn, and at all times the system maintains a variable bmax equal to the highest bid seen so far.

How many times do you expect to update bmax when this process is executed?

3. (30 points) In this problem, you will analyze a randomized algorithm that finds an item close enough to the median item of a set S = {a1,…,an} of n distinct numbers. Specifically, the algorithm finds an item ai such that at least n/4 items are smaller than ai and at least n/4 items are greater than ai.

Algorithm 1

Randomized Approximate Median (S)

1: Select an item ai ∈ S uniformly at random

2: rank = 1

3: for j = 1 to n do

4: if aj &lt; ai then rank = rank + 1

5: end if 6: end for

7: if bn/4c &lt; rank ≤b3n/4c then return ai

8: else return error

9: end if

(a) (5 points) What kind of randomized algorithm is Randomized Approximate Median(S) and why?

(b) (3 points) What is the running time of this algorithm?

(c) (8 points) What is the success probability of this algorithm?

(d) (14 points) Show how you can amplify (improve) the success probability of Randomized Approximate Median(S) to over 99% by running several independent executions of the algorithm. You should analyze the success probability and the running time of the resulting algorithm.

RECOMMENDED EXERCISES (do NOT return, they will not be graded)

1. Problem 24-3, part a. only, from your textbook (p. 679).

2. Problem 7-2 in the textbook.

3. Problem 7-4 in the textbook.

(If necessary, read pages 232-233 to refresh your memory on the definition of a stack.)

4. Given an undirected unweighted graph G = (V,E), we define a cut (S,V − S) to be a bipartition of the vertices. The size of a cut (S,V − S) is defined as the number of crossing edges, that is, edges with one endpoint in S and the other in V −S; we will henceforth denote the set of these edges by F. A global min-cut is a cut with minimum size.

The global min-cut is a natural robustness parameter of the graph: its size represents the smallest number of edges whose deletion disconnects the graph.

(a) (4 pts) Let (S∗,V − S∗) be a global min-cut in G of size k. Let F be the set of crossing edges of (S∗,V − S∗). Compute the probability that an edge in F is contracted in the first iteration of the algorithm.

(b) (8 pts) Derive a lower bound on the total number of edges in G, based on the fact that a global min-cut has size k.

(c) (4 pts) Derive an upper bound for the probability that a crossing edge in F is contracted in the first iteration of the algorithm using parts (a) and (b) above.

Algorithm 2

GlobalMinCut(G = (V,E))

1: // For each node v, maintain the set Cv of nodes that have been contracted into v 2: Initialize Cv = {v} for every v

3: if G has two nodes x and y then

4: return the cut (Cx,Cy)

5: else

6: Choose an edge e = (x,y) uniformly at random

7: // contract edge e

8: Replace e by a single new node vxy

9: Remove all edges between x and y from G

10: For any edge that has exactly one endpoint in {x,y}, update that endpoint to be vxy

11: Set Cvxy = Cx ∪ Cy

12: Let G0 be the resulting graph // note that G0 might be a multigraph

13: GlobalMinCut(G0)

14: end if

(d) (17 pts) Derive a lower bound for the probability that the algorithm successfully returns the cut (S∗,V − S∗) upon termination(using your answer in part (c). We will call this probability the success probability of the algorithm, and denote it by ps.

Hint: The algorithm will successfully return the cut (S∗,V − S∗) if no crossing edge in F is contracted in any recursive call before the last one. Let εi be the event that, in call i, the contracted edge is not an edge in F. First express the event that the algorithm successfully returns (S∗,V −S∗) upon termination in terms of the events εi. Then lower bound ps in terms of the probabilities of the εi’s.

(e) (2 pts) Derive an upper bound for the probability that the algorithm fails to return (S∗,V −S∗) upon termination. We will call this probability the failure probability of the algorithm, and denote it by pf.

(g) (10 pts) Give an upper bound on the number of global min-cuts in G.

Hint: Observe that what you computed in part (d) is the probability that the algorithm successfully returns a specific global min-cut (S∗,V −S∗). Let M be the number of global min-cuts in G, and let Ei be the event that Karger’s algorithm returns the global min-cut (Si,V − Si) for 1 ≤ i ≤ M. Now let E be the event that Karger’s algorithm returns any of the global min-cuts (Si,V − Si)’s. First, express E in terms of the Ei’s, and derive a lower bound for Pr[E]. Then use this lower bound to deduce an upper bound for M.
