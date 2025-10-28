Setting Up The Project

Install VSCode
Install Python
Extract the folder sent
Open Folder -> Braininj
open terminal
cd tbi_prognosis
env/Scripts/activate
pip install -r requirements.txt
python manage.py runserver


For Output
http://127.0.0.1:8000/


Sample Inputs and Outputs

Inputs Resulting in Critical State
1. Input 1:  
   - **Age**: 70  
   - **Time Since Injury**: 6 hours  
   - **GCS**: 7  
   - **GOS**: 2  
   - **Output**:  
     - **Prognosis State**: *Critical state*  
     - **Mortality Prediction**: High risk of mortality.  
     - **Morbidity Prediction**: 0.25 (low recovery chances).  

2. Input 2:  
   - **Age**: 60  
   - **Time Since Injury**: 8 hours  
   - **GCS**: 9  
   - **GOS**: 2  
   - **Output**:  
     - **Prognosis State**: *Critical state*  
     - **Mortality Prediction**: High risk of mortality.  
     - **Morbidity Prediction**: 0.30 (low recovery chances).  

3. Input 3:  
   - **Age**: 55  
   - **Time Since Injury**: 5 hours  
   - **GCS**: 8  
   - **GOS**: 1  
   - **Output**:  
     - **Prognosis State**: *Critical state*  
     - **Mortality Prediction**: High risk of mortality.  
     - **Morbidity Prediction**: 0.20 (very low recovery chances).  


Inputs Resulting in Recovery State
1. Input 1:  
   - **Age**: 30  
   - **Time Since Injury**: 2 hours  
   - **GCS**: 14  
   - **GOS**: 4  
   - **Output**:  
     - **Prognosis State**: *Recovery state*  
     - **Mortality Prediction**: Low risk of mortality.  
     - **Morbidity Prediction**: 0.85 (high recovery chances).  

2. Input 2:  
   - **Age**: 25  
   - **Time Since Injury**: 1.5 hours  
   - **GCS**: 15  
   - **GOS**: 5  
   - **Output**:  
     - **Prognosis State**: *Recovery state*  
     - **Mortality Prediction**: Low risk of mortality.  
     - **Morbidity Prediction**: 0.90 (excellent recovery chances).  

3. Input 3:  
   - **Age**: 40  
   - **Time Since Injury**: 3 hours  
   - **GCS**: 13  
   - **GOS**: 4  
   - **Output**:  
     - **Prognosis State**: *Recovery state*  
     - **Mortality Prediction**: Low risk of mortality.  
     - **Morbidity Prediction**: 0.75 (good recovery chances).  
