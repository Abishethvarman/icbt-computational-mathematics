# Section B: Set Operations - Detailed Answers

## 1. Venn Diagram Problem (Survey of 150 Students)

### Given:

* Total students: 150
* M = Music = 45
* D = Drama = 50
* A = Art = 60
* M \u2229 D = 15
* M \u2229 A = 20
* D \u2229 A = 18
* M \u2229 D \u2229 A = 8

Let:

* `x = M \u2229 D \u2229 A = 8`

### Region Calculations:

* M \u2229 D only = 15 - 8 = 7
* M \u2229 A only = 20 - 8 = 12
* D \u2229 A only = 18 - 8 = 10

Now find only-in regions:

* Music only = 45 - (7 + 12 + 8) = 18
* Drama only = 50 - (7 + 10 + 8) = 25
* Art only = 60 - (12 + 10 + 8) = 30

### i. Summary of Venn Diagram Regions

| Region                          | Count |
| ------------------------------- | ----- |
| Only Music                      | 18    |
| Only Drama                      | 25    |
| Only Art                        | 30    |
| Music \u2229 Drama (not Art)    | 7     |
| Music \u2229 Art (not Drama)    | 12    |
| Drama \u2229 Art (not Music)    | 10    |
| All three (M \u2229 D \u2229 A) | 8     |

### ii. Students in None of the Activities

* Total in any activity = 18 + 25 + 30 + 7 + 12 + 10 + 8 = **110**
* Students in none = 150 - 110 = **40**

### iii. Music Only

* Answer: **18 students**

### iv. Music and Drama but not Art

* Answer: **7 students**

### v. Drama and Art but not Music

* Answer: **10 students**

---

## 2. Set Questions on G, H, I, J

### Given:

* `G = {1, 3, 5, 7}`
* `H = { {1}, {3}, {5}, {7} }`
* `I = G \u222a {8} = {1, 3, 5, 7, 8}`
* `J = G \u222a {\u2205} = {1, 3, 5, 7, \u2205}`

### i. Is `{}` equal to `{\u2205}`?

* **No**. `\u2205` is the empty set, and `{\u2205}` is a set containing the empty set.

### ii. Subset Validations

* a. `\u2205 \u2286 G` \u2713 True
* b. `\u2205 \u2286 H` \u2713 True
* c. `{1} \u2286 G` \u2713 True
* d. `{1} \u2286 H` \u2717 False

### iii. Union of Sets

* `H \u222a I = { {1}, {3}, {5}, {7}, 1, 3, 5, 7, 8 }`
* `H \u222a J = { {1}, {3}, {5}, {7}, 1, 3, 5, 7, \u2205 }`

### iv. Intersection of G and H

* `G \u2229 H = \u2205`

### v. Set Differences

* `H \ G = { {1}, {3}, {5}, {7} }`
* `I \ G = {8}`
* `J \ G = {\u2205}`

---

## 3. Using Set Formula to Find n(A \u2229 B)

### Given:

* `n(A) = 10`, `n(B) = 25`, `n(A \u222a B) = 12`

### Formula:

```
n(A \u222a B) = n(A) + n(B) - n(A \u2229 B)
```

### Substitution:

```
12 = 10 + 25 - n(A \u2229 B)
=> n(A \u2229 B) = 35 - 12 = 23
```

### Answer:

* **n(A \u2229 B) = 23**
