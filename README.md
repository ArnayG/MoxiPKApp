# Moxifloxacin NHP PK Simulator

To run this R Shiny tool, download all files and open the file `app.r`

Then, you will see 4 pages to use:

1. _PK Simulation by Weight_ - Here, you can give 2 groups of NHPs the same dose level and see the difference in PK profiles based on the two groups' average body weight
<img width="1000" alt="image" src="https://github.com/user-attachments/assets/f0023b6d-1fe5-4ce3-9fce-f6fd0f8b333a" />
<br><br><br>

2. _PK Simulation Given Sampling_ - Here, you can upload sampling data, and the app will estimate PK parameters and allow you to download a full PK profile for the monkey uploaded
<img width="1000" alt="image" src="https://github.com/user-attachments/assets/902f1837-e8b6-43e0-b451-a78dce2dc4ad" />
<br><br><br>

3. _PK Simulation with Threshold_ - Here, you give dosing parameters and average bodyweight, and can see the PK profile in relation to a given threshold concentration
<img width="1000" alt="image" src="https://github.com/user-attachments/assets/bf076a07-7191-4128-847e-0c059378bb5f" />
<br><br><br>

4. _PK AUC Simulation_ - Input body weight, dosing interval, and amount to see the area under the curve for given window lengths. You can download the dataset of AUC values.
<img width="1000" alt="image" src="https://github.com/user-attachments/assets/658ba2b1-8bf9-49d9-81ec-f0178eb57c84" />
<br><br><br>

<br>



In _PK Simulation Given Sampling_, you can upload one of the `.csv` files from the zip file `Example PK Data.zip` to see the profile generate for a theoretical NHP. You can then download the simulation, which can be used to interpolate PK sampling values to fully utilize serial QTc measurements that are taken during trials.
