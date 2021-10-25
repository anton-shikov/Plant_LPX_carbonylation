


# Post-anoxic oxidative injury is more severe than oxidative stress induced by chemical agents in wheat and rice plants.
A repository with working scripts for Acta Physiologiae Plantarum 2021 paper.


<img src="https://github.com/anton-shikov/Plant_LPX_carbonylation/blob/main/Pics/FIgure_5_2_blots.png" width="533" height="266">
<img src="https://github.com/anton-shikov/Plant_LPX_carbonylation/blob/main/Pics/Figure_4.png" width="533" height="366">

## Contents 
This repository contains scripts used for statistical analysis of the data for the manuscript and raw data as well. Please consult the Methods section in the paper for extra details. 

## Figures
Figures are available in the <i> Pics/ </i> directory. For the description please consult the Results section of the article.

## Supplementary tables
Supplementary tables are available in the <i> Supplementary_data/ </i> directory. The description of the tables is embedded into the Exel table.

## Scripts
Scripts are available in the <i>Scripts/</i> directory.
<ul>
  <li><em> ROS_stat_clean.R</em> - evaluates difference between treatments and plants using pairwise Wilcox test and Kruskal-Wallis test on the basis of the data of lipid peroxidation and protein carbonylation measured spectrophotometrically;</li>
  <li><em> WB_clean.R</em> - evaluates difference between treatments and plants using pairwise Wilcox test and Kruskal-Wallis test using on the basis of relative protein carbonylation taken from Western blots.</li>
</ul>

## Raw data
Raw data is available in the <i>Raw_data/</i> directory.
<ul>
  <li><em> Carbonylation</em> - the directory contains spectrophotometrically measured carbonylation data;</li> 
<ul>
<li> <em> Agents </em> - the directory contains data for treatments with oxydative agents; </li> 
  <li><em> Reaeration </em> - the directory contains data for treatments with anoxic conditions followed by re-aeration.</li>
 </ul>
 
  <li> <em> Lipid_peroxidation</em> - the directory contains spectrophotometrically measured lipid peroxidation data;</li> 
<ul>
<li> <em> Agents </em> - the directory contains data for treatments with oxydative agents; </li>
  <li><em> Reaeration </em> - the directory contains data for treatments with anoxic conditions followed by re-aeration.</li>
</ul>

  <li> <em> Western</em> - the directory contains protein carbonylation data based on Western blotting results.</li> 
</ul>
