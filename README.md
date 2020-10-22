# home-loan-default-risk-management
1. Binary classification problem
2. Objective:  Use historical loan application data to predict whether or not an applicant will be able to repay a loan.
3. Target is the dependent variable. 
          0 - will repay loan on time, 
          1 - will have difficulty repaying loan.
4. EDA and data preprocessing – Converting categorical columns to numeric Aggregating numeric columns Finding and imputing missing values        Correlation heat map Merging all csv files into a single file
5. Feature selection – Chi-square test considering 1000 best features out of 1186 features
6. Modelling –  Logistic Regression
                Random Forest classifier
                XGBoost
                LGBM classifier
                 Deep Learning
7. Model Evaluation – 

                  Model Name	                         Accuracy
              Logistic Regression     	                92.01%
              Random Forest classifier	                91.8%
              XGBoost	                          92.03%
              LGBM classifier         	                92.18%
              Deep Learning	                          92.04%

After comparing the performance of all the above techniques,  LGBM classifier performs the best followed by the Deep Learning neural network classifier.
