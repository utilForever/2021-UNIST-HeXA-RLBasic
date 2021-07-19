# 2021-UNIST-HeXA-RLBasic

2021-UNIST-HeXA-RLBasic is the material(lecture notes, examples and assignments) repository for learning the basic knowledge of Reinforcement Learning course that I'll teach the club 'HeXA' at UNIST in the summer of 2021. Note that examples and assignments in this repository uses [PyTorch](https://pytorch.org/).

## Book

Deep Reinforcement Learning Hands-On - Second Edition (Packt, 2020)

![](https://static.packt-cdn.com/products/9781838826994/cover/smaller)

## Optional Readings

- Reinforcement Learning, An Introduction - Second Edition (MIT Press, 2018)
  - Korean: 단단한 강화학습 (제이펍, 2020)
- Reinforcement Learning (O'Reilly Media, 2020)
- 파이썬과 케라스로 배우는 강화학습 (위키북스, 2020)
- 바닥부터 배우는 강화 학습 (영진닷컴, 2020)

## Contents

- Week 1 (7/24)
  - What is Reinforcement Learning?
    - Supervised learning
    - Unsupervised learning
    - Reinforcement learning
    - RL's complications
    - RL formalisms
    - The theoretical foundations of RL
  - OpenAI Gym
    - The anatomy of the agent
    - Hardware and software requirements
    - The OpenAI Gym API
    - The random CartPole agent
    - Extra Gym functionality – wrappers and monitors
- Week 2 (7/31)
  - Deep Learning with PyTorch
    - Tensors
    - Gradients
    - NN building blocks
    - Custom layers
    - The final glue – loss functions and optimizers
    - Monitoring with TensorBoard
    - Example – GAN on Atari images
    - PyTorch Ignite
- Week 3 (8/7)
  - The Cross-Entropy Method
    - The taxonomy of RL methods
    - The cross-entropy method in practice
    - The cross-entropy method on CartPole
    - The cross-entropy method on FrozenLake
    - The theoretical background of the cross-entropy method
  - Tabular Learning and the Bellman Equation
    - Value, state, and optimality
    - The Bellman equation of optimality
    - The value of the action
    - The value iteration method
    - Value iteration in practice
    - Q-learning for FrozenLake
- Week 4 (8/14)
  - Deep Q-Networks
    - Real-life value iteration
    - Tabular Q-learning
    - Deep Q-learning
    - DQN on Pong
    - Things to try
- Week 5 (8/21)
  - Policy Gradients - an Alternative
    - Values and policy
    - The REINFORCE method
    - REINFORCE issues
    - Policy gradient methods on CartPole
    - Policy gradient methods on Pong
- Week 6 (8/28)
  - The Actor-Critic Method
    - Variance reduction
    - CartPole variance
    - Actor-critic
    - A2C on Pong
    - A2C on Pong results
    - Tuning hyperparameters
- Week 7 (9/4)
  - Asynchronous Advantage Actor-Critic
    - Correlation and sample efficiency
    - Adding an extra A to A2C
    - Multiprocessing in Python
    - A3C with data parallelism
    - A3C with gradients parallelism
- Week 8 (9/11)
  - AlphaGo Zero
    - Board games
    - The AlphaGo Zero method
    - The Connect 4 bot
    - Connect 4 results


## How To Contribute

Contributions are always welcome, either reporting issues/bugs or forking the repository and then issuing pull requests when you have completed some additional coding that you feel will be beneficial to the main project. If you are interested in contributing in a more dedicated capacity, then please contact me.

## Contact

You can contact me via e-mail (utilForever at gmail.com). I am always happy to answer questions or help with any issues you might have, and please be sure to share any additional work or your creations with me, I love seeing what other people are making.

## License

<img align="right" src="http://opensource.org/trademarks/opensource/OSI-Approved-License-100x137.png">

The class is licensed under the [MIT License](http://opensource.org/licenses/MIT):

Copyright &copy; 2021 [Chris Ohk](http://www.github.com/utilForever).

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
