# Oil Filter Clogging Prediction and Monitoring Mobile App (On Process)

This repository hosts the development of a **mobile application** and **machine learning models** designed to predict and monitor oil filter clogging in fuel transport vehicles. The project supports preventive maintenance strategies, reducing operational costs and improving fleet reliability for Pertamina fuel transport vehicles.

---

## 📖 Project Overview

Oil filter clogging in diesel engines is a critical issue, particularly with the widespread adoption of biodiesel blends such as B30. This project addresses the problem by developing:

1. A mobile application with an intuitive **UI/UX** for monitoring oil filter health.
2. Machine learning models to predict the optimal timing for oil filter replacement, minimizing clogging risks.

The system integrates **real-time data monitoring**, **predictive analytics**, and **user-friendly mobile interfaces** to empower operators with actionable insights.

---

## 🎯 Objectives

1. **Mobile Application Development**:

   - Create a cross-platform mobile application for real-time oil filter monitoring.
   - Design an engaging and efficient UI/UX for optimal usability.

2. **Machine Learning Model Implementation**:

   - Develop predictive models for oil filter clogging based on operational and environmental data.
   - Use these predictions to generate dynamic maintenance schedules.

3. **System Integration**:
   - Seamlessly combine machine learning predictions with mobile app functionality for a unified user experience.

---

## 🛠️ Tools and Technologies

### Mobile App Development

- **Framework**: Flutter (or React Native for cross-platform compatibility).
- **Backend**: Node.js and Express.js for RESTful API services.
- **Database**: Firebase or MongoDB for real-time and scalable data storage.

### Machine Learning

- **Programming Language**: Python.
- **Libraries and Frameworks**:
  - **scikit-learn** for baseline machine learning models.
  - **TensorFlow/Keras** for deep learning-based predictive models.
  - **Pandas** and **NumPy** for data analysis and preprocessing.
  - **Matplotlib** and **Seaborn** for data visualization.

### UI/UX Design

- **Tools**:
  - Figma or Adobe XD for wireframes, mockups, and interactive prototypes.
  - Heuristic evaluation and usability testing for user experience optimization.

---

## 📊 Dataset

The dataset for this project will consist of:

1. **Operational Data**:
   - Oil filter pressure levels, engine runtime hours, and vehicle mileage.
2. **Environmental Factors**:
   - Ambient temperature, humidity, and type of biodiesel blend used (B30, B50, etc.).
3. **Historical Maintenance Logs**:
   - Past clogging incidents and oil filter replacement records.

**Data Preprocessing Steps**:

- Cleaning and handling missing values.
- Feature scaling and normalization.
- Splitting into training, validation, and testing datasets.

---

## 🚀 Development Workflow

### Phase 1: Planning and Research

- Conduct a literature review on oil filter clogging and preventive maintenance.
- Define system requirements and success criteria.

### Phase 2: Data Collection and Analysis

- Collect data from fleet operations, including sensor logs and maintenance records.
- Perform exploratory data analysis (EDA) to identify trends and features.

### Phase 3: Model Development

- Develop baseline machine learning models (e.g., Random Forest, SVM).
- Build advanced models, including deep learning techniques (e.g., LSTM for time-series data).
- Evaluate models using metrics such as RMSE, precision, recall, and F1-score.

### Phase 4: Mobile Application Development

- Design wireframes and prototypes for the mobile app.
- Implement core features, including real-time monitoring, clogging predictions, and maintenance reminders.
- Integrate the backend predictive models into the app.

### Phase 5: Testing and Deployment

- Conduct usability testing to ensure app efficiency and user satisfaction.
- Deploy the app to Android and iOS platforms.
- Monitor real-world performance and iterate based on feedback.

---

## 📂 Repository Structure

```plaintext
├── data/                   # Dataset for machine learning
│   ├── raw/               # Raw unprocessed data
│   ├── processed/         # Cleaned and preprocessed data
├── models/                 # Machine learning models
│   ├── baseline/          # Baseline models (e.g., Random Forest, SVM)
│   ├── advanced/          # Advanced models (e.g., LSTM, CNN)
├── app/                    # Mobile application source code
│   ├── screens/           # App screens and pages
│   ├── components/        # Reusable UI components
│   ├── assets/            # Images, icons, and other assets
├── uiux/                   # UI/UX design files
│   ├── wireframes/        # Wireframe designs
│   ├── prototypes/        # Interactive prototypes and mockups
├── docs/                   # Documentation and reports
│   ├── user_manual/       # Instructions for app usage
│   ├── model_results/     # Performance metrics and evaluations
├── tests/                  # Unit and integration tests for the app
├── README.md               # Project overview and guide
├── requirements.txt        # Python dependencies for machine learning
└── LICENSE                 # License file
```
