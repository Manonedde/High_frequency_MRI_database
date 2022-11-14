MRI Processing
=================

Tools
---------------

Tools used for all MRI images processing are available on `SCIL github <https://github.com/scilus>`__.
See https://scil-documentation.readthedocs.io/ for installation and documentation.


 - For DWI and T1 processing we used `Tractoflow <https://github.com/scilus/tractoflow>`__ and `NODDI <https://github.com/scilus/noddi_flow>`__
 
 - For ihMT processing we used `ihMTflow <https://github.com/scilus/ihmtflow>`__

.. image:: pipeline_summary.png
   :align: center
   :width: 700



Metrics generated
-----------------
Table describe all metrics maps which will be evaluated.

+-------------------------------+-------------------------------------------+
| Tools                         | Generated images                          |
+===============================+===========================================+
| Tractoflow - DTI              | Fractional anisotropy (FA)                |
+-------------------------------+--------------------+----------------------+
|                               | Mean Diffusivity (MD)                     |
+-------------------------------+--------------------+----------------------+
|                               | Radial Diffusivity (AD)                   |
+-------------------------------+--------------------+----------------------+
|                               | Axial Diffusivity (AD)                    |
+-------------------------------+--------------------+----------------------+
| Tractoflow - HARDI            | Apparent fiber density total (AFD total)  |
+-------------------------------+--------------------+----------------------+
|                               | Number of fober direction (NuFO)          |
+-------------------------------+--------------------+----------------------+
| NODDI flow                    | Intra-cellular volume fraction (ICvf)     |
+-------------------------------+--------------------+----------------------+
|                               | Extra-cellular volume fraction (ECvf)     |
+-------------------------------+--------------------+----------------------+
|                               | Isotropic volume fraction (ISOvf)         |
+-------------------------------+--------------------+----------------------+
|                               | Orientation direction (OD)                |
+-------------------------------+--------------------+----------------------+
| ihMT flow                     | ihMT ratio (ihMTR)                        |
+-------------------------------+--------------------+----------------------+
|                               | ihMT delta R1 saturation (ihMTdR1sat)     |
+-------------------------------+--------------------+----------------------+
|                               | MT ratio (MTR)                            |
+-------------------------------+--------------------+----------------------+
|                               | MT saturation (MTsat)                     |
+-------------------------------+--------------------+----------------------+


Quality Control
---------------

After processing, all resulting maps are check using `DMRI QC <https://github.com/scilus/dmriqc_flow>`__.




  See section `Averaged measures in common space <https://high-frequency-mri-database-supplementary.readthedocs.io/en/latest/results/average_maps.html>`_   for an overview of each measurement. 

  See section `MRI quantitative measures <https://high-frequency-mri-database-supplementary.readthedocs.io/en/latest/results/measure.html>`_ for the    distribution of measurements.


