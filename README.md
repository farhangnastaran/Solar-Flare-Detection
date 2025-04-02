## Solar Flare Detection ##
Code private (active research project)

Summary

My ongoing research at the University of Sydney centers on the statistical characterization and modeling of solar flaring activity, with a focus SXR and EUV data. The project integrates observational data analysis, time series modeling, and machine learning techniques to improve flare detection and event classification. A key area of development is the application of a Hidden Markov Model (HMM) to identify the underlying magnetic states, i.e., background, rise, and decay phases, based on observations. The project extends to the use of Bayesian inference, Viterbi decoding, and parameter learning methods (including EM, GMM, and Dynamic Hamiltonian Monte Carlo) to improve HMM predictions. Synthetic data generation and injection-recovery tests are employed to validate the robustness of detection techniques.

Parallel efforts include:

	Temporal and spatial correlation analysis of EUV emission across active regions.
 
	Application of local extrema algorithms and continuous wavelet transforms for flare onset identification.
 
	Time series modeling using methods such as LOWESS, ARIMA, NIF, and RMSF to better capture flare dynamics.


This research contributes to a more refined understanding of solar flare statistics and aims to support the development of reliable, automated flare prediction frameworks with potential implications for space weather forecasting.

Key Libraries and Tools Used in This Project

Scientific Computing and Data Handling
- NumPy, SciPy, Pandas, xarray: Core libraries for numerical computation, statistical operations, and handling multidimensional datasets.
- netCDF4, h5py, h5netcdf, zarr: Reading and writing large scientific data formats (e.g., EUV and SXR data).
- dask: Parallel computing and efficient handling of large arrays and dataframes.
- astropy, sunpy, aiapy, drms, ChiantiPy: Domain-specific libraries for solar physics, astrophysical data structures, and spectral line analysis.

Statistical Modeling & Inference
- statsmodels, pymc3, Theano-PyMC, cmdstanpy, numpyro, arviz: Tools for Bayesian modeling, Markov Chain Monte Carlo (MCMC), and probabilistic inference.
- lifelines: Survival analysis (time-to-event modeling).
- formulaic, patsy: For constructing design matrices from formulas (like R-style statistical models).

Time Series Analysis and Signal Processing
- PyWavelets, ruptures, dtaidistance, filterpy, pystan: For analyzing time series, change point detection, wavelet transforms, and Kalman filtering.
- LOWESS, ARIMA, RMSF methods (custom-implemented or through libraries).

Machine Learning & AI
- scikit-learn, hmmlearn, pomegranate, autograd, jax, tensorflow, keras, torch: For classification, clustering, regression, HMMs, deep learning, and symbolic differentiation.
- BNLearn, pgmpy, miniKanren: For probabilistic graphical models and logical inference.

Data Preprocessing, Cleaning & Utility
- jsonschema, jsonpointer, pyerfa, asciitree, yaml, requests, xmltodict: Utilities for data validation, web queries, and structured data manipulation.
- beautifulsoup4, lxml, soupsieve: Web scraping and HTML/XML parsing.

Visualization
- matplotlib, seaborn, corner, plotly, pyqtgraph, mpl-animators, tabulate: Visualizing distributions, time series, trace plots, corner plots, animations, and interactive GUIs.

Development, Notebooks, & Productivity
- Jupyter, IPython, IPyWidgets, nbconvert, jupyterlab, jupyterlab-server: For interactive computing and scientific documentation.
- Flask, PySimpleGUI, SpeechRecognition: Lightweight web apps, simple GUIs, and basic voice-based interaction.
- virtualenv, pip, conda, setuptools: Environment and dependency management.


Project Metadata & Notes
- Total Python packages used: ~230
- Environment managed via: "venv" and "pip freeze"

[requirements.txt] included for environment reconstruction.



