<h1>TissuePlot </h1>
<p>
TissuePlot is a web application for visualizing spatial datasets using a hexagon tessellation approach that does not obscure the underlying tissue. If you use our tool please cite:
<br/>
Khawatmi M., and Sailem H., TissuePlot: A Multi-Scale Interactive Visualization Tool for Spatial Data. bioRxiv
</p>

<p>
In TissuePlot, you can view the proportion of different cell types at each spot, gene levels, as well as any cluster information. For all these views, the user can show or hide the underlying tissue image.
</p>

<p>
The current implementation is tested on Visium data from <a href='https://github.com/BayraktarLab/cell2location'>Kleshchevnikov et al., 2022</a> and <a href='http://biovis.net/2024/biovisChallenges_vis/'>Bio+MedVis Challenge @ IEEE VIS 2024</a>. That includes:
</p>
<ul>
<li>	Tissue image: an H&E image of the tissue (e.g. image.png)</li>
<li>	Spot positions file: the corresponding location of each spot on the TissueImage (e.g. SpotPositions.csv)</li>
<li>	Spot cluster membership: The percentage of different cell types at each spot based on cell deconvolution techniques (e.g. SpotClusterMembership.csv). This file can also contain ‘Cluster’ column to indicate spot cluster based on gene expression data, cell proportion profiles, or other orthogonal data</li>
<li>	Gene expression file: RNA counts at each spot. It is preferred that only top-expressed genes are uploaded for optimal performance (e.g. TopExpressedGenes.csv).</li>
</ul>  
