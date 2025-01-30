# DeepSeek Scaling Laws
An open reproduction of the training code for DeepSeek-V3. This repo is a work in progress. Contributions are welcome!

## Goal
Not all training details/ablations have been published in the DeepSeek-V3 paper e.g. what contributes most to the low pretraining cost? Is it the FP8 training, the MoE system, something else?

## TODO
- Set up a basic training loop and data loader using e.g. the OpenWebText dataset
- Implement the DeepSeek-V3 MoE model
- Implement the Auxiliary-Loss-Free Load Balancing
- Implement the Complementary Sequence-Wise Auxiliary Loss
- Run training jobs at small scale (10M, 100M, 500M, 1B params) and compute scaling laws to compare with vanilla transformer scaling laws
