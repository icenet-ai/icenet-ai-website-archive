---
title: icenet-pipeline
subtitle: Implementations of icenet workflows for end-to-end training and predictions in bash.
---
A detailed explanation of the machine learning pipeline can be [found here](https://github.com/icenet-ai/icenet-project/wiki/Model-Pipeline). Fundamentally, there is a reusable and continuously executable pipeline from data ingestion through to forecast production and upload. This repository complements the icenet-notebooks repository which explains both CLI and programmatic usage, by actually implementing a load of workflows in bash.

This high level diagram depicts the structuring of the pipeline:

<img width="100%" src="https://github.com/icenet-ai/icenet-project/wiki/Pipeline%20Layout.png" alt="IceNet ML Pipeline" />

The daily forecasting pipeline centers around a refactored version [of the original research model for monthly forecasts](https://github.com/tom-andersson/icenet-paper), located [in this library](https://www.github.com/icenet-ai/icenet). An example to using the library [can be found here](https://github.com/icenet-ai/icenet-pipeline) which leverage a BAS developed tool for running [model ensembles.](https://github.com/JimCircadian/model-ensembler) on HPCs."
