# Target-Ensemble
Apart from the main target, there are actually many auxilliary targets in the dataset.

These targets are fundamentally related to the main target which make them potentially helpful to model. And because these targets have a wide range of correlations to the main targets, it means that we could potentially build some nice ensembles to boost our performance.

In this notebook, we will

- Explore the auxilliary targets
- Select our favorite targets to include in the ensemble
- Create an ensemble of models trained on different targets
- Pickle and upload our ensemble model
