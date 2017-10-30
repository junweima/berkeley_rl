# Tranfer Learning notes:

## "forward" transfer (train on one task, transfer to a new task)
	a) try it and hope for the best
	b) architectures for transfer: progressive networks
		- how to train source task: finetune with maximum entropy (soft Qlearning)
		- what architecture to use for transfer: progressive networks
	c) finetune on new task
	d) randomize source task domain (potential improvements for Taylor)
		- randomizing physical parameters (EPOpt: learning robust neural netowrk policies Rajeswaran et al.) etc
	
### What if we can peek at target domain?
	- better transfer through domain adaptation - confusion loss
	
	
## multi-task transfer (train on many tasks, tranfer to a new task)

	a) model-based reinforcement learning
		- construct a joint MDP
		- train each MDP separately, then combine policies
	b) model distillation
		- actor mimic policy distillation (maybe can work with c)
	c) contextual policies
	d) modular policy networks
		- separate neural network into robot specific and task specific parts


## multi-task meta-learning (learn to learn from many tasks)

	a) RNN-based meta-learning
	b) gradient-based meta-learning


	