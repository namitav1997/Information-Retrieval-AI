# CPSC8470-Information-Retrieval
## **Project Repository for Fashion Recommendation with Visual Explanations.**

Fashion recommendation has attracted increasing attention from both industry and academic communities. This paper proposes a novel neural architecture for fashion recommendation based on both image region-level features and user review information. Our basic intuition is that: for a fashion image, not all the regions are equally important for the users, i.e., people usually care about a few parts of the fashion image. To model such human sense, we learn an attention model over many pre-segmented image regions, based on which we can understand where a user is really interested in on the image, and correspondingly, represent the image in a more accurate manner. In addition, by discovering such fine-grained visual preference, we can visually explain a recommendation by highlighting some regions of its image. For better learning the attention model, we also introduce user review information as a weak supervision signal to collect more comprehensive user preference. In our final framework, the visual and textual features are seamlessly coupled by a multimodal attention network. Based on this architecture, we can not only provide accurate recommendation, but also can accompany each recommended item with novel visual explanations. We conduct extensive experiments to demonstrate the superiority of our proposed model in terms of Top-N recommendation, and also we build a collectively labeled dataset for evaluating our provided visual explanations in a quantitative manner.

## Experiment Setup
* Python
* NumPy
* SciPy
* Tensorflow

The experiment has been trained in Windows OS with 16GB RAM, a premium graphics card (Nvidia GeForce GTX 1050).

## Datasets
* AmazonFashion: 100K users, 456K images, 0.8M actions
* AmazonWomen: 152K users, 765K images, 1M actions
* AmazonMen: 97K users, 324K images, 0.3M actions

The datasets can be downloaded from dataset.sh file.
