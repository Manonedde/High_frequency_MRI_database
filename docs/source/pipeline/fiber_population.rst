Fiber population analysis
==========================


The NuFO map is estimated from the number of local maxima of the fODF profile in each voxel. 
The intensity of each voxel corresponds to the number of fiber populations, 
ranging from 1 for the single fiber population to 2 and more for the multiple fiber populations 

    See `Dell'Acqua et al. 2009 <https://archive.ismrm.org/2009/3563.html>`_ and `Dell'Acqua et al. 2013 <https://doi.org/10.1002/hbm.22080>`_.

* NuFO averaged map

.. image:: ../results/averaged_maps/NuFO_gwm.gif 
   :width: 200                         


We apply two thresholds of 1 and ≥2 on the NuFO map to compartmentalize the “average” bundle 
(i.e., whole bundle) into “single” and “multi” fiber populations compartments, respectively. 
For this, each voxel of the whole and section masks for each bundle was sorted according to these two thresholds using `SCIL`_ scripts.

 .. _SCIL: http://scil.usherbrooke.ca/en/
 
.. image:: Fiberpopulation_mask.png
   :align: center


See section `Impact of fiber population: measures <https://high-frequency-mri-database-supplementary.readthedocs.io/en/latest/results/fiber_population_measures.html>`_ for measures distribution according to number of fiber population. 


See section `Impact of fiber population: consistency <https://high-frequency-mri-database-supplementary.readthedocs.io/en/latest/results/fiber_population_consistency.html>`_ for consistency according to number of fiber population. 


