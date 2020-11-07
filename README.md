# Parkinson-s-Disease-PD-diagnosis-using-Ensemble-Techniques
Parkinson’s Disease (PD) is a degenerative neurological disorder marked by decreased dopamine levels in the brain. It manifests itself through a deterioration of movement, including the presence of tremors and stiffness. Since PD patients exhibit characteristic vocal features, voice recordings are a useful and non-invasive tool for diagnosis. If machine learning algorithms could be applied to a voice recording dataset to accurately diagnosis PD, this would be an effective screening step prior to an appointment with a clinician.
There is commonly a marked effect on speech, including dysarthria (difficulty articulating sounds), hypophonia (lowered volume), and monotone (reduced pitch range). Additionally, cognitive impairments and changes in mood can occur, and risk of dementia is increased.Traditional diagnosis of Parkinson’s Disease involves a clinician taking a neurological history of the patient and observing motor skills in various situations. Since there is no definitive laboratory test to diagnose PD, diagnosis is often difficult, particularly in the early stages when motor effects are not yet severe. Monitoring progression of the disease over time requires repeated clinic visits by the patient. An effective screening process, particularly one that doesn’t require a clinic visit, would be beneficial. 
# Domain: 
Medicine

# Attribute Information:
1. name -ASCII subject name and recording number
2. MDVP:Fo(Hz) -Average vocal fundamental frequency
3. MDVP:Fhi(Hz) -Maximum vocal fundamental frequency
4. MDVP:Flo(Hz) -Minimum vocal fundamental frequency
5. MDVP:Jitter(%),MDVP:Jitter(Abs),MDVP:RAP,MDVP:PPQ,Jitter:DDP -Several measures of variation in fundamental frequency
6. MDVP:Shimmer,MDVP:Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,MDVP:APQ,Shimmer:DDA -Several measures of variation in amplitude
7. NHR,HNR -Two measures of ratio of noise to tonal components in the voice
8. status -Health status of the subject (one) -Parkinson's, (zero) -healthy
9. RPDE,D2 -Two nonlinear dynamical complexity measures
10. DFA -Signal fractal scaling exponentspread1,spread2,PPE -Three nonlinear measures of fundamental frequency variation 9. 
11. car name: string (unique for each instance)

Learning Outcomes: 
●Exploratory Data Analysis
●Supervised Learning
●Ensemble Learning

# Objective: 
Goal is to classify the patients into the respective labels using the attributes from their voice recordings

# Steps and tasks:
1. Load the dataset
2. It is always a good practice to eye-ball raw data to get a feel of the data in terms of number of records, structure of the file, number of attributes, types of attributes and a general idea of likely challenges in the dataset. Mention a few comments in this regard
3. Using univariate & bivariate analysis to check theindividual attributes for their basic statistics such as central values, spread, tails, relationships between variables etc. mention your observations
4. Split the dataset into training and test set in the ratio of 70:30 (Training:Test) 
5. Prepare the data for training -Scale the data if necessary, get rid of missing values (if any) etc
6. Train at least 3 standard classification algorithms -Logistic Regression, Naive Bayes’, SVM, k-NN etc, and note down their accuracies on the test data
7. Train a meta-classifier and note the accuracy on test data
8. Train at least one standard Ensemble model -Random forest, Bagging, Boosting etc, and note the accuracy
9. Compare all the models (minimum 5) and pick the best one among them
