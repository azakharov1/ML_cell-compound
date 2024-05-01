# ML from image-based data (cells – compound experiment)
Predict drug dosage learning on cell morphological data extracted by image segmentation from microscopy images (tumor MCF7 cells under podophyllotoxin treatment).

Data contains measuremnts for two independent channels: **n** channel for DAPI (shows DNA staining in cell nucleus) and **a** channel for actin (cell border)

Image source: Broad Bioimage Benchmark Collection https://bbbc.broadinstitute.org/BBBC021

Image segmentation: Pretrained DL-based model CellPose http://www.cellpose.org

Segmented image measurement: ImageJ https://imagej.net/ij/
