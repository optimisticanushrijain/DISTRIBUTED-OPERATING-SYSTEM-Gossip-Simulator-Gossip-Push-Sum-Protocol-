# DISTRIBUTED-OPERATING-SYSTEM-Gossip-Simulator-Gossip-Push-Sum-Protocol

Goal: To determine the convergence of algorithms such as the Gossip Algorithm and Push-Sum Algorithm through a simulator based on actors written in Elixir. Full, Line, Random 2D Grid, 3D Torus Grid, HoneyComb, and Random Honeycomb topologies were implemented for both Push Sum and Gossip algorithms.

Technologies used: Elixir, Erlang, Atom

Group Members: 
(1) Anushri Jain (UFID: 8764-6425)
(2) Gurpreet Singh Nagpal (UFID: 0698-9051) 


To run the code execute following commands on a windows system
#gossip
mix run 100 3Dtorus gossip 
 
Here
100- Number of nodes
3Dtorus- Topology
gossip- Algorithm

#push-sum
mix run 100 3Dtorus push-sum

Code words for different topologies
"full"-> Full Network 
"rand2D"->Random 2D
"line"->Line 
"honeycomb"->HoneyComb 
"honeycombR"->Random HoneyComb
"3Dtorus"->3D Torus Topology 


For Gossip Algorithm:
In 3dtorus topology and randomhoneycomb topology, the largest network handled was of 15000 nodes while for the remaining topologies, we have observed till 2000 nodes.

For Push-Sum Algorithm:
In 3dtorus topology, the largest network handled was of 10648 nodes while for the remaining topologies, we have observed till 1000 nodes.



