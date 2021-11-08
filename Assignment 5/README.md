Meta learning and multi task learning
-
The Reptile algorithm was developed by OpenAI to perform model agnostic meta-learning. Specifically, this algorithm was designed to quickly learn to perform new tasks with minimal training (few-shot learning). The algorithm works by performing Stochastic Gradient Descent using the difference between weights trained on a mini-batch of never before seen data and the model weights prior to training over a fixed number of meta-iterations.

Neural-based multi-task learning has been successfully used in many real-world large-scale applications such as recommendation systems. With multi-task learning, we aim to build a single model that learns these multiple goals and tasks simultaneously. However, the prediction quality of commonly used multi-task models is often sensitive to the relationships between tasks. Multi-gate Mixture-of-Experts (MMoE), which explicitly learns to model task relationships from data. We adapt the Mixture-of-Experts (MoE) structure to multi-task learning by sharing the expert submodels across all tasks, while also having a gating network trained to optimize each task.

Avalanche is an end-to-end Continual Learning library based on Pytorch, born within ContinualAI with the unique goal of providing a shared and collaborative open-source (MIT licensed) codebase for fast prototyping, training and reproducible evaluation of continual learning algorithms. Avalanche can help Continual Learning researchers in several ways:
- Write less code, prototype faster & reduce errors
- Improve reproducibility
- Improve modularity and reusability
- Increase code efficiency, scalability & portability
- Augment impact and usability of your research products


Following are the different meta learning and multi task learning that I have performed for this assignment
1. [Few Shot Learning with Reptile MAML Algorithm](https://github.com/raghavadevarajeurs/cmpe-297-advanced-deep-learning/blob/main/Assignment%205/Avalanche_Continual_Learning.ipynb)
2. [Keras MoME Multi task learning Model](https://github.com/raghavadevarajeurs/cmpe-297-advanced-deep-learning/blob/main/Assignment%205/Keras_MMOE_Multi_Task_Learning_Model.ipynb)
3. [Avalanche Continual Learning Framework](https://github.com/raghavadevarajeurs/cmpe-297-advanced-deep-learning/blob/main/Assignment%205/Avalanche_Continual_Learning.ipynb)


References:
1. https://keras.io/examples/vision/reptile/
2. https://github.com/drawbridge/keras-mmoe/
3. https://github.com/ContinualAI/avalanche/
