# HeartDiseaseDetectionUsingKNN <br />
  heart disease detection using K Nearest Neighbor (KNN) algorithm <br />

**Project as a part of Data And Knowledge Management Course at University of Waterloo** <br />

**Feature descriptions**:<br />
    Below is the group of features presents in the dataset segregated by their type (numerical, categorical, ordinal, binary) <br />
    **_Binary_** <br />
    sex (0 = female; 1 = male) <br />
    fbs: Fasting blood sugar > 120 mg/dl <br />
    exang: Exercise induced angina (0 = no; 1 = yes) <br />
    **Categorical**__ <br />
    cp: Chest pain type (0 = Asymptomatic angina; 1 = Atypical angina; 2 = Non-angina; 3 = Typical angina) <br />
    restecg: Resting ECG (0 = Left ventricular hypertrophy; 1 = Normal; 2 = ST-T wave abnormality) <br />
    slope: Slope of the peak exercise ST segment (0 = downsloping; 1 = upsloping; 2 = flat) <br />
    thal: Thalium stress test result (0 = NA; 1 = Fixed defect; 2 = Normal; 3 = Reversible defect) <br />
    **Ordinal**__ <br />
    ca: number of major vessels (0-3) colored by flourosopy <br />
    **Numeric**__ <br />
    age <br />
    oldpeak: ST depression induced by exercise relative to rest <br />
    trestbps: Resting blood pressure <br />
    chol: Serum cholestoral in mg/dl <br />
    thalach: Maximum heart rate achieved during thalium stress test <br />
    **Target**__ <br />
    target: 1 = heart disease; 0 = no heart disease <br />

**Steps Implemented** - <br />
    1. Checked for null and duplicate values, missing attributes and handled them <br />
    2. Normalized the resulting dataset <br />
    3. One-hot encoded the categorical features <br />
    4. Conducted thorough EDA to understand the data <br />
    5. Used hyperparamter tuning to achieve optimum performance (varied distance types, K values etc.) <br />

**Libraries used** - <br />
  Seaborn, Pandas, Numpy, Matplotlib, Neighbors <br />




