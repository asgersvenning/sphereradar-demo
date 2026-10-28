# SphereRadar demo

Interactive egocentric "radar" view of species embeddings on the unit hypersphere: global Lepidoptera
(EfficientNetV2-S, flat head), 12,632 species, up to 40 images each. Click a point to hop to it; shift-click moves to the
mean/median of its group. Class means are the fitted points (pole, plane); images are placed on the same chart.

Live: https://asgersvenning.github.io/sphereradar-demo/

The page is a single self-contained `index.html`; the embeddings are read from a public bucket with HTTP Range requests.
Accompanies the manuscript "The Role of Hierarchically Explicit Deep Learning Models in Species Classification".
