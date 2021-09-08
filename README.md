# assignment2-Prathivada
# CHAKRADHAR PRATHIVADA
#### INDIA
My birth place is **INDIA**. I love my country because of its varied cultures and traditions . Some of the major cities are **Hyderabad**, Bangalore, mumbai etc.
***

### Directions to my favourite place

1. Book an uber from Maryville to Kansas international airport.
   1. Get in the car and go to kansas Airport.
2. Book a flight ticket to Hyderabad,India.
   1. Check in the bagggage at the counter.
   2. Board the flight to Rajiv gandhi International airport location in Hyderabad,India.
3.  Get down in the Airport in Hyderabad
   1. Collect the baggage in the counter.
   2. Leave the airport and go to your favourite place.
   * Food
   * Cricket kit 
   * Camera
   * Drone
   * Frisbee
   
   [about myself](Aboutme.md)

***
# FOOD/DRINK
Must try food /drinks:
   
| Food  | Place | price
|---|---|---|
| Chicken Biryani | Paradise Hyderabad  | 3.9$
| Arabian Mandi |  36@ Arabian kitchen | 4.8$
|Badam milk | Dilsukhnagar |  2$
| Triple choco chip thickshake | Thickshake factory | 6$

***
# Quotes I like

> All is well. *-Rancho*

> Life is a journey not a destination. *-Ralph Waldo Emerson*

> Die with memories not with dreams. *-Alex benny*

***
# Code fencing
> Breadth-first search (BFS) is an algorithm for searching a tree data structure for a node that satisfies a given property. It starts at the tree root and explores all nodes at the present depth prior to moving on to the nodes at the next depth level. Extra memory, usually a queue, is needed to keep track of the child nodes that were encountered but not yet explored.

[BFS](https://en.wikipedia.org/wiki/Breadth-first_search)

```vector<vector<int>> adj;  // adjacency list representation
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


[CODE](https://cp-algorithms.com/graph/breadth-first-search.html)






