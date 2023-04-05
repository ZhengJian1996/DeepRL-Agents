

# Deep Reinforcement Learning Agents

这个仓库包含一系列使用Tensorflow编写的强化学习算法。这里的IPython笔记本是为了配合我在[Medium](https://medium.com/@awjuliani/simple-reinforcement-learning-with-tensorflow-part-0-q-learning-with-tables-and-neural-networks-d195264329d0#.4gyadb8a4)上发布的仍在进行中的教程系列而编写的。
如果您是新手，我建议阅读每个算法的附带文章来了解强化学习的相关知识。

该仓库当前包含以下算法：
* **Q-Table** - 使用表格实现的Q-learning算法，用于解决随机环境问题。
* **Q-Network** - 使用神经网络实现的Q-learning算法，用于解决与Q-Table相同的环境问题。
* **Simple-Policy** - 针对无状态环境（例如n臂赌博问题）的策略梯度方法的实现。
* **Contextual-Policy** - 针对有状态环境（例如上下文赌博问题）的策略梯度方法的实现。
* **Policy-Network** - 神经网络策略梯度代理的实现，可解决具有状态和延迟奖励以及两个相反动作的完整强化学习问题（例如CartPole或Pong）。
* **Vanilla-Policy** - 神经网络vanilla-policy-gradient代理的实现，可解决具有状态、延迟奖励和任意数量动作的完整强化学习问题。
* **Model-Network** - Policy-Network算法的扩展，包括一个单独的网络，用于建模环境动态。
* **Double-Dueling-DQN** - Deep-Q网络的实现，包括Double DQN和Dueling DQN的改进，以提高稳定性和性能。
* **Deep-Recurrent-Q-Network** - Deep Recurrent Q-Network的实现，可解决涉及部分可观察性的强化学习问题。
* **Q-Exploration** -包含多种行动选择策略（包括贪婪、随机、ε-贪婪、Boltzmann和贝叶斯Dropout）的DQN的实现。
* **A3C-Doom** - 异步优势演员-评论家算法（A3C）的实现。它利用多个代理共同改进策略。这个实现可以解决VizDoom等3D环境中的强化学习问题。
