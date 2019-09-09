# Raft-Uppaal

This is a uppaal model for the leader election algorithm of Raft.
We check the five properties of our model as follows:
  - (Reachability) A candidate node can win a majority of votes.
  - (Liveness) A candidate node will be a Leader node eventually.
  - (Liveness) When the number of leader nodes is more than two, eventually the number of leader nodes will be one.
  - (Liveness) If more than half of nodes do not fail, eventually a candidate node will be a leader node.
  - (Safety) Deadlock would not happen.
  
![Raft-Uppaal](https://user-images.githubusercontent.com/1949515/64499079-75b18e80-d2f2-11e9-97d4-817267954219.PNG)
