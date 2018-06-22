---
layout: post
title:  "The order of an element of a group to a particular power"
date:   2018-06-22 
categories: math algebra group-theory
tags: math algebra group-theory proof
---

**Proposition 1.**
Let $$G$$ be a group and $$a \in G$$ such that $$\lvert a \rvert = n$$, then 
for any $$i \in \mathbb{N}$$, $$\lvert a^i \rvert = \frac{n}{(n,i)}$$.

**Proof.**
Let $$m = \lvert a^i \rvert$$, since 

$$(a^i)^{n/(n,i)} = (a^n)^{i/(n,i)} = 1$$

we have $$m \mid \frac{n}{(n,i)}$$. Now note that $$a^{im} = (a^i)^m = 1$$ thus
$$n \mid im$$. Then

$$ \frac{n}{(n,i)}(n,i) \mid \frac{im}{(n,i)}(n,i) $$

so $$ \frac{n}{(n,i)} \mid \frac{im}{(n,i)} $$. Now since

$$\Bigg( \frac{n}{(n,i)}, \frac{i}{(n,i)} \Bigg) = 1$$

by Euclid's lemma $$\frac{n}{(n,i)} \mid m$$. Hence $$\lvert a^i \rvert = \frac{n}{(n,i)}$$.
//