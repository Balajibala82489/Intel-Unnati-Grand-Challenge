# Intel-Unnati-Grand-Challenge
Enhancing Road Safety through Advanced Driver Assistance System Data Analysis

Advanced Driver Assistance Systems (ADAS) play a crucial role in modern vehicle safety. This data analysis project aims to leverage ADAS dataset attributes, including alerts, date, time, latitude, longitude, vehicle ID, speed, and accident records, to gain insights into road safety and propose strategies for improvement. The dataset is pre processed to handle missing data, perform feature engineering, and encode categorical variables. 
The feature engineering process includes extracting temporal information from date and time columns, normalizing numerical features, and introducing text-based features from alert descriptions using Count Vectorizer. Hyperparameter tuning using Grid Search CV is employed to optimize a Random Forest Classifier for accident prediction.
The results indicate that the proposed approach significantly enhances the understanding of road safety. It identifies factors contributing to accidents, temporal trends in ADAS activations, and the relationship between alerts and road safety. Furthermore, it suggests strategies such as improving driver training, fine-tuning ADAS systems based on real-world data, and collaborating with vehicle manufacturers to enhance safety.
We use ‘Grid Search CV’ to perform Hyperparameters tuning for the Random Forest Classifier
We extract text-based feature from the ‘Alert’ column using CountVectorizer.
These new text-based features are concatenated with the existing feature
