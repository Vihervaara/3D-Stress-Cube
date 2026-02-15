![Logo](https://github.com/Vihervaara/3D-Stress-Cube/blob/main/3DstressCube_Logo.png)

## Welcome to 3D Stress Cube. 


__INFO__


3D Stress Cube is a simple visualisation tool that can be opened in a web browser. 
It displays expression changes in polyA+ RNA upon three protein damaging stress conditions



__USAGE__


1) Download File_S1.zip
2) Unzip the downloaded File_S1.zip file
3) Navigate into the opened folder
4) Open the 3D_stressCube_minDistance_1p5.html file in a web browser

The 3D Stress Cube allows rotation and zooming. Each data point represents an RNA. Pointing the cursor on a datapoint displays an infobox.



__RNA expression changes__


The 3D Stress cube compares stress-induced changes in polyA+ RNA expression caused by three proteo-toxic conditions in mouse striatal muscle:
- HS: Heat Shock (42°C)
- i90: HSP90 inhibition (HSP990)
- R6: polyQ aggregation (R6/2 mouse model of Huntington's Disease)

The three axes (x, y, and z) show log2foldChanges upon the respective stress.
- log2(HS / NHS)
- log2(90i / Ci)
- log2(R6 / WT)
NHS = non heat shock control
Ci = vector control for HSP990




__ORIGINAL WORK__


The original data is from Neueder et al., 2017 (PMID: 28465506) in mouse striatal muscle (WT and R6/2 mice).

The analysis and the 3D Stress Cube are described in Rabenius et al., 2026 (PMID: 41619802).
- The 3D Stress Cube provided for browsing contain RNAs with a minimum of total log2FC 1.5
- The Original article (PMID: 28465506) provides a Supplememntal Dataset with all expressed RNAs.



__CITATION and further information__

Rabenius et al., 2026, Cell Stress Chaperones (PMID: 41619802)
https://doi.org/10.1016/j.cstres.2026.100146



