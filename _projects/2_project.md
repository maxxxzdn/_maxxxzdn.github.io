---
layout: page
title: graph neural networks
description: Interpretable classification of EEG data with GNNs and GNNExplainer.
img: assets/img/gnns.png
importance: 2
category: all
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/gnns_scheme.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Scheme of the proposed approach. (A) Latent temporal features are computed with 1D CNN in a channel-wise manner. Afterwards, the latent feature vectors are mapped on a graph determined by the EEG setup. Multiple steps of message passing are further applied via graph neural networks to calculate the hidden representation of the graph. Node-wise max pooling is then applied to produce a graph embedding. The embedding is passed through an MLP to predict the graph's disorder and state classes. (B) GNNExplainer takes EEG data, a model and a prediction of the model to infer a subset of nodes (red nodes), a subset of edges (red edges) and a subspace of node features (transparent red area) that the model relied on while making the decision. (C) Class-wise explanations are computed for each edge as the frequency of being included in the explanation subgraph.
</div>
