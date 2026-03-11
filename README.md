**Ethan Fricker**

I am a Mathematics PhD based in Chicago, specializing in reinforcement learning, high-performance computing, and algorithmic design. My work focuses on bridging the gap between rigorous mathematical theory and bare-metal computational efficiency.
Featured Project: The AlphaZero Architecture Series

I recently completed a three-part portfolio reconstructing the AlphaZero reinforcement learning algorithm from the ground up. This series demonstrates a full-stack progression from mathematical fundamentals to distributed, production-scale systems engineering.

**AlphaZero Project***

    -Built a complete neural network and Monte Carlo Tree Search (MCTS) entirely from scratch using pure Python and NumPy.
        
    -Implemented manual forward and backward passes for Dense, Conv2D, and Batch Normalization layers to demonstrate a ground-truth understanding of gradient calculus and backpropagation.
      
    -Transitioned to a full chess environment, tackling computational bottlenecks by writing custom C++ and CUDA kernels (conv2d.cu) compiled dynamically via NVCC.
        
    -Engineered zero-copy memory management using PyBind11 to pass raw memory pointers directly from CuPy to the C++ backend, eliminating Host-to-Device (H2D) transfer overhead.
   
    -Scaled the architecture to industry standards using PyTorch, focusing on throughput, distributed data pipelines, and hardware utilization.
        
    -Designed an asynchronous GPU orchestrator where CPU-bound MCTS actors write state tensors directly into OS-level shared memory buffers (.share_memory_()), bypassing Python multiprocessing overhead.
        
    -Handled the memory limits and engineering constraints of processing massive, compressed .zst PGN dataset dumps on a single RunPod instance.

**Skills & Technologies**

    -Mathematics: Probability, stochastic processes, gradient calculus, and optimization.

    -Machine Learning: PyTorch, Reinforcement Learning (MCTS, PUCT), ResNet architectures, and batched inference.

    -High-Performance Computing: C++, CUDA, memory management, parallelization, OS-level shared memory, and Numba JIT.

LinkedIn is probably the best place to contact me; don't hesitate to reach out. 
