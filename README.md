In this repo there are two datasets: "Initial_dataset_maritime_medical_records.xls" and "Preprocessed_Dataset.xls". &nbsp;


**Initial_dataset_maritime_medical_records.xls** &nbsp;


This dataset was collected in Italy, so the values in the data are in Italian. The name of the features are translated in English. &nbsp; 

* PATIENT_ID: unique identifier (C1_ for Company1, C2_ for Company2)
* Sex	: Sex of the worker
* Age	: Age at visit data
* Visit Data 
* Job	
* Weight 	
* Height 	
* Smoker : smoker habits: Smoker (Fumatore), Ex-Smoker, Not Smoker (Non Fumatore)	
* Number Of Cigarettes : the numbers of the cigarettes smoked for day
* Electronic Cigarette	
* Smoke Since	: Time when the smoker began smoking 
* Smoke To : Time when the smoker stopped smoking
* Allergies
* Allergies' sympthoms	
* Type of Visit : in this column there is the type of visit like: periodic visit(visita periodica), Audiometry (audiometria), Spine assessment (Esame obiettivo del rachide)	
* Outcome : the results of the type of visit


&nbsp;
**Preprocessed_Dataset.xls** &nbsp;


This is the preprocessed dataset.
* AGE	
* Audiometry Class	: The class of damage categorizes the type and origin of hearing loss.
* Audiometry Score%: The score of damage quantifies the severity of hearing impairment. In this case we have a percentege score. 	
* BMI	
* Fitness for work: Binary feature indicating Fit or Unfit for a specific Job. Fit:1 Unfit:0	
* Job	
* PATIENT_ID: unique identifier (C1_ for Company1, C2_ for Company2)	
* Sex	
* Smoker:smoker habits: Smoker, Ex-Smoker, Not Smoker
* Job Category: indicates the sector in which the job falls in Job feature. The used classification is the following:
  - Deck Officers = chiefmate, 2ndmate, 3rdmate, boatswain, ordinaryseaman, deckcadet, deckofficer, bosun, deckboy
  - Engineering Positions = chief engineer, 1st engineer, 2n dengineer, 3rd engineer, 4th engineer, engineer deck, engineer, engine officer, engineer officer, ufficiale di macchina, engine rating, enginee rating
  - Engineering Department = fitter, oiler, greaser, wiper, plumber, utilityman, motorman, pumpman, machinist, electrician, refrigeration engineer, tankerman, engineer cadet
  - Professional Certifications and Credentials = able seaman, able deck seaman, able seafarer engine, able seafarer deck
  - Shipyard Jobs = electrician, electrician assistant, treinee electrician, electrotechnical officer, driver, carpenter, trainee electrician
