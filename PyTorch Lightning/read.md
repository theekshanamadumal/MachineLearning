PyTorch Lighting is a lightweight PyTorch wrapper for high-performance AI research that aims to abstract Deep Learning boilerplate while providing you full control and flexibility over your code. With Lightning, you scale your models not the boilerplate. Lightning makes coding complex networks simple.

* built on pure PyTorch
* Run your code on any hardware
* Performance & bottleneck profiler
* Model checkpointing
* 16-bit precision
* Run distributed training
* Logging
* Metrics
* Visualization
* checkpointing
* Early stopping
*  Without Lightning, the PyTorch code is allowed to be in arbitrary parts. With Lightning, this is structured.
*  As the project grows in complexity, your code won’t because Lightning abstracts out most of it.
*  You retain the flexibility of PyTorch because you have full control over the key points in training.
*  In Lightning you got a bunch of freebies such as a  progress bar

 ![image](https://github.com/theekshanamadumal/MachineLearning/assets/66960247/d058b302-56f9-4427-97be-8aa445e28909)
 

*  you also got a beautiful weights summary
 ![image](https://github.com/theekshanamadumal/MachineLearning/assets/66960247/0edfeda4-4fce-4404-a871-04bd0f98a591)

*  Out-of-the-box integration with popular logging/visualizing frameworks such as Tensorboard, MLFlow, Neptune.ai, Comet.ml and Wandb
*  PyTorch Lightning has minimal running speed overhead (about 300 ms per epoch compared with PyTorch)
*  
*  tensorboard logs
*  Lightning is known best for out of the box goodies such as TPU training
*  In Lightning, you can train your model on CPUs, GPUs, Multiple GPUs, or TPUs without changing a single line of your PyTorch code.
*  built in profiler that can tell you where the bottlenecks are in your training.
*  can also train on multiple GPUs at once without you doing any work (you still have to submit a SLURM job)


**Pytorch Lightning Alternatives
      TensorFlow
      Ignite 
       - Ignite is another high-level library made on top of PyTorch. It helps with neural network training. Like Lightning, it was also created for researchers. It requires less coding from pure PyTorch, which adds flexibility and simplicity to the interface. 



** PyTorch Lightning vs. TensorFlow
   - PyTorch Lightning is easier to use than TensorFlow for deep learning
   - The primary disadvantage of PyTorch Lightning is its lack of scalability. It is not suitable for large-scale projects, as it does not have the ability to scale up to multiple GPUs or distributed training. Additionally, it is not as mature as TensorFlow, so it may not have all the features and capabilities of TensorFlow.
   - The primary disadvantage of TensorFlow is its complexity. It requires a lot of code to build and train models, and it can be difficult to debug. Additionally, it is not as flexible as PyTorch Lightning, so it may not be suitable for all types of projects.


** When to use PyTorch Lightning
  - Researching and producing new architecture.
  - Looking for distributed and parallel training.
  - Looking for CPU, GPU, and TPU training. In PyTorch, you can easily change the hardware from the trainer itself.
  - It provides SOTA architecture so that you can tweak its settings for your own use. 
When not to use PyTorch Lightning

** When not to use PyTorch Lightning
  - If you don’t know PyTorch, then learn PyTorch first and then use Lightning
   

