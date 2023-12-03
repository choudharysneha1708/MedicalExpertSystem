# MedicalExpertSystem
****DataSet****
The main task of our project is to making dataset from scratch. we collected the data of 50 disease, which have total 92 symptoms, concentrated on respiratory ailments, encompassing post-COVID conditions and diseases associated with occurrences post-COVID.
Additionally, common diseases and systemic ailments were integrated, broadening the dataset's scope. 
Data set is marked with 0,1,2,3 this represent the probability levels of symptom manifestation within each disease profile. 
In this project we are predicting probabilty of happening a disease.
****Rule Based Implementation****
In our rule-based implementation, we streamline the user experience by initially presenting the top 8 symptoms most frequently occurring across various diseases, sorted in order of prevalence. 
With each user selection, if the choice aligns with any of these top symptoms, the subsequent iteration displays the top 8 symptoms associated with diseases featuring the chosen symptom. 
This strategic approach effectively diminishes the search space by focusing on symptoms closely linked to the user's selections, progressively refining and narrowing down potential disease options.
In our diagnostic system, we determine the likelihood of a user's ailment by computing probabilities associated with specific diseases, aiding in assessing the severity of their illness. 
If any calculated probability exceeds or equals 0.5, we present the top 5 probabilities to the user. However, if all probabilities remain below this threshold, we display all potential probabilities. 
This approach offers a comprehensive view of potential illnesses, providing users with crucial insights into the likelihood and severity of their condition for informed decision-making.
