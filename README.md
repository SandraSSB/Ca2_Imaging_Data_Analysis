# Calcium imaging data analysis pipeline
<p align="center">
  <img width="207" height="560" alt="Logo github_contorno blanco" src="https://github.com/user-attachments/assets/3db553d2-70ce-4293-9615-1e3fbb88950c" />
</p>

Scripts (Python language) to analyze in vivo Ca2+ imaging data acquired through a one-photon miniscope set onto freely moving mice 🐁
-----------------------------
This pipeline works with the calcium signals already extracted from recordings through any package (e.g. CNMF-E, PCA-ICA...). Please, adjust the names of the columns in the csv file(s) to match with some terms used in the scripts (e.g. 'Time(s)' or 'Cell Name') or vice versa, adjust the terms in the scripts to match with the ones in your csv file(s).

-----------------------------

👉[1. Area Under the Curve (AUC) calculation for specific time window](https://github.com/SandraSSB/Ca2_Imaging_Data_Analysis/blob/main/Scripts/Area%20Under%20the%20Curve/AUC%20calculation)

👉[2. AUC bar graph showing the mean and the AUC of each cell individually](https://github.com/SandraSSB/Ca2_Imaging_Data_Analysis/blob/main/Scripts/Area%20Under%20the%20Curve/AUC%20calculation)
<p align="center">
  <img width="1778" height="450" alt="AUC" src="https://github.com/user-attachments/assets/bf3ad8f4-b1f3-400c-a3a8-0bb2f20b8c2c" />
</p>


-----------------------------

👉[3. Calculation of Ca2+ event rates](https://github.com/SandraSSB/Ca2_Imaging_Data_Analysis/blob/main/Scripts/Calcium%20events/Event%20rates)

👉[4. Histogram showing the number of cells for each event rate range](https://github.com/SandraSSB/Ca2_Imaging_Data_Analysis/blob/main/Scripts/Calcium%20events/Histogram%20Ca2%2B%20event%20rates)
<p align="center">
  <img width="1394" height="450" alt="histogram" src="https://github.com/user-attachments/assets/82fcf967-ddbc-47ec-a6ff-051f687aaed7" />
</p>

👉[5.Raster plot representing Ca2+ events](https://github.com/SandraSSB/Ca2_Imaging_Data_Analysis/blob/main/Scripts/Calcium%20events/Raster%20plot%20Ca2%2B%20events)
<p align="center">
  <img width="1000" height="444" alt="rasterplot" src="https://github.com/user-attachments/assets/6b7314d8-eeaf-4df5-8728-afca7d80cd79" />
</p>

-----------------------------
👉[6. Calculation of different statistics from your calcium signals data (mean, median, standard deviation, skewness, coefficient of variation, mean amplitude)](https://github.com/SandraSSB/Ca2_Imaging_Data_Analysis/blob/main/Scripts/Statistics%20and%203D%20plot/Statistics)

👉[7. 3D Plot representing cells distribution based on (up to) 4 parameters](https://github.com/SandraSSB/Ca2_Imaging_Data_Analysis/blob/main/Scripts/Statistics%20and%203D%20plot/3D%20Plot)
<p align="center">
  <img width="900" height="700" alt="3Dplot" src="https://github.com/user-attachments/assets/e1e4a57c-1dda-4869-b704-6458fe7c1549" />  
</p>
