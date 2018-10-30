Submission for:
Pavan Kottapalli
SBU ID: 112027511
CSE535 Asynchronous Systems

Please find instructions below on running the DistAlgo code for Paxos code with preemption:

Folder Structure:
	a. Zip file Pavan_Kottapalli_112027511.zip containing:
		i. 		README.txt
		ii. 	correctness_main.txt
		iii.	correctness_orig.txt
		iv.		main.da
		v. 		orig.da
		vi.		Pavan_Kottapalli_112027511_A4.pdf
		vii.	times_main.txt
		viii.	times_orig.txt
-------------------------------------------------------------------------------------------------
main.da contains code for preemption.
-------------------------------------------------------------------------------------------------
The files ii, iii, vii and viii are for checking correctness and performance run values. Please clear them periodically if their sizes grows too large.

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