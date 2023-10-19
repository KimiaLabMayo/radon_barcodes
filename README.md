# Radon Barcodes - Barcode Annotations for Medical Image Retrieval: A Preliminary Investigation
### Paper Abstract
This paper proposes to generate and to use barcodes to annotate medical images and/or their regions of interest such as organs, tumors and tissue types. A multitude of efficient feature-based image retrieval methods already exist that can assign a query image to a certain image class. Visual annotations may help to increase the retrieval accuracy if combined with existing feature-based classification paradigms. Whereas with annotations we usually mean textual descriptions, in this paper barcode annotations are proposed. In particular, Radon barcodes (RBC) are introduced. As well, local binary patterns (LBP) and local Radon binary patterns (LRBP) are implemented as barcodes. The IRMA x-ray dataset with 12,677 training images and 1,733 test images is used to verify how barcodes could facilitate image retrieval.
### Code
This Matlab function extracts a Radon barcode from an image.

Usage: ```function barcode = extract RBC(IMG, nrows, ncols, numRays, showRBC)```

Implemented as introduced and described in the paper.
### Useful Links
- [Paper](https://arxiv.org/abs/1505.05212)
- [Learn more on Kimia Lab](https://kimialab.uwaterloo.ca/kimia/index.php/data-and-code-2/kimia-net/)
### Disclaimer
Rhazes Lab does not own the code in this repository. This code and data were produced in Kimia Lab at the University of Waterloo. The code is provided as-is without any guarantees, and is stored here as part of Kimia Lab's history. We welcome questions and comments.
