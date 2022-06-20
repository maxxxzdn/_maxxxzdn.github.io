---
layout: page
title: generative modelling
description: Learning neurological mechanisms of pathologies with variational auto-encoders.
img: assets/img/eegvae.png
importance: 1
category: all
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/eegvae_scheme.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Scheme of the proposed approach. We receive neuroimaging data as input and learn a stochastic mapping to a latent space with CCVAEs [1]. We further manipulate learned generative factors of data to gain insights regarding neurological mechanisms related to the attributes of interest, e.g. symptoms.
</div>

[1] Joy, T., Schmon, S.M., Torr, P.H., Siddharth, N., & Rainforth, T. (2021). Capturing Label Characteristics in VAEs. ICLR.
