# Iterators
## lazy
    no effect until consume
##.next()
    * consuming adaptors
    * move an item out of iter, so iter need mutable
## .sum()
    take the iterator ownership, but not take iter
## consuming adaptor + `collection`
    to create a vec by a vec
## .filter()
    closure with return true item to build new iterator
## .into_iter()
    create a iterator and takes ownership
## custom iterator
    implements  `impl Iterator for Custom`
## .zip()
    make pairs `Counter::new().zip(Counter::new().skip(1))`, When None stop
## .map()
    create a new iterator by each element