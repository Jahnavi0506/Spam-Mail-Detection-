📧 Spam Mail Detection
This project uses Logistic Regression to classify emails as Spam (0) or Ham (1) based on their content. The model is trained using the SMS Spam Collection Dataset.

🗂️ Dataset
Total Samples: 5,572

Columns:

Category: Label (ham or spam)

Message: The email/SMS text

📌 After preprocessing:

spam → 0

ham → 1

🛠️ Libraries Used

numpy
pandas
scikit-learn

🔍 Data Preprocessing
Handled missing values

Converted labels (ham to 1, spam to 0)

Split data into training and testing sets (80/20 split)

Applied TF-IDF Vectorization to convert text into numerical features

🧠 Model Used
Logistic Regression

Vectorized with TfidfVectorizer

Achieved:

Training Accuracy: ~96.86%

Testing Accuracy: ~95.34%

🔎 Predictive System
You can input any message and the model will predict whether it is:

📨 Ham → Not spam
🚫 Spam → Junk mail
