# orders
#### Orders 2 list from the minumum to the maxumum and leaves undefined values where a value is not present.
    o_{rders}\left(l_1,l_2\right)=\sum_{n=\left[\min\left(\min\left(l_1\right),\min\left(l_2\right)\right),...,\max\left(\max\left(l_1\right),\max\left(l_2\right)\right)\right]}^{\left[\min\left(\min\left(l_1\right),\min\left(l_2\right)\right),...,\max\left(\max\left(l_1\right),\max\left(l_2\right)\right)\right]}\left\{t_{otalOf}\left(l_1,n\right)\ge1:n,\ t_{otalOf}\left(l_2,n\right)\ge1:n\right\}

* Must be using intagers!
* Step of 1

# order
#### Orders a list from the minumum to the maxumum and leaves undefined values where a value is not present.
    o_{rder}\left(l\right)=\sum_{n=\left[\min\left(l\right),...,\max\left(l\right)\right]}^{\left[\min\left(l\right),...,\max\left(l\right)\right]}\left\{t_{otalOf}\left(l_1,n\right)\ge1:n\right\}

* Must be using intagers!
* Step of 1

# orderM
#### Orders a list from m to M on a given step s and leaves undefined values where a value is not present.
    o_{rderM}\left(l,m,M,s\right)=\sum_{n=\left[m,\ m+s,...,M\right]}^{\left[m,\ m+s,...,M\right]}\left\{t_{otalOf}\left(l,n\right)\ge1:n\right\}

* Can use any floating point number (given that it fits in the step and rage)
