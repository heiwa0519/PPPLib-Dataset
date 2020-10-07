**PPPLib Dataset**

PPPLib provides different dataset to evaluate its performance. This dataset contains three kinds of
data, namely static GNSS data, suburban vehicle data and urban data, which can be used to evaluate
the performance of PPP, PPK, GNSS/INS integration mode of the software. Note some data are
collected from the Internet, if you use the dataset, please cite related paper or indicate the source.
For mainland China users, please download the dataset using the [Baidu Cloud link (8888)](https://pan.baidu.com/s/1Yr5g9O_U52Wp7T_K2aPoqg).

* Static GNSS Data

 1. For PPP
    The GNSS observations are collected from IGS-MGEX stations on December, 1, 2019, with 30s sampling intervals,
    including station FAA1, HARB and SGOC. The dataset includes required files to performance PPP solutions.
    The static/kinematic-sim, single- to multi-constellation, single- to multi-frequency PPP results can be compared and
    analyzed using the PPPLib software. All files can be found in folder /data_mgex. You can use the configuration file
    in folder /conf/PPP/PPPLib_PPP_MGEX to perform this dataset.

    The software supports batch processing for PPP mode; thus, the batch processing dataset is also provided, which can
    be found in folder /data_batch. It is worth to note that the data storing in folder in according to certain rules.
    If you want to build your own batch folder, please follow this rule. You can use the configuration file in folder
    /conf/PPP/PPPLib_PPP_BATCH to perform this dataset. This dataset also can be used to perform PPP-AR mode.

 
 2. For PPK
    Short-baseline GNSS data are collected from [GNSS Research Centre at Curtin University]
    (http://gnss.curtin.edu.au/). GNSS observations on March, 6, 2020 from station CUAA and CUBB
    can be used to evaluate the performance of PPK mode. All files can be found in folder /data_cu.
 
* Suburban Vehicle Data
 
    This dataset is collected in a suburban environment with vehicle. The data collection platform is
    equipped with the GNSS (Trimble R10) and IMU (SPAN-CPT) sensors, together with accurate
    ground truth from SPAN-CPT system. This dataset can be used to evaluate the performance of the
    real-kinematic PPP, PPK and GNSS/INS integration mode. All files can be found in folder
    /data_cpt0.
 
*  Urban Data

 1. From Carvig: this dataset is collected from open-source project [carvig](https://github.com/Erensu/carvig). The dataset can be used to
    performance GNSS/INS loosely coupled and PPK/INS tightly coupled. Related files can be
    converted into a unified format for easy visualization using PPPLib but missing reference truth.
    All files can be found in folder /data_carvig.
 
 2. From [UrbanNav](https://github.com/weisongwen/UrbanNavDataset): this dataset is collected from open-source project UrbanNav. The data information can be
    found at website https://github.com/weisongwen/UrbanNavDataset. Related files can be
    converted into a unified format for easy visualization using PPPLib. All files can be found in
    folder /data_urban.
 