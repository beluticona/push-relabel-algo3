# push-relabel-algo3

## Table of contents
* [General info](#general-info)
* [Setup](#setup)

## General info
Review and implementation of the push-relabel maximum-flow algorithm (Goldberg's version).
Presented as part of a project for Algorithms and Data Structures III.

There are two implementations in O(V3):
-relabel-to-back (fifo queue)
-push-to-front (linked list)

Input:
```
n m
v1 w1 c1
...
vm wm cm
```
Output:
```
max flux
```

## Setup
To run this project, to run one of the posible version v in {back, front} and sample.in:

```
$ make
$ ./push_relabel -a < sample.in
```



