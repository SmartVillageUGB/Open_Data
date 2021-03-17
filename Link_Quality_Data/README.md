# Open data
## LoRa link quality

A (LoRa) network link quality can be assessed through two main metrics:  the SNR and the RSSI. The two datasets contain SNR and RSSI measurements collected in various distances in different environments. The [first dataset](csv/snr_rssi_gps_data_100.csv) is for short distances signal chareacterization for a LoRa network. It contains SNR and RSSI values in different distances between 0 and 100 meters. The [second data](csv/rssi_distance_pau_ndar.csv) is collected from wider deployments (up to 4km) in different environment in PAU (France) and Saint-Louis (Senegal). These datasets can be use for designing LoRa network deployment planning tools using path-loss model or for distance estimation methods that are based RSSI and SNR values. They can be also used for research purposes in LoRa signal characterization or for LoRa simulator design.

## Data coverage
Date from: 20-08-20\
Date to: 20-08-26

## Parameters
Below are the supported parameters :
- SNR Signal-to-Noise Ratio
- RSSI Reaceived Signal Strength Indicator (dBm)
- Distance (m)
- Classe classe (interval) of distance (e.g. class0_4_7 means class number 0 that contains RSSI and SNR values collected between distances of 4m and 7m)
- LAT Latitude
- LGT Longitude



These data has been published under the Open data initiative from the Smart Village Living Lab, in the context of the Wazihub project (www.wazihub.com), partenered with Sonatel, Orange, and University Gaston Berger of Saint-Louis.

