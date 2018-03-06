# equal
#### Returns an array with all matching values(in same index) all other values are replaced with 0/0 (und)
    e_{qual}\left(l_1,l_2\right)=\sum_{n=\left[1,...,\operatorname{length}\left(l_1\right)\right]}^{\left[1,...,\operatorname{length}\left(l_1\right)\right]}\left\{l_1\left[n\right]=l_2\left[n\right]:l_1\left[n\right]\right\}

# notEqual
#### Returns an array of the first input and replaces all matching values(in same index) with 0/0 (und)
    n_{otEqual}\left(l_1,l_2\right)=\sum_{n=\left[1,...,\operatorname{length}\left(l_1\right)\right]}^{\left[1,...,\operatorname{length}\left(l_1\right)\right]}\left\{l_1\left[n\right]=l_2\left[n\right]:\frac{0}{0},l_1\left[n\right]\right\}

* Does not remove the element, just makes undefined and creates a new array.
