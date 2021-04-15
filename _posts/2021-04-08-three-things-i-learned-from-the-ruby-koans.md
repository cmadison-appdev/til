---
layout: post
title: Three things I learned from The Ruby Koans
---

Here are (at least) three things I learned from [The Ruby Koans](http://rubykoans.com/):
1. I was caught off guard by the difference in function of the shovel operator (<<) vs the plus-equals operator (+=). The Koans posed the question as to why Ruby programmers tend to prefer the shovel operator. I assumed it was a matter of performance, which I confirmed looking through [Stack Overflow](https://stackoverflow.com/questions/4684446/why-is-the-shovel-operator-preferred-over-plus-equals-when-building-a). I was surprised to then find that each is actually a syntactic shortcut (which makes sense in hindsight).
2. I learned a fair bit about working with error messages, a topic that I've generally taken for granted up until now. The Koans that required manipulation of different types of errors took me the longest to complete by far. I found [this guide](https://rollbar.com/guides/ruby-raising-exceptions/) helpful when figuring out where to get started in the [official ruby docs](https://ruby-doc.org/core-3.0.0/index.html).
3. The Koans also helped sharpen my understanding of Ruby classes. Prior to these exercises, I did not fully appreciate the capabilities that classes bring to the language. I found [this guide](https://www.rubyguides.com/2019/02/ruby-class/) helpful as a refresher and [this blog post](https://tomoharutsutsumi.medium.com/how-to-use-nested-classes-rails-fe66f0301c3) helpful when working through the more complicated topics, such as nesting.
