# Segmentation_EB
new segmentation routine used for FSD and accurate floe characteristics. Used for the floe size distribution in:

Buckley, E. M., Cañuelas, L., Timmermans, M.-L., and Wilhelmus, M. M.: Seasonal Evolution of the Sea Ice Floe Size Distribution from Two Decades of MODIS Data, EGUsphere [preprint], https://doi.org/10.5194/egusphere-2024-89, 2024.

The floe size distribution used in the paper generated from this segmentation algorithm can be found here: https://doi.org/10.5281/zenodo.11553699

The files in this repository include:
- Segmentation_EB.ipynb - example notebook with commented seg algorithm code
- modis_download_short.ipynb -  example notebook showing how to quickly download modis data for the inputs to the segmentation algo
- input
  - cloud - files for cloud mask
  - tci - images for analysis
- output
  - sample output
