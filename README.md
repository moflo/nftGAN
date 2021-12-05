# nftGAN
Using StyleGAN with NFT datasets

## Release v0.1

Testing styleGAN with TFDS dataset from opensea.io, using the Chain Runners NFT collection with a target resolution of 128x128, trained for 10k epochs at each resolution step.

- 0_training : directory of training and testing scripts
- 1_testing : using Huggingface for test of trained models
- 2_control : test styleGAN generation using mix of FFHQ/CelebA and Chain Runners NFT datasets for mapping tests