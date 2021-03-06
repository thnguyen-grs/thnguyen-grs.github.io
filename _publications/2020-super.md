---
title: "Super-Resolution-based Snake Model—An Unsupervised Method for Large-Scale Building Extraction using Airborne LiDAR Data and Optical Image"
collection: publications
permalink: /publication/2020-super
excerpt: ''
date: 2020-04-30
venue: 'Remote Sensing'
paperurl: 'https://www.mdpi.com/2072-4292/12/11/1702'
citation: 'T. H. Nguyen, S. Daniel, D. Guériot, C. Sintès, and J.-M. Le Caillec. (2020). &quot;Super-Resolution-based Snake Model—An Unsupervised Method for Large-Scale Building Extraction using Airborne LiDAR Data and Optical Image.&quot; <i>Remote Sens.</i>, 12(11), 1702. DOI: 10.3390/rs12111702'
---

**Abstract:** Automatic extraction of buildings in urban and residential scenes has become a subject of growing interest in the domain of photogrammetry and remote sensing, particularly since mid-1990s. Active contour model, colloquially known as snake model, has been studied to extract buildings from aerial and satellite imagery. However, this task is still very challenging due to the complexity of building size, shape, and its surrounding environment. This complexity leads to a major obstacle for carrying out a reliable large-scale building extraction, since the involved prior information and assumptions on building such as shape, size, and color cannot be generalized over large areas. This paper presents an efficient snake model to overcome such challenge, called Super-Resolution-based Snake Model (SRSM). The SRSM operates on high-resolution LiDAR-based elevation images—called z-images—generated by a super-resolution process applied to LiDAR data. The involved balloon force model is also improved to shrink or inflate adaptively, instead of inflating the snake continuously. This method is applicable for a large scale such as city scale and even larger, while having a high level of automation and not requiring any prior knowledge nor training data from the urban scenes (hence unsupervised). It achieves high overall accuracy when tested on various datasets. For instance, the proposed SRSM yields an average area-based Quality of 86.57% and object-based Quality of 81.60% on the ISPRS Vaihingen benchmark datasets. Compared to other methods using this benchmark dataset, this level of accuracy is highly desirable even for a supervised method. Similarly desirable outcomes are obtained when carrying out the proposed SRSM on the whole City of Quebec (total area of 656 km<sup>2</sup>), yielding an area-based Quality of 62.37% and an object-based Quality of 63.21%.

**Keywords:** building extraction, building footprint extraction, airborne LiDAR, optical imagery, active contour model, snake model, super-resolution, unsupervised approach, large-scale.

The article can be downloaded from \[[link](https://www.mdpi.com/2072-4292/12/11/1702)\] or \[[arXiv](https://arxiv.org/abs/2004.08522)\].
The results are made publically at [Github](https://github.com/nthuy190991/SRSM_QuebecCity_building_extraction).
