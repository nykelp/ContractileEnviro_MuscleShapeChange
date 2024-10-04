# ContractileEnviro_MuscleShapeChange
Data files for JEB article Effects of altered contractile environment on muscle shape change in the triceps surae

This repository contains one csv file:
 EXCON_Hold_data_level_v2



**EXCON_Hold_data_level_v2** contains data used within the manuscript to produce the statistical analysis and figures.
Data is organized by subject (S01, S04...etc), muscle (LG, MG, SOL = lateral gastrocnemius, medial gastrocnemius, soleus), condition (KB=knee flexed, KS= knee extended), level (30% SOL EMG and 60% SOL EMG).
- Standard height, weight, leg dominance, age and gender included.
- sol_under defines which gastrocnemius muscle the Soleus was imaged under during the protocol
- maximum torque, torque at 30% and 60% for the knee flexed and knee extended condtions
- FL_mm = resting fascicle length in mm at each condition, PA_deg= resting pennation angle, TH_mm= resting muscle thickness
- FLc_per and THc_per= Change in Fascicle length and Change in Muscle thickness from resting to the hold portion of the contraction, as a percentage or resting (strain)
- PAc_deg.= Change in pennation angle from resting to the hold of the contraction
- FLa_mm and THa_mm= Change in fascicle length and muscle thickness as an absolute millimeter value ( this was not used in the paper or statistics as between conditions can not be compared considering there were different resting FL and TH values for each condition)
- THmax_mm= Absolute change in muscle thickness at any time point during the contraction ( not just at hold) - used for data exploration but not included within paper
- emg= smoothed and filtered emg values during the hold portion of the contraction ( emg trials only) hence why there are values for all 3 muscles
- us_emg= SMoothed and filtered emg values during the hold portion of the contraction (ultrasound trials only) could only capture MG and SOL ( sol is the average of the medial and lateral soleus EMG data). 
  
Statistical Analysis was conducted in R Studio

