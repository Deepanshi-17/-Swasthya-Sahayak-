## 🏥Swasthya-Sahayak (Healthcare-Provider Recommendation System)
Google Girl Hackathon - Ideathon Round Submission

## Overview

This project aims to develop a healthcare recommendation system to facilitate the process of finding and connecting with healthcare providers based on user-entered symptoms. Leveraging machine learning, natural language processing (NLP), and web development technologies, the system offers personalized doctor recommendations tailored to individual healthcare needs.

## Features

- 🩺 **Symptom Analysis:** Machine learning algorithms analyze user-entered symptoms to identify potential health conditions. The system utilizes a dataset containing disease-symptom correlations to make accurate predictions.
  
- 📋**Doctor Recommendation:** Recommended doctors are matched with user symptoms based on specialties and availability. The recommendation engine prioritizes doctors with high ratings and aligned schedules to ensure quality and convenience for users.

### Prerequisites

- The latest version of Python installed on your system
- Jupyter Notebook installed (optional) or access to Google Colab for running code files

### Installation

1. Download the project files from the repository.

2. Ensure you have the latest version of Python installed on your system.

3. Install Jupyter Notebook (optional) or open the code file in Google Colab.

4. Upload the dataset named `updated_dataset.csv` along with the code files in your working environment.

### Usage

1. Open the `updated_main.ipynb` file in your Jupyter Notebook or Google Colab.

2. Run the code file.

3. Enter your symptoms when prompted. Ensure the symptoms match those available in the dataset.

4. The system will output the most relevant diseases and recommend a doctor specializing in the corresponding field. The recommendation will consider the doctor's availability and user ratings.

## Future Scope

- **Updation of User Ratings:** Implement a feature to allow users to update doctor ratings over time, ensuring the recommendations remain relevant and accurate.
  
- **Updating Doctor Schedules:** Integrate functionality to update doctor schedules dynamically, reflecting real-time availability.

- **Emergency Button:** Incorporate an emergency button feature that, when activated, provides immediate access to nearby healthcare facilities based on geolocation.

- **Multilingual Chatbot Assistant:** Recognizing the linguistic diversity of our country, integrate a multilingual chatbot assistant using NLP. This chatbot will enable users to input symptoms in their preferred language, ensuring accessibility for everyone.

## References

- Symptom-Disease Dataset: [Kaggle Dataset](https://www.kaggle.com/datasets/kaushil268/disease-prediction-using-machine-learning)
- Healthcare-Provider Dataset: Web scrapped from [DrData](https://www.drdata.in/listdoctors.php?search=Doctor&state=&state=Uttar%20Pradesh&page=2)
- Review paper on Healthcare Recommendation System: [ScienceDirect](https://www.sciencedirect.com/science/article/abs/pii/S0957417422018413)

## Contributing

👩‍💻 Contributions to the project are welcome! If you encounter any issues or have ideas for improvements, please submit a GitHub issue or create a pull request with your changes.

