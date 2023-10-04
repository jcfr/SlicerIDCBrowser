[Work in progress] Slicer IDC Browser
===========

## About
IDCBrowser is a [3D Slicer](http://slicer.org/) extension for browsing and downloading DICOM files from [NCI Imaging Data Commons](https://imaging.datacommons.cancer.gov/).

Development of this extension was [initiated](https://projectweek.na-mic.org/PW39_2023_Montreal/Projects/SlicerIDCBrowser/) in June 2023. 

## Usage

Once the extension is published (it is not yet), you should be able to install it via 3D Slicer [Extensions Manager](https://slicer.readthedocs.io/en/latest/user_guide/extensions_manager.html). 

Once the extension is installed, it provides interface to choose from any of the imaging collections available in Imaging Data Commons, and select and download imaging data at the patient, study or series level. 

This extension relies on [`s5cmd`](https://github.com/peak/s5cmd) command line tool, which is installed by the extension, and is used to download images stored in DICOM format from the cloud-based storage buckets maintained by the IDC team.

**WARNING**: the extension is in its early stages, with the interface and features expected to evolve.

## Acknowledgments

This project has been funded in whole or in part with Federal funds from the National Cancer Institute, National Institutes of Health, under Task Order No. HHSN26110071 under Contract No. HHSN261201500003l.