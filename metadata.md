# Preliminary visualization of Tite-seq DMS data

This `dms-view` session presents a preliminary visualization of our DMS data on the 6m0j structure. You can alter the condition menu to display binding versus expression measurements. Raw binding values are measurements of the delta log<sub>10</sub>(*K*<sub>A,app</sub>) value of a single mutant relative to the wildtype binding, and expression values are delta mean fluorescence via fluorescent detection of a C-terminal epitope tag. 

On the site-wise metric panel, sites can be illustrated by the *mean* effect of mutations at the site on the binding or expression phenotype, or by the maximum or minimum effect of any of the 19 tested mutations.

For the mutation-level metrics illustrated in the logo plots, you can visualize the raw delta\_phenotype metric, though this visualization focuses the view on the largely deleterious mutations. The "relative\_effect" mutational metric is the exponentiated delta\_phenotype of a mutation, divided by the sum of the exponentiated delta\_phenotype of all 19 amino acid mutations at a site, thereby normalizing each site's logo stack from 0 to 1, and making more preferable amino acids have larger letter heights.
