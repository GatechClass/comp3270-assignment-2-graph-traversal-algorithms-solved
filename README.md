# comp3270-assignment-2-graph-traversal-algorithms-solved
**TO GET THIS SOLUTION VISIT:** [COMP3270 Assignment 2-Graph Traversal Algorithms Solved](https://mantutor.com/product/comp-3270-introduction-to-algorithms-solved-2/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115144&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP3270 Assignment 2-Graph Traversal Algorithms Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
Programming Assignment 2 – Graph Traversal Algorithms

1. Overview

Imagine you are given a dataset that represents a social network, where individuals are nodes in the graph, and their connections or friendships are represented as edges in an edge list. Your task is to analyze this social network to extract valuable insights. The dataset is in the form of an edge list. A visualization of the graph is shown below to help you.

Input:

An edge list file where each line represents a friendship connection between two individuals, e.g., “N_0, N_1.”

Output:

A report with a table such as the one below that documents the length of the shortest path between two individuals (or vertices) in this graph and the time taken to find the path between the two nodes. You must explore all pairs indicated in the table and complete the table below for each of the following algorithms. You should not include an entry if there are no paths between the two nodes. Use the graph above to identify if the nodes have paths connecting them.

Node 1 Node 2 BFS DFS

Distance Time (ms) Distance Time (ms)

N_0 N_1

N_0 N_2

N_0 N_3

N_0 N_4

N_0 N_5

N_0 N_6

N_0 N_7

N_0 N_8

N_0 N_9

N_0 N_10

N_0 N_11

N_0 N_12

N_0 N_13

N_0 N_14

N_0 N_15

N_0 N_16

N_0 N_17

N_0 N_18

N_0 N_19

N_0 N_20

N_0 N_21

N_0 N_22

N_0 N_23

N_0 N_24

You must explore the following algorithms. Breadth First Search (BFS) and Depth-First Search (DFS). For each of the node pairs in the table, you must run BFS/DFS with the start node as Node 1 and terminate the algorithm when Node 2 is reached. For example, to find the distance between N_0 and N_1, the start node is N_0. The algorithm terminates when N_1 is visited or “explored” by the algorithm. The distance is the total number of nodes visited by the algorithm before reaching the target vertex.

Your report should also have a brief description of the data structure that you will use to represent the graph and a short justification.

The goal of this assignment is to analyze how long it takes for BFS and DFS to reach nodes at different depths. Based on your experiments above, briefly answer the following questions with an example:

1. Suppose you want to find a path between nodes at a shallow depth to your start node. Would you use BFS or DFS?

2. Suppose that the end node is at a very large depth from the start node. Would you use BFS or DFS?
