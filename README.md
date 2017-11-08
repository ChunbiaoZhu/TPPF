## A Three-pathway Psychobiological Framework of Salient Object Detection Using Stereoscopic Technology

This paper is accepted at ICCV workshop.

[Full-text is available on CVF.](http://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w43/Zhu_A_Three-Pathway_Psychobiological_ICCV_2017_paper.pdf)

## Abstract

Saliency detection, finding the most important parts of
an image, has become increasingly popular in computer vision.
Existing proposal methods are mostly based on color
information, which may not be effective for cluttered backgrounds.
We propose a new algorithm leveraging stereopsis
to generate optical flow which can obtain addition cue
(depth cue) to get the final saliency map. The proposed
framework consists of three pathways. The first pathway
eliminates the background based on cellular automata. The
second pathway gets the optical flow and color flow saliency
map. The third pathway calculates a coarse saliency map.
Finally, we fuse these three pathways to generate the final
saliency map. Besides, we construct a new high-quality
dataset with the complex scene to make computer challenge
human vision. Experimental results on our dataset and another
three popular datasets demonstrate that our method
is superior to the existing methods in terms of robustness.


## Framework
![QFramework saliency detection](https://github.com/ChunbiaoZhu/TPPF/blob/master/framework.png)

## DATASET

Dataset is public.

You can download in [here](https://github.com/ChunbiaoZhu/TPPF/blob/master/%5BDataset%5DPKU80.zip)

## Cite this paper as:

    @InProceedings{Zhu_2017_ICCV_Workshops,
    author = {Zhu, Chunbiao and Li, Ge},
    title = {A Three-Pathway Psychobiological Framework of Salient Object Detection Using Stereoscopic Technology},
    booktitle = {The IEEE International Conference on Computer Vision (ICCV)},
    month = {Oct},
    year = {2017}
    }

## Acknowledgements

This work was supported by the grant of National Natural Science Foundation of China (No.U1611461), Shenzhen Peacock Plan (20130408-183003656), and Science and Technology Planning Project of Guangdong Province, China (No. 2014B090910001).


## Contact

If you have any general doubt about our work or code which may be of interest for other researchers, please use the [public issues section](https://github.com/ChunbiaoZhu/TPPF/issues) on this github repo. Alternatively, drop us an e-mail at <mailto:zhuchunbiao@pku.edu.cn>.

