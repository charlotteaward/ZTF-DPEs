# ZTF-DPEs
SDSS spectroscopy and ZTF+WISE light curves for the double-peaked emitters and broad-line AGN control sample presented in our paper on optically variable double-peaked emitters in ZTF. If using any of these intermediate data products in your own work, please cite the paper (https://arxiv.org/abs/2309.02516) as well as the relevant ZTF/WISE/SDSS survey papers.

Description of folders:

SDSSspectroscopy/ contains the SDSS spectra of the parent variable ZTF AGN sample after continuum subtraction with ppxf (https://academic.oup.com/mnras/article/466/1/798/2566728). The columns in each text file are wavelength (Angstroms), Flux (1e-17 * erg/s/cm^2/Ang), FluxError (1e-17 * erg/s/cm^2/Ang).

ZTFlightcurves/ contains the ZTF forced photometry of the full DPE+control AGN sample. The datafiles subdirectory contains the data (columns are described at the beginning of each file) and the pngs/ subdirectory contains plots of the combined optical and neoWISE photometry. 

WISElightcurves/ contains the W1 and W2 light curves of the DPE sample only. The columns are Mjd-58119, Mag (Vega mags) and Mag Error (Vega mags). 

Please see the paper for details about how these intermediate data products were generated.
