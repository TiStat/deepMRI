# GridMRI
Cleaning Magnetic Resonance Images (MRI) from undersampling artifacts with Deep Convolutional Neural Networks - A grid search on Unet and implicit variants such as DnCNN

U_grid.py expands the cartesian parameter grid and pickles it. The pickled gridfile must have U_gridexec name and be in the same directory.
U_gridexec.py is the main execution script. The scalable Unet version can be found with U_model_fn.
