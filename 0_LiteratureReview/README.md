# Literature Review

Approaches or solutions that have been tried before on similar projects.

**Summary of Each Work**:

- **Source 1**: [Deep Learning for Satellite Image Time Series Analysis]

  - **[Link](https://arxiv.org/pdf/2404.03936)**
  - **Objective**: Review paper that is intended to provide a resource for remote sensing experts interested in deep learning techniques.
  - **Methods**: State-of-the art methods for Satellite Image Time Series (SITS) are introduced and discussed (paper is from 2023).
  - **Outcomes**: Deep learning can capture complex relationships between Earth Observation variables, outperforming other machine learning and 
statistical learning techniques. 
  - **Relation to the Project**: This paper provides a guideline how satellite-derived Earth Observation variables and deep learning techniques can effectively combined. Particularly, it gives an overview of available satellite missions and neural network architectures, which are relevant for our proposed project.

- **Source 2**: [Application of Deep Learning Architectures for Satellite Image Time Series Prediction: A review]

  - **[Link](https://www.mdpi.com/2072-4292/13/23/4822)**
  - **Objective**: Another recent review paper that highlights Deep Learning applications for SITS. The important difference to Source 1 is that this study focuses on predictions, rather than on a general overview. 
  - **Methods**: Deep learning architectures, data, optimization functions and evaluation metrics are reviewed.
  - **Outcomes**: Existing deep learning-based methods can be divided in three categories: recurrent neural networks, hybrid models and convolutional neural networks. The study also points out future challenges, for example, the like lack of available training datasets or the difficulty to generalize or reuse models.
  - **Relation to the Project**: Amongst the examples, where SITS prediction has been applied, this paper provides more in-depth information on architecture, datasets, weakness and advantage and selected optimizers for many cases studies.
  - 
- **Source 3**: [Detection of Subtle Thermal Anomalies: Deep Learning Applied to the ASTER Global Volcano Dataset]

  - **[Link](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10032629)**: 
  - **Objective**: Development and evaluation of a deepl learning approach, specifically using a U-Net convulutional neural network, for the automated detection of subtle volcanic thermal anomalies in ASTER thermal infrared (TIR) satellite imagery, thereby enhancing global volcano monitoring capabilities.
  - **Methods**:
  - Compiled a dataset of 1,500 labeled ASTER TIR images from five active volcanoes (time-series): Etna (Italy), Popocatépetl (Mexico), Lascar (Chile), Fuego (Guatemala), and Kliuchevskoi (Russia).
  - Trained a supervised U-Net model to identify thermal anomalies by learning spatial patterns associated with volcanic activity.
  - Validated the model's performance on unseen data, including images from Vulcano Island (Italy), to assess generalization capabilities.
  - **Outcomes**:
  - The U-Net model achieved a detection accuracy of 93%, effectively identifying both prominent and subtle thermal anomalies.
  - Demonstrated the model's ability to generalize across different volcanic settings and activity levels.
  - Highlighted the potential for integrating this approach into global volcanic monitoring systems, especially in remote or inaccessible regions lacking ground-based observations.

  - **Relation to the Project**: This study could be directly relevant to the project if we focuse on detecting anomalies around volcanoes. It provides a robust, automated method for identifying thermal precursors to volcanic activity, which can be instrumental in early warning systems and risk mitigation strategies.

- **Source 4**: [Forecasting, detecting, and tracking volcanic eruptions from space]

  - **[Link](https://doi.org/10.1007/s41976-020-00034-x)**
  - **Objective**: The objective of the paper is to review how satellite remote sensing can be used to forecast, detect, and track volcanic eruptions, with focus on regions without land based volcano monitoring. It reviews four key types of satellite observations: ground deformation, gas emissions (SO₂), thermal anomalies  and ash plumes. Using datasets like InSAR (Sentinel-1, ALOS-2), MODIS, TROPOMI and geostationary weather satellites.
  - **Methods**: Review and evaluate existing satellite remote sensing techniques for volcanic monitoring. The paper describes how existing satellite data (InSAR for ground deformation, UV/IR sensors for gas emissions, thermal infrared for heat anomalies and multispectral imagery for ash plumes) are applied to monitor and analyze volcanic activity.
  The authors combine previously published results. Ground deformation using metrics such as line of sight (LOS) displacement, pixel tracking, interferometric coherence for surface changes and topographic differences from repeated digital elevated models to estimate lava thickness or effusive volume. Gas emission datasets, especially for SO₂ are derived from UV and IR sensors such as Ozone Monitoring Instrument (OMI), Tropospheric Monitoring Instrument. (TROPOMI) and Infrared Atmospheric Infrared Sounder (IASI) and expressed in Dobson units or g/m². Thermal anomalies are detected using radiation measurements with a focus on the middle infrared (MIR) and thermal infrared (TIR) bands, saturation thresholds and sub-pixel hotspot modeling. To detect ash clouds, brightness temperature differences in IR bands from geostationary satellites are used.
  - **Outcomes**: Forecasting, detecting and tracking volcanic eruptions is extremely effective, especially for remote or unmonitored volcanoes. It is highlighted that the combination of several types of satellite data, regarding deformation, gas emissions, thermal anomalies and ash detection - is essential for accurate monitoring. The practical application of this approach is demonstrated in a case study of the Agung volcano. Challenges like limited coverage and the need for automated analysis are also highlighted and possibilities for future improvements are outlined.
  - **Relation to the Project**: The paper supports our project by reviewing how satellite based data of gas emissions, thermal anomalies and deformation can be used as precursors of volcanic eruptions. It fits with our goal of using remote sensing indicators such as vegetation changes for eruption forecasting/detection.
