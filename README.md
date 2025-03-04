
# SMS-Email Spam Classifier

This project is a machine learning-based SMS and email spam classifier that uses **TF-IDF (Term Frequency-Inverse Document Frequency)** and **Multinomial Naive Bayes (MultinomialNB)** to identify spam messages with a remarkable accuracy of 97%. The application features a user-friendly interface built with **Streamlit** and is deployed on Render.  

Access the live application here:  
**[SMS-Email Spam Classifier](https://sms-emails-spam-classifier-raj-patel.onrender.com/)**

---

## Snapshots

### 1. Not Spam Detection Output Example
![Not Spam Detection](https://github.com/user-attachments/assets/281fbec4-3bf0-47bd-86a4-64d71bd6366a)


### 2. Spam Detection Output Example
![Spam Detection](https://github.com/user-attachments/assets/25442d65-eb52-4c17-a8f2-eb4e06ab9b75)


---

## Features

- **High Accuracy**: Achieves a classification accuracy of 97%.
  
![Accuracy Score](https://github.com/user-attachments/assets/e6883e33-21f5-4c1e-9012-8b80b4802180)
- **Streamlit Interface**: A clean and interactive web interface for ease of use.
- **Efficient Deployment**: Hosted on [Render](https://render.com/) for reliable and scalable access.
- **Fast and Lightweight**: Utilizes TF-IDF and MultinomialNB for efficient processing.

---

## Installation

To run the project locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/rajnish80130/sms-email-spam-classifier.git
   cd sms-email-spam-classifier
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

4. Open your browser and navigate to `http://localhost:8501` to use the app.

---

## Dataset

The model was trained on an imbalanced dataset of SMS and email messages:

- 87% Ham Messages: Normal (non-spam) messages.
- 13% Spam Messages: Unwanted or spam messages.
- This imbalance was addressed during training to ensure robust spam detection.

---

## Model Details

- **Vectorization**: TF-IDF (Term Frequency-Inverse Document Frequency)  
- **Classifier**: Multinomial Naive Bayes (MultinomialNB)  
- **Accuracy**: 97% on test data.

---

## Deployment

The project is deployed on Render and can be accessed at:  
**[SMS-Email Spam Classifier](https://sms-emails-spam-classifier-raj-patel.onrender.com/)**

---

## Usage

1. Visit the deployed application.  
2. Enter the SMS or email text you want to check in the input field.  
3. Click on the **"Predict"** button.  
4. The app will classify the input as either **Spam** or **Not Spam**.

---

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.  
2. Create a new branch for your feature or bug fix.  
3. Commit your changes and push the branch.  
4. Submit a pull request for review.

---

## Contact

For questions or feedback, feel free to reach out:  
**Rajnish Patel**  
Email: [rajnish80130@gmail.com]
