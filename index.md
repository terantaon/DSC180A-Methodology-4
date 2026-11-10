## Chentao Gong c1gong@ucsd.edu
D38 Zhijian Liu
- **What is the most interesting topic covered in your domain this quarter?** \
The most interesting topic I think is the implementation of speculative decoding and how we use it to speed up models.
-  **Describe a potential investigation you would like to pursue for your Quarter 2 Project.** \
For next quarter I'm considering improve our project from the angle of quantization, so we can run a larger model.
- **What is a potential change you'd make to the approach taken in your current Quarter 1 Project?** \
The actual scenario of RL rollout is the generation of large batches in parallel, while the acceleration of speculative decoding diminishes as the batch size increases. I want to measure acceleration ratio as a function of batch size to see if we want another approach.
- **What other techniques would you be interested in using in your project?** \
Besides the techniques covered in our domain, I also would like to try prompt-lookup, layer skip and early exit. These technologies are orthogonal and can be superimposed.