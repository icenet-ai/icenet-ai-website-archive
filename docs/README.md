# IceNet

IceNet is a deep learning sea ice forecasting system developed by an [international team and led by the British Antarctic Survey and The Alan Turing Institute](https://www.bas.ac.uk/media-post/artificial-intelligence-to-help-predict-arctic-sea-ice-loss/).
The original IceNet research model, [published in *Nature Communications*](https://www.nature.com/articles/s41467-021-25257-4) was trained on climate simulations and observational data to forecast the next 6 months of monthly-averaged sea ice concentration maps.
This version advanced the range of accurate sea ice forecasts, outperforming a state-of-the-art dynamical model (ECMWF SEAS5) in seasonal forecasts of summer sea ice, particularly for extreme sea ice events.
Since then, the IceNet team has focussed on building an operational version of the model which forecasts on a daily resolution.
The [original research code](https://www.github.com/tom-andersson/icenet-paper) was refactored into `icenet`: [a library for operational forecasting](https://github.com/icenet-ai/icenet).
The `icenet` library can support further research efforts into AI-based operational sea ice forecasting

In addition, several use cases and an ecosystem of service components are contained within this organisation, supporting execution and downstream analysis. 

For further information about the team involved, please look at the [project pages at BAS](https://www.bas.ac.uk/project/icenet/) or [The Alan Turing Institute](https://www.turing.ac.uk/news/artificial-intelligence-help-predict-arctic-sea-ice-loss). 

## How do I get started?

For some high level information, review the [project repository](https://github.com/icenet-ai/icenet-project). If you want to dive straight into the technicals, likely you'll want to start with the [icenet library](https://github.com/icenet-ai/icenet/), [icenet-pipeline operational usage example](https://github.com/icenet-ai/icenet-pipeline/) and/or [the icenet-notebooks repository which explains both CLI and programmatic usage](https://github.com/icenet-ai/icenet-notebooks/).

## Publications

* [Tom Andersson's original IceNet research paper, published in Nature Communications](https://www.nature.com/articles/s41467-021-25257-4)

## Presentations

* [James Byrne](https://www.bas.ac.uk/profile/jambyr) described how the IceNet project reflects best practice software engineering for climate science at [Climate Informatics 2023](https://cambridge-iccs.github.io/climate-informatics-2023/), watch it below: 

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/sfmVOaR_YCg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
