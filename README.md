# Raxos

Minimized multi value consensus, half Raft half Paxos consensus.

## Why this repo?

Paxos is made for single value consensus and is relatively easy to learn and
understand, but it is hard to use directly in production.

Raft is multi value consensus and production ready but it involves too many
concepts for learning.

`Raxos` can be considered as a minimal implementation that support multi value
consensus, but without unnecessary complexity like Raft.

For a production use of Raft, refer to [Openraft](https://github.com/datafuselabs/openraft)
