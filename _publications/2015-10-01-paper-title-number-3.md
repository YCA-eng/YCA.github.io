---
title: "Rapid 3D Model Generation with Intuitive 3D Input"
collection: publications
permalink: /publication/2015-10-01-paper-title-number-3
excerpt: 'The paper proposes Deep3DVRSketch, a 3D model generation network that enables novice users to create high-quality 3D models from 3D VR sketches. It aims to overcome the complexity of traditional CAD software. The method uses AI models and introduces the KO3D+ dataset. Experiments show it is over 10 times faster than conventional CAD tools.'
date: 2024-9-16
venue: 'Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition(CVPR).'
slidesurl: 'https://github.com/YCA-eng/YCA.github.io/tree/master/files/Rapid_3D_Model_Generation_with_Intuitive_3D_Input.pdf'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2024/papers/Chen_Rapid_3D_Model_Generation_with_Intuitive_3D_Input_CVPR_2024_paper.pdf'
citation: 'Chen T, Ding C, Zhang S, et al. Rapid 3d model generation with intuitive 3d input[C]//Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2024: 12554-12564.'
---

With the emergence of AR/VR, 3D models are in tremendous demand. However, conventional 3D modeling with Computer-Aided Design software requires much expertise and is difficult for novice users. We find that AR/VR devices, in addition to serving as effective display mediums, can offer a promising potential as an intuitive 3D model creation tool, especially with the assistance of AI generative models. Here, we propose Deep3DVRSketch, the first 3D model generation network that inputs 3D VR sketches from novice users and generates highly consistent 3D models in multiple categories within seconds, irrespective of the users’ drawing abilities. We also contribute KO3D+, the largest 3D sketch-shape dataset. Our method pre-trains a conditional diffusion model on quality 3D data, then finetunes an encoder to map 3D sketches onto the generator’s manifold using an adaptive curriculum strategy for limited ground truths. In our experiment, our approach achieves state-of-the-art performance in both model quality and fidelity with real-world input from novice users, and users can even draw and obtain very detailed geometric structures. In our user study, users were able to complete the 3D modeling tasks over 10 times faster using our approach compared to conventional CAD software tools. We believe that our Deep3DVRSketch and KO3D+ dataset can offer a promising solution for future 3D modeling in metaverse era. Check the project page at http://research. kokoni3d.com/Deep3DVRSketch.
