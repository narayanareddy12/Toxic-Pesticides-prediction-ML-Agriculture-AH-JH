# The-Toxic-Pesticides-ML-Agriculture-AH-JH


**The Toxic Pesticides**

Though, many of us don't appreciate much, but a farmer's job is real test of endurance and determination. Once the seeds are sown, he works days and nights to make sure that he cultivates a good harvest at the end of season. A good harvest is ensured by several factors such as availability of water, soil fertility, protecting crops from rodents, timely use of pesticides & other useful chemicals and nature. While a lot of these factors are difficult to control for, the amount and frequency of pesticides is something the farmer can control.

Pesticides are also special, because while they protect the crop with the right dosage. But, if you add more than required, they may spoil the entire harvest. A high level of pesticide can deem the crop dead / unsuitable for consumption among many outcomes. This data is based on crops harvested by various farmers at the end of harvest season. To simplify the problem, you can assume that all other factors like variations in farming techniques have been controlled for.

You need to daetermine the outcome of the harvest season, i.e. whether the crop would be healthy (alive), damaged by pesticides or damaged by other reasons.



**Data Description**

Variable	Definition

ID	UniqueID

Estimated_Insects_Count	Estimated insects count per square meter

Crop_Type	Category of Crop(0,1)

Soil_Type	Category of Soil (0,1)

Pesticide_Use_Category	Type of pesticides uses (1- Never, 2-Previously Used, 3-Currently Using)

Number_Doses_Week	Number of doses per week

Number_Weeks_Used	Number of weeks used

Number_Weeks_Quit	Number of weeks quit

Season	Season Category (1,2,3)

Crop_Damage	Crop Damage Category (0=alive, 1=Damage due to other causes, 2=Damage due to Pesticides)


sample_submission.csv

ID: Unique ID

Crop_Damage: Predicted Crop damage category for the test set 





**Evaluation Metric:**
The evaluation metric for this hackathon is Accuracy Score.


https://datahack.analyticsvidhya.com/contest/janatahack-machine-learning-in-agriculture/#ProblemStatement
