# atlas

This is a playground for testing empirical properties of the Paxos consensus algorithm against the Raft consensus algorithm in Go.  Paxos implementation care of [Richard Knop](https://github.com/RichardKnop), Raft implementation care of [Piotr Tabor](https://github.com/ptabor).  More details to come as I become familiar with the properties of each and where we might expect divergence.

The intent is to enable future research into Raft, similar to how [The Paxos Register](https://www.cs.utexas.edu/~lorenzo/corsi/cs380d/papers/li07Paxos.pdf) successfully framed [Leslie Lamport](https://www.microsoft.com/en-us/research/people/lamport/)'s [classic paper](https://lamport.azurewebsites.net/pubs/paxos-simple.pdf).

Note original licenses remain intact for the bodies of work the algorithms have been extracted from.
