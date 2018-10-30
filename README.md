# Paxos-with-Preemption
Implementation of Paxos with Preemption in the high level language of DistAlgo

Please find instructions below on running the DistAlgo code for Paxos code with preemption:

Folder Structure:

main.da
orig.da

among other files

-------------------------------------------------------------------------------------------------
main.da contains code for preemption.
-------------------------------------------------------------------------------------------------

To execute code:

For correctness testing:
 python.exe -m da main.da p a l n r d w tp tl c

For performance testing:
python.exe -m da main.da p a l n r d w tp tl p


where:

p - no. of proposers
a - no. of acceptors
l - no of learners
n - no of runs
r - loss rate
d - message delay
w - round wait time
tp - proposer timeout
tl - learner timeout
p - the character 'p'
c - the character 'c'
