# ONiT: Annotated Dataset Final Version

This is the updated version of our annotated image dataset extracted from the travelogues corpus, which was analized in context of the [Ottoman Nature in Travelogues (ONiT) project](https://onit.oeaw.ac.at/). In total, we extracted 22,299 images from a corpus of about 15,000 travelogues. Many of them were previously unknown to research, albeit this not only included mimetic representations relevant to the project, but also printer’s marks and paratextual additions as well as artifacts from the digitization process, which were detected by the image extraction tool. For the image extraction, we used the [Illustration Detector](https://gitlab.com/vgg/nls-chapbooks-illustrations/-/tree/master) by the Visual Geometry Group (VGG), Oxford. 

We included multi-label annotations in [ICONCLASS](https://iconclass.org/) of all nature representations identified in the images, comprising animals, plants, landscapes, and maps. In total, we annotated 5,713 representations of plants or vegetation (26% of all extracted images), 4,252 landscapes (20% of all extracted images), 3,517 animals (16% of all extracted images), and 1,084 maps (5% of all extracted images). As the animal class contained notably heterogeneous features, we created more detailed annotations within it. This resulted in 21,793 annotations of flora, fauna, landscapes, maps, and individual animal classes (in total 68 annotated classes).

**Please note:**
A collection of direct links leading to the extracted images at the [Austrian National Library (ÖNB) IIIF repository](http://iiif.onb.ac.at/) are provided in the CSV/Excel files. The links were created during the first project year based on the IIIF link used for downloading the scanned book pages and the coordinates of the identified image-crops provided by the Illustration Detector. Since then, some of the books that we harvested were updated by the ÖNB (respectively Google books). This led to changes in the sequence of scanned pages in ÖNB's IIIF repository. Thus, in some cases, the direct links to the original image source do not point to the identified image anymore. Be aware that not all provided IIIF links lead to the correct page or image-crop. To make the entire set of extracted images available, we will provide a dump for download shortly.

**This repository contains:**
* A CSV/Xcel file listing all images that we have extracted and, where identified, the annotations of nature classes present on the image (ONiT_extracted-images_singleEditions_wAnnotations_2025-01-28);
* A CSV/Xcel file listing all images with nature representations from the corpus with the ICONCLASS notations (ONiT_D16-L19_multi-label_detailed_2025-01-28).

# References
This dataset was published in context of the paper submitted to the DSH special issue for the DH 2023 conference proceedings (currently under review).
