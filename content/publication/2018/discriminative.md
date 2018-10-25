+++
abstract = "State-of-the-art deep learning algorithms yield remarkable results in many visual recognition tasks. However, they still catastrophically struggle in low data scenarios. To a certain extent, the lack of visual data can be compensated by multimodal information. Information missing in one modality (e.g. image) due to the limited data can be included in the other modality (e.g. text). In this paper, we propose a benchmark for few-shot learning with multi-modal data which can be used by other researchers. We also introduced a method for few-shot fine-grained recognition, utilizing textual descriptions of the visual data. We developed a two-stage framework built upon the idea of cross-modal data hallucination. For each visual category, we first generate a set of images by conditioning on the textual description of the category using StackGANs. Next, we rank the generated images based on their class-discriminativeness and only pick the most discriminative images to extend the dataset. Lastly, a classifier invariant to our framework can be trained using an extended training set. We show the results of our proposed discriminative hallucinated method for 1-, 2-, and 5-shot learning on the CUB dataset, where the accuracy is improved by employing the multi-modal data."
title = "Discriminative Hallucination for Multi-Modal Few-Shot Learning"
authors = ["Frederik Pahde", "Moin Nabi", "Tassilo Klein", "Patrick Jähnichen"]
publication = "2018 IEEE International Conference on Image Processing"
url_pdf = "pdf/icip-discriminative-hallucination.pdf"
url_image = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_external = "https://ieeexplore.ieee.org/document/8451372"
+++