# Tunable Consistency in Riak

## Introduction to Riak
1. this applies to 1.0
## CAP Theorem overview
1. why do we have to sacrifice consistency?
## What is consistency?
1. Where does Riak fit in?
2. Tuning -- favoring A or C
## Examples of eventual consistency
1. caches
2. asynchronous replcation
3. DNS
## The knobs
1. N W/R
2. DW/RW
3. all, quorum, one (quorum) is default
4. allow_mult, last-write-wins