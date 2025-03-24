Welcome to our “LaaR” (Loss as a Reward) digit classification project! Here, we train a Decision Transformer agent that dynamically moves a small window over an MNIST digit and uses the model’s classification loss as its reward signal. This approach encourages the agent to gather useful visual information step by step, leading to an accuracy of **86.6%** on the test set.  

Explore the repository to see how we:  
- Implement the moving window environment,  
- Integrate loss as a reward,  
- Apply a Decision Transformer to handle sequences of states and actions,  
- Incorporate curriculum learning for smoother training.  

Feel free to clone, experiment, and contribute!
