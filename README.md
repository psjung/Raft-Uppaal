# Raft-Uppaal

This is a uppaal model for the leader election algorithm of Raft.
We check the five properties of our model as follows:
  - (Reachability) It is possible for all the nodes to reach a Leader state together.
  - (Reachability) A candidate node can win a majority of votes.
  - (Liveness) A candidate node will be a Leader node eventually.
  - (Liveness) When the number of leader nodes is more than two, eventually the number of leader nodes will be one.
  - (Safety) Deadlock would not happen.
