# water_quality_dataset
The dataset consists of water quality measurements collected at Lac Hertel in [Mont Saint-Hilaire, Quebec](https://en.wikipedia.org/wiki/Mont_Saint-Hilaire). This data is collected using a Multiparameter Sonde, [Exo1 from YSI](https://www.ysi.com/exo1). The sensor was mounted on an autonomous surface vehicle to collect these data measurements.

**Date of Data Collection:** 12th of July 2018

**The measurement fields are as listed below,**

* %time --> global timestamp
* header_seq --> serial number of the measurement
* header_stamp --> timestamp
* stamp_sonde --> relative timestamp
* temp_c --> temperature in celcius
* spcond_u --> Specific Conductance, μS/cm
* sal --> Salinity, PPT
* ph --> pH
* orp --> ORP, mV
* depth_m --> Depth, m
* turbidity_ntu --> Turbidity, NTU
* turbidity_fnu --> Turbidity, FNU
* odo_percsat --> ODO, %Sat
* odo_m --> ODO, mg/L
* latitude --> Latitude of the sampling platform
* longitude --> Longitude of the sampling platform

**Sample plots of the data fields,**

Temperature in Celcius|  Ph | Conductivity (μS/cm)
:-------------------------:|:-------------------------:|:-------------------------:
![](https://user-images.githubusercontent.com/12105301/154365943-857e1f1b-6a09-4dcb-a84b-d74fe056f81a.png)  |  ![](https://user-images.githubusercontent.com/12105301/154365991-1df1aebd-8c22-46c1-9c17-62458c861ebf.png) |  ![](https://user-images.githubusercontent.com/12105301/154369013-38d51f39-188d-42fc-be28-8f8be121bc38.png) 


**Citation:**

**Acknowledgements:**
I, [Sandeep Manjanna](https://www.seas.upenn.edu/~msandeep/), would like to acknowledge the help from [Jeremy Mallette](https://mrcerealkiller.ninja/) in conducting field experiments at Lac Hertel for collecting this dataset. I would like to thank the administration at [Gault Nature Reserve](https://gault.mcgill.ca/en/) and McGill University for providing help with the facility and equipment.

Please cite this git repository and our paper if you are using this dataset for any kind of research. Citation details are provided above.

@inproceedings{malencia2022adaptive,
  title={Adaptive Sampling of Latent Phenomena using Heterogeneous Robot Teams (ASLaP-HR)},
  author={Malencia, Matthew and Manjanna, Sandeep and Hsieh, M Ani and Pappas, George and Kumar, Vijay},
  booktitle={2022 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  pages={},
  year={2022},
  organization={IEEE}
}
