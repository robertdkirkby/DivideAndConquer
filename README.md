# DivideAndConquer
Some docs relating to Divide and Conquer algo as implemented in VFI Toolkit

The pdf very briefly explains the Divide and Conquer algorithm 'two-level monotonicity' which is used in VFI Toolkit.

There are a bunch of examples, with differing combinations of decision variable (d), markov exogenous state (z), and iid exogenous state (e).
All examples run the value function command twice, once with two-level monotonicity (by setting vfoptions.divideandconquer=1; and vfoptions.level1n=7; (7 is example, could by 5 or 15), and the second time with default (pure discretization). They then compare V with V2 and Policy with Policy2, showing that get the same solution.
