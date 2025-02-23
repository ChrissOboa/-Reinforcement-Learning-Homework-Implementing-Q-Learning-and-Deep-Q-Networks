Professor Grace Yang, Georgetown University
Feedback by TA: Your TD(0) implementation has a problem—you used SARSA's algorithm.
You updated Q(s, a) and used it to select actions.
However, in TD(0), you don’t need to update the policy; you only need to update V(s).
