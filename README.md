RoundixReason: Multi-Domain Reasoning with GRPO

RoundixReason (Round Raisin) was built with the goal of creating a model that could reason across a more diverse set of topics, hence the name "Roundix" to reflect a well-rounded model built in Tunix. Our approach uses Gemma 3 1B Instruct as the base model, fine-tuned with GRPO (Group Relative Policy Optimization).

The model usually gets 0.5 in rewards on average before training, and 4.4 afterwards.

The notebook was designed to be run on a v5e-8 TPU cluster with at least 16 GB of memory per core. It can be run on smaller clusters, but the batch size and learning rate may need to be adjusted accordingly.
You can get access to TPU clusters through platforms like Google Cloud Platform or Google Colab Pro+.

In order to access the datasets used for training, visit the dataset repository at https://huggingface.co/datasets/LockedInTheSkage/RoundixReason-tagged-reasoning