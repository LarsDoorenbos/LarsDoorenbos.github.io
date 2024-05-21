---
layout: page
title: Hyperspectral segmentation
description: a holoscan application for segmentation of intraoperative hyperspectral cubes
img: assets/img/h.jpg
importance: 1
category: work
---

During my internship at Nvidia I built a holoscan application that segments intraoperative hyperspectral cubes into 20 organ classes, and visualizes the result together with the RGB image corresponding to the hyperspectral cube. I used the <a href="https://www.heiporspectral.org/">HeiPorSPECTRAL</a> dataset, and a pretrained segmentation network from <a href="https://github.com/IMSY-DKFZ/htc">this repository</a>.

 The application is available on <a href="https://github.com/nvidia-holoscan/holohub/tree/main/applications/hyperspectral_segmentation">Holohub</a> and <a href="https://catalog.ngc.nvidia.com/orgs/nvidia/teams/clara-holoscan/resources/hyperspectral_segmentation">NGC</a>.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/h.jpg" title="hyperspectral segmentation" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The RGB image corresponding to the hyperspectral input, the segmentation, and the overlay.
</div>

