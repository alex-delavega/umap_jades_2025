# umap_jades_2025
de la Vega et al. (2025) searched for quiescent galaxies over 3 < z < 6 in the publicly available JWST dataset JADES (Rieke et al. 2023; Eisenstein et al. 2023a; 2023b; D'Eugenio et al. 2024) using the Uniform Manifold Approximation and Projection machine-learning algorithm (UMAP, [McInnes et al. 2018](https://arxiv.org/abs/1802.03426)). This repository contains a jupyter notebook (umap_jades_2025.ipynb) that can be used to reproduce Figures 2 through 4 in de la Vega et al. (2025), which involve training the UMAP algorithm on a mock dataset (JAGUAR, [Williams et al. 2018](https://ui.adsabs.harvard.edu/abs/2018ApJS..236...33W/abstract)), selecting a parent sample of galaxies, projecting the parent sample onto the UMAP visualization, and pre-selecting candidate pools that contain high-redshift quiescent galaxies. 

The repository also contains a catalog of physical properties derived by fitting the HST+JWST spectral energy distributions (SEDs) of 2,282 galaxies. The fits were performed using the Bayesian SED-fitting tool BAGPIPES ([Carnall et al. 2018](https://ui.adsabs.harvard.edu/abs/2018MNRAS.480.4379C/abstract)). The catalog lists the JADES IDs, redshifts and provenances thereof, instantanous specific star-formation rates (sSFRs), stellar masses, SFRs averaged over the last 100 Myr, dust attenuations in the rest-frame _V_ band (Av), and mass-weighted ages. For each quantity after the redshifts, the 16th, 50th, and 84th percentiles of the posteriors are provided in columns ending in "_16," "_50," and "_84," respectively. For more details, please see Sec. 4.4 in de la Vega et al. (2025). 
