# ML Models

## What are types of models models?

- ***Deterministic model:***  A statistical model that determines boundaries in the observed data and uses these boundaries to make decisions or predictions.
- ***Generative model:*** Describes how a dataset is generated in terms of probablistc model and sampling from the model allows to generate new data that did not exist.

| **Aspect** | **Deterministic Model** | **Generative Model** |
| --- | --- | --- |
| **Definition** | A statistical model that determines boundaries in the observed data and uses these boundaries to make decisions or predictions. | Describes how a dataset is generated in terms of a probabilistic model, and sampling from the model allows generating new data that did not exist. |
| **Nature of Prediction** | Makes fixed predictions based on specific input. | Makes probabilistic predictions and can generate new data points. |
| **Data Handling** | Focuses on patterns in the observed data and does not account for uncertainty. | Models the underlying process that generates the data, accounting for uncertainty. |
| **Goal** | To find a clear boundary or decision rule to classify or predict. | To understand the data distribution and generate new instances. |
| **Example** | Decision trees, linear regression. | Gaussian Mixture Models (GMM), Variational Autoencoders (VAE). |
| **Uncertainty** | No inherent uncertainty; predictions are deterministic. | Inherently accounts for uncertainty in predictions. |
| **Output** | A specific prediction or classification. | New data samples or a distribution from which data can be sampled. |
| **Data Generation** | Does not generate new data. | Can generate new data similar to the observed data. |

Generative Advesarial Networks called as GANs for short - [GAN Fundamentals](gan_overview.md)

What are CNNs and Deep CNN based GAN: [CNN Overview and Deep CNN based GAN architecture](overview_cnns.md)