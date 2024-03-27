#NYRFitness

To track my fitness progression from newyear 2024.


2 proposals. 
Please see detailed project plan

Concept:

Calorie_in = Food Intake
Calorie_Out = Daily_Locomotion+ Deliberate_Exercise + Basal_Metabolic_Rate

Function(Calorie_in,Calorie_Out)
  If Calorie_in>Calorie_out
    Return Gain
  elif Calorie_in == Calorie_out
    Return Net_Neutral
  Else
    Return Caloric Deficiet


Calorie In is defined by food intake, broken down into meal * Portion. Broken down into ingredients*Caloric Count per Unit

Calorie out is broken down into Daily Locomotion (API call from Garmin SmartWatch, Deliberate Exercise (Manually Tracked with Google sheet as csv into Local SQL Server), Basal Metabolic Rate based on Theoretical Calculation on BodyMass:Height:Gender numbers provided.
