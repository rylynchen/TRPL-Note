# Closures

## A demo
    let f = |x| {}

## Can no type annotation
* parameters
* return values 
    
## multiple times call , parameters should be same type

## can access variable from the same scope

## capture environment value three ways
* FnOnce : take ownership, move to closure, only once
* FnMut : mutable borrow, can change value
* Fn : borrow, immutable

## force take ownership
    use `move` before paramenters