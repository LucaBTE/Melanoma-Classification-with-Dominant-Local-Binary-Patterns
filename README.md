# Abstract
This report describes a texture-based pipeline for melanoma recognition in dermoscopic images, inspired by Dominant
Local Binary Patterns for Texture Classification (DLBP) and complemented with Normalized Gabor Features (NGF).
Texture descriptors are computed inside a lesion mask and a non-linear SVM (RBF kernel) is used for classification. The
system is evaluated on two train/test splits of a 7 000-image demo subset from the ISIC 2020 Challenge dataset, obtaining
an accuracy (hit rate) close to 98%.
