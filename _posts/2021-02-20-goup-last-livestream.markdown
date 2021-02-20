---
layout: post
title:  "Last live stream about microarchitectural/compiler stuff."
date:   2021-02-20 16:33:10 +0400
categories: low-level
---
We did livestream in the last month of 2020.
I told about (compiler and microarchitectural stuff) following topics:
 - Concepts of Shusha PL.
 - Microarchitectural implementations (CPU port contention/pressure,
   Reorder-buffer, RAT-Register allocation table etc.) and instruction
   decoding process (DSB/μop cache)
 - Store-to-load forwarding in microarchitecture and how compilers do
   optimization with this mechanism.
 - Persistent data structures and using of COW (Copy-on-write) on
   demanding to create new field.
 - Async/resume/suspend implementation and concept of goroutines. Also,
   how we can implement them with psuedocode.
 - Recursion and tail call optimization.

See live stream [here][stream-link].

[stream-link]: https://www.youtube.com/watch?v=4qStWyY4BmE
