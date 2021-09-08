# assignment2-GANTA
# RADHIKA GANTA
###### ARAKU-VIZAG
>Spread over an area of 36 km with an altitude ranging 600-900m above sea level, Araku Valley offers breathtaking views of the **waterfalls** and streams running through its valley depths. Thanks to its pleasant climate and beautiful hills, this valley is home to several coffee plantations and over 17 different tribal societies. You can swing by the Araku Tribal Museum to gain some insight into the lifestyles of these local tribes. If you have the opportunity, make sure to check out a performance of ‘Dhimsa’ dance, **a cultural event in the region full of expert movement and colorful costumes**.
# heading for the ordered list
1. Maryville
2. Kensas city
     1. kensas airport
     2. terminal
     3. aeroplane
3. India country
4. Hyderabad
5. Vizag- Araku
* home town
* movies
* food
* family
* relatives
* friends    
**[linktoAboutMe.md](AboutMe.md)**
---
# section about creating a table about food/drinks

Intro:
This table is about my favourite food items, drinks and locations where we can find them along with cost
|required|  item1  |  item2  |  item3  |  item4  |
|:------:|  :----: | :-----: | :------:| :-----: |
|food    |manchuria|  pizza  | pulihora| biryani |
|location| guntur  | vizag   | guntur  |hyderabad|
|  type  | spicy   | spicy   | spicy   | spicy   |
| amount | 10-20   | 15-25   |  5-10   | 20-30   |
---
# Heading about Quotes
>“Knowledge of what is does not open the door directly to what should be.”“The only thing that interferes with my learning is my education.”
>Author: *Albert Einstein*
***
# A New Section about Code Fencing
> In graph theory, the shortest path problem is the problem of finding a path between two vertices (or nodes) in a graph such that the sum of the weights of its constituent edges is minimized. Quick link to source.`Graphs Traversal/connected/shortest paths`<https://en.wikipedia.org/wiki/Shortest_path_problem>
```
vector<vector<int>> adj;  // adjacency list representation
int n; // number of nodes
int s; // source vertex

queue<int> q;
vector<bool> used(n);
vector<int> d(n), p(n);

q.push(s);
used[s] = true;
p[s] = -1;
while (!q.empty()) {
    int v = q.front();
    q.pop();
    for (int u : adj[v]) {
        if (!used[u]) {
            used[u] = true;
            q.push(u);
            d[u] = d[v] + 1;
            p[u] = v;
        }
    }
}
```
 Quick link to code :< https://cp-algorithms.com/graph/breadth-first-search.html>



