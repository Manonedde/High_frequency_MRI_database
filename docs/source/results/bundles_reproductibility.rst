Bundles reproductibility
========================

The reproducibility of the bundles is performed using the method described in `Rheault et al. 2022 <https://doi.org/10.1002/hbm.25777>`_ (see also `Rheault et al. 2020 <https://doi.org/10.1002/hbm.24917>`_), and generated the following reproducibility metrics: 

  * Dice scores used to check for volume overlap of all bundles over session.
  * Density correlation at the voxel-level for streamline density of all bundles over session.
  * Streamlines and voxels adjency used to evaluate distance between streamlines (or voxels) over session.
  
  
See section `Bundles <https://high-frequency-mri-database-supplementary.readthedocs.io/en/latest/pipeline/bundles.html>`_ for the method.


.. note::

   The plots are interactive, click on the elements of the legend to select and/or deselect the elements.
   Colors represents the bundle. Each dot represents reproducibility metric for one participant and session.


Dice scores
------------------------

.. raw:: html
  :file: bundles_reproductibility/dice_scores.html
  
  
  
Correlation between Density Map
---------------------------------

.. raw:: html
  :file: bundles_reproductibility/correlation_density.html



Streamlines Adjency
------------------------

.. raw:: html
  :file: bundles_reproductibility/adjency_streamlines.html
  
  
 
Voxels Adjency
------------------------

.. raw:: html
  :file: bundles_reproductibility/adjency_voxels.html
  
  
