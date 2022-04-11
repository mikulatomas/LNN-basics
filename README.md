# LNN-basics

## Inference
Following notebooks describes process of inference in [Logical Neural Networks](https://github.com/IBM/LNN) (LNN).

> Inference refers to the entire process of computing truth value bounds for (sub)formulae and atoms based on initial knowledge, ultimately resulting in predictions made at neurons pertaining to queried formulae or other results of interest. 

> LNN achieves this with multiple passes over the represented formulae, propagating tightened truth value bounds from neuron to neuron until computation necessarily converges. The previous section already suggests the upward pass of inference, whereby formulae compute their truth value bounds based on bounds available for their subformulae.

* `upward.ipynb` - describes the upward pass of inference
* `downward.ipynb` - describes the downward pass of inference
* `uncertainty.ipynb` - describes the inference with uncertainty

## Reference
> [1] Riegel, Ryan, Alexander Gray, Francois Luus, Naweed Khan, Ndivhuwo Makondo, Ismail Yunus Akhalwaya, Haifeng Qian et al. "Logical neural networks." arXiv preprint arXiv:2006.13155 (2020).