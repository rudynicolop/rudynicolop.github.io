---
title: "A Program Logic for Tree Borrows"
collection: publications
permalink: /publications/2025-09-19-tree-borrows
excerpt: 'We present a program logic for Tree Borrows capable of modularly reasoning about ghost trees in a higher order and concurrent setting under block-based memory.'
date: 2023-09-19
venue: 'Masters Thesis'
paperurl: 'http://rudynicolop.github.io/files/thesis.pdf'
citation: 'Rudy Peterson. 2025. A Program Logic for Tree Borrows. (September 2025). Retrieved from http://rudynicolop.github.io/files/thesis.pdf'
---

The Rust programming language, via its ownership model and borrow checker, provides strong memory safety guarantees for references and aliasing. Compilers take advantage of the guarantees of the borrow checker in order to justify powerful optimizations. Yet, the borrow checker is unable to reason about unsafe code and raw pointers therein, which may bypass Rust's type system and violate its safety guarantees, complicating compiler optimizations. Tree Borrows is a new formal aliasing model for Rust, which precisely articulates the contract unsafe Rust should abide by. Tree Borrows provides compilers with the justification to perform optimizations.

There are many program logics for Rust, but very few consider the aliasing model. This limitation of these program logics precludes one from safely composing safety and correctness proofs in the program logic with semantics-preserving proofs for the compiler. Thus we present a program logic for Tree Borrows capable of modularly reasoning about *ghost trees* in a higher order and concurrent setting under block-based memory. Our novel ghost tree construction unlocks powerful reasoning principles, including pointwise permission weakening, subtree deletion, and lateral separation. Our extensive *Lilac Tree* library buttresses our program logic, enabling these reasoning principles.

<pre> ```bibtex @mastersthesis{tree-borrows-separation-logic, author = {Peterson, Rudy}, title = {A Program Logic for Tree Borrows}, year = {2025}, month = {September}, school = {ETH Zurich}, type = {Master's Thesis}, url = {http://rudynicolop.github.io/files/thesis.pdf} } ``` </pre>
