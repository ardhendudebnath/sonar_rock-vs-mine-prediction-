# sonar_rock-vs-mine-prediction-
𝗢𝘃𝗲𝗿𝘃𝗶𝗲𝘄
This project uses a logistic regression model to predict whether an object detected by sonar is a rock or a mine. The model is trained on a dataset of sonar signals and their corresponding labels (rock or mine).

𝗗𝗮𝘁𝗮𝘀𝗲𝘁
The dataset used in this project is a CSV file containing 60 features (sonar signals) and 1 label (rock or mine). The dataset is split into training and test sets using stratified sampling to ensure that the model is trained and evaluated on a representative sample of the data.

𝗠𝗼𝗱𝗲𝗹

The model used in this project is a logistic regression model, which is a type of supervised learning algorithm that is well-suited for binary classification problems like this one. The model is trained on the training data and evaluated on the test data using accuracy as the performance metric.

𝗰𝗼𝗱𝗲
𝙏𝙝𝙚 𝙘𝙤𝙙𝙚 𝙛𝙤𝙧 𝙩𝙝𝙞𝙨 𝙥𝙧𝙤𝙟𝙚𝙘𝙩 𝙞𝙨 𝙬𝙧𝙞𝙩𝙩𝙚𝙣 𝙞𝙣 𝙋𝙮𝙩𝙝𝙤𝙣 𝙖𝙣𝙙 𝙪𝙨𝙚𝙨 𝙩𝙝𝙚 𝙛𝙤𝙡𝙡𝙤𝙬𝙞𝙣𝙜 𝙡𝙞𝙗𝙧𝙖𝙧𝙞𝙚𝙨:

numpy for numerical computations
pandas for data manipulation and analysis
scikit-learn for machine learning

𝙏𝙝𝙚 𝙘𝙤𝙙𝙚 𝙞𝙨 𝙤𝙧𝙜𝙖𝙣𝙞𝙯𝙚𝙙 𝙞𝙣𝙩𝙤 𝙨𝙚𝙫𝙚𝙧𝙖𝙡 𝙛𝙪𝙣𝙘𝙩𝙞𝙤𝙣𝙨, 𝙚𝙖𝙘𝙝 𝙤𝙛 𝙬𝙝𝙞𝙘𝙝 𝙥𝙚𝙧𝙛𝙤𝙧𝙢𝙨 𝙖 𝙨𝙥𝙚𝙘𝙞𝙛𝙞𝙘 𝙩𝙖𝙨𝙠:


load_data: loads the dataset from a CSV file
analyze_data: prints the shape and statistical measures of the data
preprocess_data: separates the data into features (X) and labels (Y)
train_model: trains a logistic regression model on the training data
evaluate_model: evaluates the model's accuracy on both training and test data
make_prediction: makes a prediction using the trained model
main: the main function that calls the other functions and runs the project
