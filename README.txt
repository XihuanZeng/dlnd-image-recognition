Note:

1. weight initialization: if use truncated_normal with default mean and stddev, the accuracy will stuck at 0.1, while change mean=0.001, stdev=0.05 solves the problem.
2. feed_dict naming: x:0, y:0 instead of x,y
