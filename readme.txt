----------- readme ------------

Two notebooks are presented, each notebook presents a different architectural approach to the challenge. Both have been developed within Colab using a dedicated GPU for training. Please note, that both models have been developed in pytorch, specifically, pytorch lightning has been used to reduce boiler plate code and improve the development experience. Furthermore, Ray Tune has been used to launch optimisation trials for both approaches.

Each main section of each notebook have comparable headings, the general work flow is as follows for both of them.

1. Import libraries
2. Load cifar-10 data and inspect it
3. Declare a pytorch lightning model (including datasets, and data modules for cifar-10)
4. Single model training with config dictionary
5. Automatic hyper-parameter tuning over range of parameters
6. Capture logs from automatic tuning and display in training/validation graphs (as seen in report)