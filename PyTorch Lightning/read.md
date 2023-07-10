1. Without Lightning, the PyTorch code is allowed to be in arbitrary parts. With Lightning, this is structured.

2. As the project grows in complexity, your code won’t because Lightning abstracts out most of it.

3. You retain the flexibility of PyTorch because you have full control over the key points in training.

4. In Lightning you got a bunch of freebies such as a  progress bar

 ![image](https://github.com/theekshanamadumal/MachineLearning/assets/66960247/d058b302-56f9-4427-97be-8aa445e28909)
 


5. you also got a beautiful weights summary

 ![image](https://github.com/theekshanamadumal/MachineLearning/assets/66960247/0edfeda4-4fce-4404-a871-04bd0f98a591)

 

6. tensorboard logs

7. checkpointing, and early stopping

8. Lightning is known best for out of the box goodies such as TPU training

9. In Lightning, you can train your model on CPUs, GPUs, Multiple GPUs, or TPUs without changing a single line of your PyTorch code.

10. built in profiler that can tell you where the bottlenecks are in your training.

11. can also train on multiple GPUs at once without you doing any work (you still have to submit a SLURM job)


