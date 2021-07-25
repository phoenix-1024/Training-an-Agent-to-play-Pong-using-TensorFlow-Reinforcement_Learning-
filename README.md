# Training-an-Agent-to-play-Pong-using-TensorFlow-Reinforcement_Learning-
I implemented an Agent that adjusts its parameters and policies with gradients to get better rewards over time directly from experiences. This Model samples the expected action (moving a paddle up/down) from distribution when no gradients are available and high uncertainty is in place. We used the TensorFlow framework to make a sequential Neural network(Model) that accepts the current frame as input and tries to predict the best action from a set of possible actions. After we accumulate sufficient experience, We train the Model using Policy Gradient.
