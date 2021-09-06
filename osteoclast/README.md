Image analysis workflow for morphological feature extraction.
An automated image analysis workflow is required for the image feature extraction.
We have chosen CellProfiler for its broad range of applicable cell types, rich suite of morphological features, and optimization for analysis at large scale and high throughput. The 
image feature extraction workflow for this screening is divided into 
two tasks, each of which is performed by a CellProfiler pipeline: 
(i) illumination correction, and (ii) morphological feature extraction.
(i) Illumination correction serves to correct each image for spatial illumination heterogeneities introduced by the microscope optics, which can bias intensity-based measurements and impair cellular feature identification. We have found that this corrective step improves the ability to detect cells during the segmentation step.
(ii) Finally, morphological image feature extraction provides the raw quantitative material for profiling. The second CellProfiler pipeline identifies the nucleus, cells, makes measurements of morphology, peripheral / internal actin intensity and peripheral / internal tubulin intensity. The results are then exported for data analysis.
