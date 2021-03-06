---
type: talk
title: "Raft: Consensus for Rubyists"
speaker: Patrick Van Stee
room: Poinciana
day: Saturday
session: 1:50 PM
---

## About the speaker

Rubyist at Big Nerd Ranch, coffee snob, and distributed computing enthusiast.

## Talk Abstract

Consensus. It's not anything new. In fact, there have been great papers and discussions on the topic since the late 80's. But this year, a new consensus algorithm was written up in a paper titled, "In Search of an Understandable Consensus Algorithm". This is actually pretty rare in academia -- a paper, about a complex topic, that takes a systems approach to describing an algorithm. Not only do they give you a cheat-sheet on what RPC calls you'll need, but the entire algorithm is focused on being understandable first, which is something I think a lot of rubyists can appreciate.

I've always thought one of the major themes in the community was to focus on making software fun. Not only telling whimsical stories about foxes who like bacon or naming gems named after 90's cartoon characters, but making an effort to break problems down into small, digestible pieces and delivering them in the most practical way possible. Describing the Raft algorithm is a chance to get rubyists excited about what's going on in the distributed computing world and academia in general.

So what all do I want to teach everyone? The core concepts behind consensus, the three parts that make up the raft algorithm (consensus, state machine, and replicated log) with a toy implementation in ruby, and, most importantly, where to apply it in the real world (replacing redis, distributed configuration, and database failover). But I also have an ulterior motive, to use this unique paper to bridge the gap between academia and ruby, both making understandability more important in the education community and bringing more interesting complex projects to ruby.