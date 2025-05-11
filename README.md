# Moxifloxacin NHP PK Simulator

To run this R Shiny tool, download all files and open the file `app.r`

Then, you will see 4 pages to use:
- _PK Simulation by Weight_ - Here, you can give 2 groups of NHPs the same dose level and see the difference in PK profiles based on the two groups' average body weight
- _PK Simulation Given Sampling_ - Here, you can upload sampling data, and the app will estimate PK parameters and allow you to download a full PK profile for the monkey uploaded
- _PK Simulation with Threshold_ - Here, you give dosing parameters and average bodyweight, and can see the PK profile in relation to a given threshold concentration
- _PK AUC Simulation_ - Input body weight, dosing interval, and amount to see the area under the curve for given window lengths. You can download the dataset of AUC values.
<br>

In _PK Simulation Given Sampling_, you can upload one of the `.csv` files from the zip file `Example PK Data.zip` to see the profile generate for a theoretical NHP. You can then download the simulation, which can be used to interpolate PK sampling values to fully utilize serial QTc measurements that are taken during trials.
- Note: _PK Simulation Given Sampling_ will take some time to run. Please be patient, as it has to estimate post-hoc PK parameters and run the simulation for the given datapoints.
