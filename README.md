# Sutskever 30 - Complete Implementation Suite

**Comprehensive toy implementations of the 30 foundational papers recommended by Ilya Sutskever**

[![Implementations](https://img.shields.io/badge/Implementations-27%2F30-brightgreen)](https://github.com/pageman/sutskever-30-implementations)
[![Coverage](https://img.shields.io/badge/Coverage-90%25-blue)](https://github.com/pageman/sutskever-30-implementations)
[![Python](https://img.shields.io/badge/Python-NumPy%20Only-yellow)](https://numpy.org/)

## Overview

This repository contains detailed, educational implementations of the papers from Ilya Sutskever's famous reading list - the collection he told John Carmack would teach you "90% of what matters" in deep learning.

**Progress: 27/30 papers (90%) implemented!**

Each implementation:
- ✅ Uses only NumPy (no deep learning frameworks) for educational clarity
- ✅ Includes synthetic/bootstrapped data for immediate execution
- ✅ Provides extensive visualizations and explanations
- ✅ Demonstrates core concepts from each paper
- ✅ Runs in Jupyter notebooks for interactive learning

## Quick Start

```bash
# Navigate to the directory
cd sutskever-30-implementations

# Install dependencies
pip install numpy matplotlib scipy

# Run any notebook
jupyter notebook 02_char_rnn_karpathy.ipynb
```

## The Sutskever 30 Papers

### Foundational Concepts (Papers 1-5)

| # | Paper | Notebook | Key Concepts |
|---|-------|----------|--------------|
| 1 | The First Law of Complexodynamics | ✅ `01_complexity_dynamics.ipynb` | Entropy, Complexity Growth, Cellular Automata |
| 2 | The Unreasonable Effectiveness of RNNs | ✅ `02_char_rnn_karpathy.ipynb` | Character-level models, RNN basics, Text generation |
| 3 | Understanding LSTM Networks | ✅ `03_lstm_understanding.ipynb` | Gates, Long-term memory, Gradient flow |
| 4 | RNN Regularization | ✅ `04_rnn_regularization.ipynb` | Dropout for sequences, Variational dropout |
| 5 | Keeping Neural Networks Simple | ✅ `05_neural_network_pruning.ipynb` | MDL principle, Weight pruning, 90%+ sparsity |

### Architectures & Mechanisms (Papers 6-15)

| # | Paper | Notebook | Key Concepts |
|---|-------|----------|--------------|
| 6 | Pointer Networks | ✅ `06_pointer_networks.ipynb` | Attention as pointer, Combinatorial problems |
| 7 | ImageNet/AlexNet | ✅ `07_alexnet_cnn.ipynb` | CNNs, Convolution, Data augmentation |
| 8 | Order Matters: Seq2Seq for Sets | ✅ `08_seq2seq_for_sets.ipynb` | Set encoding, Permutation invariance, Attention pooling |
| 9 | GPipe | ✅ `09_gpipe.ipynb` | Pipeline parallelism, Micro-batching, Re-materialization |
| 10 | Deep Residual Learning (ResNet) | ✅ `10_resnet_deep_residual.ipynb` | Skip connections, Gradient highways |
| 11 | Dilated Convolutions | ✅ `11_dilated_convolutions.ipynb` | Receptive fields, Multi-scale |
| 12 | Neural Message Passing (GNNs) | ✅ `12_graph_neural_networks.ipynb` | Graph networks, Message passing |
| 13 | **Attention Is All You Need** | ✅ `13_attention_is_all_you_need.ipynb` | Transformers, Self-attention, Multi-head |
| 14 | Neural Machine Translation | ✅ `14_bahdanau_attention.ipynb` | Seq2seq, Bahdanau attention |
| 15 | Identity Mappings in ResNet | ✅ `15_identity_mappings_resnet.ipynb` | Pre-activation, Gradient flow |

### Advanced Topics (Papers 16-22)

| # | Paper | Notebook | Key Concepts |
|---|-------|----------|--------------|
| 16 | Relational Reasoning | ✅ `16_relational_reasoning.ipynb` | Relation networks, Pairwise functions |
| 17 | **Variational Lossy Autoencoder** | ✅ `17_variational_autoencoder.ipynb` | VAE, ELBO, Reparameterization trick |
| 18 | **Relational RNNs** | ✅ `18_relational_rnn.ipynb` | Relational memory, Multi-head self-attention, Manual backprop (~1100 lines) |
| 19 | The Coffee Automaton | ✅ `01_complexity_dynamics.ipynb` | Irreversibility, Mixing, Complexity |
| 20 | **Neural Turing Machines** | ✅ `20_neural_turing_machine.ipynb` | External memory, Differentiable addressing |
| 21 | Deep Speech 2 (CTC) | ✅ `21_ctc_speech.ipynb` | CTC loss, Speech recognition |
| 22 | **Scaling Laws** | ✅ `22_scaling_laws.ipynb` | Power laws, Compute-optimal training |

### Theory & Meta-Learning (Papers 23-30)

| # | Paper | Notebook | Key Concepts |
|---|-------|----------|--------------|
| 23 | MDL Principle | ✅ `23_mdl_principle.ipynb` | Information theory, Model selection, Compression |
| 24 | Machine Super Intelligence | N/A (Theoretical) | AGI, Intelligence metrics |
| 25 | Kolmogorov Complexity | ✅ `25_kolmogorov_complexity.ipynb` | Compression, Algorithmic randomness, Universal prior |
| 26 | CS231n | N/A (Course) | CNNs, Computer vision |
| 27 | Multi-token Prediction | ✅ `27_multi_token_prediction.ipynb` | Multiple future tokens, Sample efficiency, 2-3x faster |
| 28 | Dense Passage Retrieval | ✅ `28_dense_passage_retrieval.ipynb` | Dual encoders, MIPS, In-batch negatives |
| 29 | Retrieval-Augmented Generation | ✅ `29_rag.ipynb` | RAG-Sequence, RAG-Token, Knowledge retrieval |
| 30 | Lost in the Middle | ✅ `30_lost_in_middle.ipynb` | Position bias, Long context, U-shaped curve |

## Featured Implementations

### 🌟 Must-Read Notebooks

These implementations cover the most influential papers and demonstrate core deep learning concepts:

#### Foundations
1. **`02_char_rnn_karpathy.ipynb`** - Character-level RNN
   - Build RNN from scratch
   - Understand backpropagation through time
   - Generate text

2. **`03_lstm_understanding.ipynb`** - LSTM Networks
   - Implement forget/input/output gates
   - Visualize gate activations
   - Compare with vanilla RNN

3. **`04_rnn_regularization.ipynb`** - RNN Regularization
   - Variational dropout for RNNs
   - Proper dropout placement
   - Training improvements

4. **`05_neural_network_pruning.ipynb`** - Network Pruning & MDL
   - Magnitude-based pruning
   - Iterative pruning with fine-tuning
   - 90%+ sparsity with minimal loss
   - Minimum Description Length principle

#### Computer Vision
5. **`07_alexnet_cnn.ipynb`** - CNNs & AlexNet
   - Convolutional layers from scratch
   - Max pooling and ReLU
   - Data augmentation techniques

6. **`10_resnet_deep_residual.ipynb`** - ResNet
   - Skip connections solve degradation
   - Gradient flow visualization
   - Identity mapping intuition

7. **`15_identity_mappings_resnet.ipynb`** - Pre-activation ResNet
   - Pre-activation vs post-activation
   - Better gradient flow
   - Training 1000+ layer networks

8. **`11_dilated_convolutions.ipynb`** - Dilated Convolutions
   - Multi-scale receptive fields
   - No pooling required
   - Semantic segmentation

#### Attention & Transformers
9. **`14_bahdanau_attention.ipynb`** - Neural Machine Translation
   - Original attention mechanism
   - Seq2seq with alignment
   - Attention visualization

10. **`13_attention_is_all_you_need.ipynb`** - Transformers
    - Scaled dot-product attention
    - Multi-head attention
    - Positional encoding
    - Foundation of modern LLMs

11. **`06_pointer_networks.ipynb`** - Pointer Networks
    - Attention as selection
    - Combinatorial optimization
    - Variable output size

12. **`08_seq2seq_for_sets.ipynb`** - Seq2Seq for Sets
    - Permutation-invariant set encoder
    - Read-Process-Write architecture
    - Attention over unordered elements
    - Sorting and set operations
    - Comparison: order-sensitive vs order-invariant

13. **`09_gpipe.ipynb`** - GPipe Pipeline Parallelism
    - Model partitioning across devices
    - Micro-batching for pipeline utilization
    - F-then-B schedule (forward all, backward all)
    - Re-materialization (gradient checkpointing)
    - Bubble time analysis
    - Training models larger than single-device memory

#### Advanced Topics
14. **`12_graph_neural_networks.ipynb`** - Graph Neural Networks
    - Message passing framework
    - Graph convolutions
    - Molecular property prediction

15. **`16_relational_reasoning.ipynb`** - Relation Networks
    - Pairwise relational reasoning
    - Visual QA
    - Permutation invariance

16. **`18_relational_rnn.ipynb`** - Relational RNN
    - LSTM with relational memory
    - Multi-head self-attention across memory slots
    - Architecture demonstration (forward pass)
    - Sequential reasoning tasks
    - **Section 11: Manual backpropagation implementation (~1100 lines)**
    - Complete gradient computation for all components
    - Gradient checking with numerical verification

17. **`20_neural_turing_machine.ipynb`** - Memory-Augmented Networks
    - Content & location addressing
    - Differentiable read/write
    - External memory

18. **`21_ctc_speech.ipynb`** - CTC Loss & Speech Recognition
    - Connectionist Temporal Classification
    - Alignment-free training
    - Forward algorithm

#### Generative Models
19. **`17_variational_autoencoder.ipynb`** - VAE
    - Generative modeling
    - ELBO loss
    - Latent space visualization

#### Modern Applications
20. **`27_multi_token_prediction.ipynb`** - Multi-Token Prediction
    - Predict multiple future tokens
    - 2-3x sample efficiency
    - Speculative decoding
    - Faster training & inference

21. **`28_dense_passage_retrieval.ipynb`** - Dense Retrieval
    - Dual encoder architecture
    - In-batch negatives
    - Semantic search

22. **`29_rag.ipynb`** - Retrieval-Augmented Generation
    - RAG-Sequence vs RAG-Token
    - Combining retrieval + generation
    - Knowledge-grounded outputs

23. **`30_lost_in_middle.ipynb`** - Long Context Analysis
    - Position bias in LLMs
    - U-shaped performance curve
    - Document ordering strategies

#### Scaling & Theory
24. **`22_scaling_laws.ipynb`** - Scaling Laws
    - Power law relationships
    - Compute-optimal training
    - Performance prediction

25. **`23_mdl_principle.ipynb`** - Minimum Description Length
    - Information-theoretic model selection
    - Compression = Understanding
    - MDL vs AIC/BIC comparison
    - Neural network architecture selection
    - MDL-based pruning (connects to Paper 5)
    - Kolmogorov complexity preview

26. **`25_kolmogorov_complexity.ipynb`** - Kolmogorov Complexity
    - K(x) = shortest program generating x
    - Randomness = Incompressibility
    - Algorithmic probability (Solomonoff)
    - Universal prior for induction
    - Connection to Shannon entropy
    - Occam's Razor formalized
    - Theoretical foundation for ML

27. **`01_complexity_dynamics.ipynb`** - Complexity & Entropy
    - Cellular automata (Rule 30)
    - Entropy growth
    - Irreversibility

## Repository Structure

```
sutskever-30-implementations/
├── README.md                           # This file
├── PROGRESS.md                         # Implementation progress tracking
├── IMPLEMENTATION_TRACKS.md            # Detailed tracks for all 30 papers
│
├── 01_complexity_dynamics.ipynb        # Entropy & complexity
├── 02_char_rnn_karpathy.ipynb         # Vanilla RNN
├── 03_lstm_understanding.ipynb         # LSTM gates
├── 04_rnn_regularization.ipynb         # Dropout for RNNs
├── 05_neural_network_pruning.ipynb     # Pruning & MDL
├── 06_pointer_networks.ipynb           # Attention pointers
├── 07_alexnet_cnn.ipynb               # CNNs & AlexNet
├── 08_seq2seq_for_sets.ipynb          # Permutation-invariant sets
├── 09_gpipe.ipynb                     # Pipeline parallelism
├── 10_resnet_deep_residual.ipynb      # Residual connections
├── 11_dilated_convolutions.ipynb       # Multi-scale convolutions
├── 12_graph_neural_networks.ipynb      # Message passing GNNs
├── 13_attention_is_all_you_need.ipynb # Transformer architecture
├── 14_bahdanau_attention.ipynb         # Original attention
├── 15_identity_mappings_resnet.ipynb   # Pre-activation ResNet
├── 16_relational_reasoning.ipynb       # Relation networks
├── 17_variational_autoencoder.ipynb   # VAE
├── 18_relational_rnn.ipynb             # Relational RNN
├── 20_neural_turing_machine.ipynb     # External memory
├── 21_ctc_speech.ipynb                # CTC loss
├── 22_scaling_laws.ipynb              # Empirical scaling
├── 23_mdl_principle.ipynb             # MDL & compression
├── 25_kolmogorov_complexity.ipynb     # K(x) & randomness
├── 27_multi_token_prediction.ipynb     # Multi-token prediction
├── 28_dense_passage_retrieval.ipynb    # Dense retrieval
├── 29_rag.ipynb                       # RAG architecture
└── 30_lost_in_middle.ipynb            # Long context analysis
```

**27 out of 30 papers implemented! (90% complete)**

## Learning Path

### Beginner Track (Start here!)
1. **Character RNN** (`02_char_rnn_karpathy.ipynb`) - Learn basic RNNs
2. **LSTM** (`03_lstm_understanding.ipynb`) - Understand gating mechanisms
3. **CNNs** (`07_alexnet_cnn.ipynb`) - Computer vision fundamentals
4. **ResNet** (`10_resnet_deep_residual.ipynb`) - Skip connections
5. **VAE** (`17_variational_autoencoder.ipynb`) - Generative models

### Intermediate Track
6. **RNN Regularization** (`04_rnn_regularization.ipynb`) - Better training
7. **Bahdanau Attention** (`14_bahdanau_attention.ipynb`) - Attention basics
8. **Pointer Networks** (`06_pointer_networks.ipynb`) - Attention as selection
9. **Seq2Seq for Sets** (`08_seq2seq_for_sets.ipynb`) - Permutation invariance
10. **GPipe** (`09_gpipe.ipynb`) - Pipeline parallelism for large models
11. **Transformers** (`13_attention_is_all_you_need.ipynb`) - Modern architecture
12. **Dilated Convolutions** (`11_dilated_convolutions.ipynb`) - Receptive fields
13. **Scaling Laws** (`22_scaling_laws.ipynb`) - Understanding scale

### Advanced Track
14. **Pre-activation ResNet** (`15_identity_mappings_resnet.ipynb`) - Architecture details
15. **Graph Neural Networks** (`12_graph_neural_networks.ipynb`) - Graph learning
16. **Relation Networks** (`16_relational_reasoning.ipynb`) - Relational reasoning
17. **Neural Turing Machines** (`20_neural_turing_machine.ipynb`) - External memory
18. **CTC Loss** (`21_ctc_speech.ipynb`) - Speech recognition
19. **Dense Retrieval** (`28_dense_passage_retrieval.ipynb`) - Semantic search
20. **RAG** (`29_rag.ipynb`) - Retrieval-augmented generation
21. **Lost in the Middle** (`30_lost_in_middle.ipynb`) - Long context analysis

### Theory & Fundamentals
22. **MDL Principle** (`23_mdl_principle.ipynb`) - Model selection via compression
23. **Kolmogorov Complexity** (`25_kolmogorov_complexity.ipynb`) - Randomness & information
24. **Complexity Dynamics** (`01_complexity_dynamics.ipynb`) - Entropy & emergence

## Key Insights from the Sutskever 30

### Architecture Evolution
- **RNN → LSTM**: Gating solves vanishing gradients
- **Plain Networks → ResNet**: Skip connections enable depth
- **RNN → Transformer**: Attention enables parallelization
- **Fixed vocab → Pointers**: Output can reference input

### Fundamental Mechanisms
- **Attention**: Differentiable selection mechanism
- **Residual Connections**: Gradient highways
- **Gating**: Learned information flow control
- **External Memory**: Separate storage from computation

### Training Insights
- **Scaling Laws**: Performance predictably improves with scale
- **Regularization**: Dropout, weight decay, data augmentation
- **Optimization**: Gradient clipping, learning rate schedules
- **Compute-Optimal**: Balance model size and training data

### Theoretical Foundations
- **Information Theory**: Compression, entropy, MDL
- **Complexity**: Kolmogorov complexity, power laws
- **Generative Modeling**: VAE, ELBO, latent spaces
- **Memory**: Differentiable data structures

## Implementation Philosophy

### Why NumPy-only?

These implementations deliberately avoid PyTorch/TensorFlow to:
- **Deepen understanding**: See what frameworks abstract away
- **Educational clarity**: No magic, every operation explicit
- **Core concepts**: Focus on algorithms, not framework APIs
- **Transferable knowledge**: Principles apply to any framework

### Synthetic Data Approach

Each notebook generates its own data to:
- **Immediate execution**: No dataset downloads required
- **Controlled experiments**: Understand behavior on simple cases
- **Concept focus**: Data doesn't obscure the algorithm
- **Rapid iteration**: Modify and re-run instantly

## Extensions & Next Steps

### Build on These Implementations

After understanding the core concepts, try:

1. **Scale up**: Implement in PyTorch/JAX for real datasets
2. **Combine techniques**: E.g., ResNet + Attention
3. **Modern variants**:
   - RNN → GRU → Transformer
   - VAE → β-VAE → VQ-VAE
   - ResNet → ResNeXt → EfficientNet
4. **Applications**: Apply to real problems

### Research Directions

The Sutskever 30 points toward:
- Scaling (bigger models, more data)
- Efficiency (sparse models, quantization)
- Capabilities (reasoning, multi-modal)
- Understanding (interpretability, theory)

## Resources

### Original Papers
See `IMPLEMENTATION_TRACKS.md` for full citations and links

### Additional Reading
- [Ilya Sutskever's Reading List (GitHub)](https://github.com/dzyim/ilya-sutskever-recommended-reading)
- [Aman's AI Journal - Sutskever 30 Primers](https://aman.ai/primers/ai/top-30-papers/)
- [The Annotated Transformer](http://nlp.seas.harvard.edu/annotated-transformer/)
- [Andrej Karpathy's Blog](http://karpathy.github.io/)

### Courses
- Stanford CS231n: Convolutional Neural Networks
- Stanford CS224n: NLP with Deep Learning
- MIT 6.S191: Introduction to Deep Learning

## Contributing

These implementations are educational and can be improved! Consider:
- Adding more visualizations
- Implementing missing papers
- Improving explanations
- Finding bugs
- Adding comparisons with framework implementations

## Citation

If you use these implementations in your work or teaching:

```bibtex
@misc{sutskever30implementations,
  title={Sutskever 30: Complete Implementation Suite},
  author={Paul "The Pageman" Pajo, pageman@gmail.com},
  year={2025},
  note={Educational implementations of Ilya Sutskever's recommended reading list, inspired by https://papercode.vercel.app/}
}
```

## License

Educational use. See individual papers for original research citations.

## Acknowledgments

- **Ilya Sutskever**: For curating this essential reading list
- **Paper authors**: For their foundational contributions
- **Community**: For making these ideas accessible

---

## Latest Additions (December 2025)

### Recently Implemented (18 new papers!)
- ✅ **Paper 4**: RNN Regularization (variational dropout)
- ✅ **Paper 5**: Neural Network Pruning (MDL, 90%+ sparsity)
- ✅ **Paper 7**: AlexNet (CNNs from scratch)
- ✅ **Paper 8**: Seq2Seq for Sets (permutation invariance, attention pooling)
- ✅ **Paper 9**: GPipe (pipeline parallelism, micro-batching, re-materialization)
- ✅ **Paper 11**: Dilated Convolutions (multi-scale)
- ✅ **Paper 12**: Graph Neural Networks (message passing)
- ✅ **Paper 14**: Bahdanau Attention (original attention)
- ✅ **Paper 15**: Identity Mappings ResNet (pre-activation)
- ✅ **Paper 16**: Relational Reasoning (relation networks)
- ✅ **Paper 18**: Relational RNNs (relational memory + Section 11: manual backprop ~1100 lines)
- ✅ **Paper 21**: Deep Speech 2 (CTC loss)
- ✅ **Paper 23**: MDL Principle (compression, model selection, connects to Papers 5 & 25)
- ✅ **Paper 25**: Kolmogorov Complexity (randomness, algorithmic probability, theoretical foundation)
- ✅ **Paper 27**: Multi-Token Prediction (2-3x sample efficiency)
- ✅ **Paper 28**: Dense Passage Retrieval (dual encoders)
- ✅ **Paper 29**: RAG (retrieval-augmented generation)
- ✅ **Paper 30**: Lost in the Middle (long context)

## Quick Reference: Implementation Complexity

### Can Implement in an Afternoon
- ✅ Character RNN
- ✅ LSTM
- ✅ ResNet
- ✅ Simple VAE
- ✅ Dilated Convolutions

### Weekend Projects
- ✅ Transformer
- ✅ Pointer Networks
- ✅ Graph Neural Networks
- ✅ Relation Networks
- ✅ Neural Turing Machine
- ✅ CTC Loss
- ✅ Dense Retrieval

### Week-Long Deep Dives
- ✅ Full RAG system
- ⚠️ Large-scale experiments
- ⚠️ Hyperparameter optimization

---

**"If you really learn all of these, you'll know 90% of what matters today."** - Ilya Sutskever

Happy learning! 🚀
