![Static Badge](https://img.shields.io/badge/MATLAB-R2018b_or_higher-orange)

[1.2]: http://i.imgur.com/wWzX9uB.png
[1]: http://www.twitter.com/AswendtMarkus
<!--social icon from https://github.com/carlsednaoui/gitsocial -->
<img align="right" src="https://github.com/maswendt/AIDAhisto/blob/master/logo.png"><h1>AIDA<i>histo</i></h1>***Atlas-based imaging data analysis tool for quantitative mouse brain histology***
<p align="justify"> Software to automatically <b>detect cells</b> in histological <b>mouse brain</b> and <b>spinal cord</b> sections. Tested for different immunostainings (e.g., GFAP, Iba1, and MAP2) and histological stainings (e.g., Nissl). The Allen Mouse Brain/Spinal Cord Atlas is used to register the microscopy files. Cell counting results are reported as cells per brain region.</p>

Information about [Version 1.2 (current)](https://github.com/maswendt/AIDAhisto/releases/tag/v1.2) / [Version 1.1](https://github.com/maswendt/AIDAhisto/releases/tag/v1.1) / [Version 1.0](https://github.com/maswendt/AIDAhisto/releases/tag/v1.0)</b>

<h2><b>EXAMPLES</h2></b>
<img align="center" src="https://github.com/maswendt/AIDAhisto/blob/master/AIDAhisto_Overview.png">
<img align="center" src="https://github.com/maswendt/AIDAhisto/blob/master/AIDAhisto_Overview_SC.png">

<h3><b>FEATURES</h3></b>
<i>Please note that we stopped supporting Python-based tools. All corresponding tools are available for Matlab.</i>

- Includes a custom version of the Allen Mouse Brain/Spinal Cord Atlas with a list of annotations

- Instruction on how to register the atlas with microscopy files using ImageJ

- Automated cell counting

- Cell counting works for immunostainings and histological stainings; the cell nuclei position (e.g. based on a DAPI staining) can be used to improve the cell counting (only cells with a cell nuclei will be counted)

<h3><b>GET STARTED</h3></b>

Download the modified atlas files and the test images (including representative results) [here](https://doi.org/10.12751/g-node.25jp6z). For details on installation and use, see the step-by-step guide in the [Manual v1.2](https://github.com/aswendtlab/AIDAhisto/blob/master/AIDAhisto_v1_2.pdf).


<h3><b>CITATION</h3></b>

When applying or modifying AIDAhisto, please always cite the original reference: [Pallast, N., et al. "Atlas-based imaging data analysis tool for quantitative mouse brain histology (AIDAhisto)" Journal of Neuroscience Methods, 2019](https://www.sciencedirect.com/science/article/pii/S0165027019302511?via%3Dihub)

[<h3><b>CONTACT</h3></b>](https://neurologie.uk-koeln.de/forschung/ag-neuroimaging-neuroengineering/)
Chat with us [![Matrix](https://matrix.to/#/#AIDA_tools_community:gitter.im) 

or 

join our Open Office Hour - each Thursday 3:00 pm (UTC+2) [![Zoom](https://img.shields.io/badge/Zoom-2D8CFF?style=for-the-badge&logo=zoom&logoColor)](https://uni-koeln.zoom.us/meeting/register/tJYsceyorDoqGdX4H8Z7c86_qxoaq6yOdFGM)

Markus Aswendt (markus.aswendt@uk-koeln.de)[![alt text][1.2]][1]

___
LICENSE
CC BY-NC-SA 4.0
<details>
<summary>REFERENCES</summary></b>

+ Allen Institute for Brain Science (2004). Allen Mouse Brain Atlas and Allen Mouse Spinal Cord Atlas. Available from mouse.brain-map.org. Allen Institute for Brain Science (2011). Source: [Allen Mouse Brain Atlas](https://mouse.brain-map.org/static/atlas), [Allen Mouse Spinal Cord Atlas](https://mousespinal.brain-map.org)
+ Allen Brain Reference Atlas: [Lein, E.S. et al. (2007). Genome-wide atlas of gene expression in the adult mouse brain, Nature 445: 168-176. ](https://doi:10.1038/nature05453), [Harris, J. A. et al. (2019). Hierarchical organization of cortical and thalamic connectivity. Nature 575, 195-202](https://doi:10.1038/s41586-019-1716-z), [Oh, Seung Wook, et al. "A mesoscale connectome of the mouse brain." Nature, 2014](https://www.nature.com/articles/nature13186)
+ AIDA<i>histo [Pallast, N., et al. "Atlas-based imaging data analysis tool for quantitative mouse brain histology (AIDAhisto)" Journal of Neuroscience Methods, 2019](https://www.sciencedirect.com/science/article/pii/S0165027019302511?via%3Dihub)
+ AIDA<i>mri [Pallast, N., et al. "Processing pipeline for Atlas-based Imaging Data Analysis (AIDA) of structural and functional mouse brain MRI" Frontiers in Neuroinformatics, 2019](https://www.frontiersin.org/articles/10.3389/fninf.2019.00042/full)
+ Incremental cell search [Meruvia-Pastor, Oscar E., et al. "Estimating cell count and distribution in labeled histological samples using incremental cell search" Journal of Biomedical Imaging, 2011](https://www.hindawi.com/journals/ijbi/2011/874702/)
