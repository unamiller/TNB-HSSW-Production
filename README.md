# TNB-HSSW-Production
Code and demo data accompanying the manuscript *High Salinity Shelf Water production in Terra Nova Bay, Ross Sea from high-resolution near-surface salinity observations*, currently under review.

Una Kim Miller, Christopher J. Zappa, Arnold L. Gordon, Seung Tae Yoon, Craig Stevens, Won Sang Lee

License: Apache 2.0 License

## 1. System requirements

This code runs easily on a laptop computer with the following specs:

RAM: 16 GB <br>
CPU: 6 cores, 2.6 GHz/core

## 2. Installation guide

This code is written in Python (version 3.8.8) and executed in Jupyter Lab, both of which are easily installed using the Anaconda Python distribution (<https://www.anaconda.com/>). Anaconda setup typically takes less than 10 minutes.
<br>
### Package dependencies
The following packages are required to run this code:
- numpy 
- xarray 
- matplotlib 
- pandas 
- scipy
- gsw (Gibbs SeaWater)

The specific versions of these packages used in the present code are contained in the TNB_demo_environment.yml file, which can be loaded in as:

`conda activate TNB_demo`

## 3. Demo

`P_HSSW_from_mooring.ipynb` is a notebook showing an example calculation of HSSW production rate from moored salinity. <br>
`P_HSSW_from_net_heat_fluxes.ipynb` is a notebook showing the calculation of HSSW production rates from net heat fluxes in TNB across 2012-2021. Generates Figure 5 of the manuscript. <br>

### How to run the code
- Open either `.ipynb` file in Jupyter Lab/Notebook. From the `Run` tab, select `Run All`. Runtime = ~5 seconds

