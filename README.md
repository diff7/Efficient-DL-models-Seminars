# Efficient-DL-models-Seminars



## Lecture one
### Introduction:

- Which model is more suitable for a taks?
- Which data is more suitable for a task?
- How long does it take to find the best solution?
- An example with SeqNAS
-  Motivation type two computational effectiveness

- LLM
- Low resource devices-
- Trends

- How do we measure computational effectiveness?

- Hardware Software and inbetween 
- Hardware review
- CPU vs GPU 
- How they are connected
- OpenVINO
- ONNX
- TensorRT

### Seminar :
- Compute FLOPS and analyze memory-bound by plooting FLOPs vs Latenncey plots with different configurations

## HW1
Link to HW https://github.com/ZhMax/basic_sparse_quant/tree/main/notebooks

## Projects
### 1. Using deep learning representations during hyperparameters optimization.

Existing methods of hyperopt typically are a "block-box" optimization.
However, for neural networks, one can study internal representations. 
For neural representations, some comparison measures are established [1,2].
Your goal is to improve some of existing hyperopt methods with this idea.

1. Select a family of neural networks, i.e. different depth/width/layers or a hyperparams space (learning rate, decay, etc.)
2. Pick a datasets and develop a train/test pipeline.
3. Use this pipeline with some existing hyperopt method.
4. Invent a way how to incorporate similarity of neural representations and make hyperopt faster.

**Project evaluation:**
60%: 1,2,3
100%: 1,2,3,4

This is a research project, so I realize that improvement may not be obtained. 
A good grade will be provided for interesting experiments and a good report.
[1] Kornblith, S., Norouzi, M., Lee, H., & Hinton, G. (2019, May). Similarity of neural network representations revisited. In International conference on machine learning (pp. 3519-3529). PMLR.
[2] Barannikov, S., Trofimov, I., Balabin, N., & Burnaev, E. (2021). Representation topology divergence: A method for comparing neural network representations. arXiv preprint arXiv:2201.00058.

### 2. Neural architecture search for tabular DNN

Recently, deep learning methods outperformed traditional boosting-based methods on tabular data.
However, the improvement over boosting-based methods is small and not stable.
The idea of this project is to make the gap wider by using techniques of neural architecture search.

1. Select a DNN model for tabular data: e.g. FT-Transformer [1], SAINT [2], or simple MLP.
2. Invent a search space for this model.
3. Implement a differentiable NAS procedure like DARTS, GDAS, etc. 
4. Pick one or several tabular datasets and carry out experiments. 
5. One should see improvement in metrics over a default DNN model.

**Project evaluation:**
60%: 1,2,3
100%: 1,2,3,4

This is a research project, so I realize that improvement may not be obtained. 
A good grade will be provided for interesting experiments and a good report.

[1] Gorishniy, Y., Rubachev, I., Khrulkov, V., & Babenko, A. (2021). Revisiting deep learning models for tabular data. Advances in Neural Information Processing Systems, 34, 18932-18943.
[2] Somepalli, G., Goldblum, M., Schwarzschild, A., Bruss, C. B., & Goldstein, T. (2021). Saint: Improved neural networks for tabular data via row attention and contrastive pre-training. arXiv preprint arXiv:2106.01342.

### 3. Neural architecture search for tabular DNN via train-free NAS

The same as a previous project, but train-free NAS like [1] must be used.

[1] Chen, W., Gong, X., & Wang, Z. (2021). Neural architecture search on imagenet in four gpu hours: A theoretically inspired perspective. arXiv preprint arXiv:2102.11535.

### Project deliverables and grading: <br>

**Concise report with 4-6 pages (excl. appendices)**

■ Introduction, motivation and problem statement <br>
■ Related work and brief literature overview <br>
■ ML Methods and algorithms, proposed algorithm modifications, etc. <br>
■ Experiments / Discussion: details about (hyper) parameters, metrics and details, discussion of failures and successes, equations, results,  visualizations, tables, etc. <br>
■ Conclusion and directions for further research <br>
■ References, acknowledgements and contributions of each team member. <br>


**GitHub repo with project code and provided documentation - README.md**

■ Experiments should be reproducible <br>
■ Clear README to run the experiments should be provided, specify what outcome one should expect after running the code <br>
■ Code should follow common guidelines and be readable <br>
■ If you used other libraries or repositories please describe them and explicitly mention which modifications you made or where your code starts <br>



