---
title: "Getting Started with Kotlin"
date: 2026-11-07 09:00:00 +0530
categories: [Android, Kotlin]
tags: [tutorial, beginners]
---

 

## Initialisations 

## String ops
##### String iteration

    val str = "abc"
    val ch: Char = str[0]

##### lowercase string to uppercase
    "abc".uppercase() // "ABC"
##### uppercase string to lowercase
    "ABC".lowercase() // "abc"

## Character ops

##### Covert Char to ascii
    'a'.code // 97
##### Covert ascii to Char
    65.toChar() // 'A'
##### lowercase char to uppercase
    'a'.uppercase() // 'A'


## Heap ops
##### Initialisation
    val pq = PriorityQueue<Int>(compareBy{it}) // Ascending order
    val pq = PriorityQueue<Int>(compareByDescending{it}) // Descending order
    val pq = PriorityQueue<Pair<Int, Int>>(compareBy{it.first}) // Ascending wrt first



 
