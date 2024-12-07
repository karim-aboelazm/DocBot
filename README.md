# **DocBot: Comprehensive Medical AI Assistant**  

---

## **📘 Project Overview**  
DocBot is an advanced AI-powered medical assistant that integrates **10 powerful medical AI projects** into a single, unified system. It leverages **Odoo ERP** as the deployment platform, ensuring an intuitive and user-friendly experience for healthcare professionals, researchers, and students. DocBot applies cutting-edge machine learning and deep learning techniques to assist in medical diagnosis, disease classification, and predictive analytics.  

This comprehensive AI solution is designed to support healthcare providers with quick, accurate, and explainable insights, promoting better decision-making and patient outcomes. The project emphasizes scalability, modularity, and future enhancements, making it a significant contribution to the field of AI in healthcare.  

---

## **🎯 Project Goals**  
- **Unified Medical AI System**: Combine multiple AI-powered healthcare solutions into one cohesive platform.  
- **Accurate Diagnosis**: Provide early detection and classification of diseases with high accuracy.  
- **User-Friendly Interface**: Deploy the AI assistant on **Odoo ERP**, offering an intuitive user experience.  
- **Modularity and Scalability**: Ensure that each AI module can be maintained, updated, or expanded independently.  
- **Customizable Enhancements**: Provide a platform for future work and improvements.  

---

## **🧪 Included AI Projects**  
DocBot integrates the following **10 AI projects**, each focusing on a specific area of medical diagnosis or prediction:  

1. **Breast Cancer Classification**  
   - **Dataset**: Breast Cancer Wisconsin Dataset  
   - **Models Used**: KNeighborsClassifier, SVC  
   - **Features**: Feature reduction, GridSearchCV, visualizations (scatterplots, heatmaps), and classification reports.  

2. **Breast Cancer Detection**  
   - **Dataset**: Breast Cancer Wisconsin Dataset  
   - **Models Used**: KNeighborsClassifier, SVC  
   - **Features**: Similar approach to Breast Cancer Classification, with a focus on detailed analysis.  

3. **COVID-19 Detection from Chest X-Rays**  
   - **Dataset**: COVID-19 Radiography Database from Kaggle  
   - **Models Used**: ResNet18 (PyTorch)  
   - **Features**: Chest X-ray image classification for COVID-19 detection.  

4. **Diabetes Prediction**  
   - **Dataset**: Diabetes Dataset (via GitHub)  
   - **Models Used**: Logistic Regression  
   - **Features**: Prediction of diabetes using features like glucose, insulin, BMI, etc.  

5. **Diagnosing Coronary Artery Disease**  
   - **Dataset**: Cleveland Heart Disease Dataset  
   - **Models Used**: Convolutional Neural Network (CNN) using Keras  
   - **Features**: Categorical and binary classification of heart disease.  

6. **DNA Classification**  
   - **Dataset**: Promoter Gene Sequences Dataset  
   - **Models Used**: KNeighborsClassifier, DecisionTreeClassifier, RandomForestClassifier, MLPClassifier, SVC, etc.  
   - **Features**: Multi-class classification of DNA promoter sequences.  

7. **Eye Disease Classification**  
   - **Dataset**: Eye Diseases Classification Dataset from Kaggle  
   - **Models Used**: EfficientNetB3 with BatchNormalization, Dense layers, and Dropout  
   - **Features**: Identification of multiple types of eye diseases using deep learning.  

8. **Heart Disease Classification**  
   - **Dataset**: Heart Disease Dataset (similar to Cleveland Heart Disease)  
   - **Models Used**: Machine learning models for heart disease prediction.  
   - **Features**: Prediction and analysis of heart disease based on patient metrics.  

9. **Prediction Diabetes with Multilayer Perceptrons**  
   - **Dataset**: Healthline Dataset on Diabetes  
   - **Models Used**: Multilayer Perceptrons (MLPs)  
   - **Features**: Type 1 and Type 2 diabetes classification with a deep learning approach.  

10. **Skin Disease Classification**  
    - **Dataset**: Skin Disease Dataset from Kaggle  
    - **Models Used**: ResNet50  
    - **Features**: Image classification of skin diseases using deep learning.  

---

## **⚙️ Odoo ERP Deployment**  
The **Odoo 17** ERP system serves as the deployment platform for DocBot. It enables the smooth integration of all AI models and provides an accessible, web-based interface for medical practitioners and researchers.  

### **Odoo Features**  
- **Custom Views**: Customizable dashboards and views for each AI project.  
- **Dynamic Widgets**: Custom **JavaScript widgets using the Owl framework** for better UI/UX.  
- **Abstract Models**: Abstract models to handle image and binary field processing.  
- **Custom Banners**: Personalized banner between the "Create" button and the search view for the **sale.order** screen.  
- **Modular Design**: Each AI project is a self-contained module that can be extended or improved.  

---

## **📊 Key Features**  
- **Multi-Disease Detection**: Diagnose multiple diseases using different AI models.  
- **Explainable AI (XAI)**: Provide transparent predictions and explainable decision-making.  
- **Medical Image Processing**: Use CNNs, ResNet, and EfficientNet for X-ray, eye, and skin disease image classification.  
- **Statistical Analysis**: Utilize KNeighborsClassifier, SVC, RandomForest, and Decision Trees for tabular datasets.  
- **Interactive Interface**: Web-based, user-friendly interface via **Odoo 17** ERP.  
- **Custom Widgets**: JavaScript widgets using the Owl framework for better user interaction.  

---

## **📦 Technologies Used**  
- **Languages**: Python, JavaScript, HTML, CSS  
- **Frameworks**: Odoo 17, Keras, TensorFlow, PyTorch, scikit-learn  
- **Databases**: MongoDB (DIGI_DB) for document-based storage, MySQL for relational databases  
- **Deployment**: Odoo ERP system  
- **Visualization**: Matplotlib, Seaborn, Plotly for heatmaps, scatterplots, and other data visualizations  

---

## **📚 Project Structure**  
```
📁 docbot/
├── 📁 odoo/
│     ├── 📁 models/
│     │      ├── abstract_models.py
│     │      ├── medical_projects.py
│     ├── 📁 views/
│     │      ├── medical_diagnosis_views.xml
│     │      ├── dashboard_view.xml
│     ├── 📁 static/
│     │      ├── 📁 images/ (custom images)
│     │      ├── 📁 js/ (JavaScript widgets)
├── 📁 ai_models/
│     ├── breast_cancer_classification.py
│     ├── breast_cancer_detection.py
│     ├── covid_detection.py
│     ├── diabetes_prediction.py
│     ├── coronary_artery_disease.py
│     ├── dna_classification.py
│     ├── eye_disease_classification.py
│     ├── heart_disease_classification.py
│     ├── prediction_diabetes_mlp.py
│     ├── skin_disease_classification.py
```

---

## **🔮 Future Work & Enhancements**  
- **Performance Optimization**: Further optimization of AI models for faster predictions.  
- **Additional Medical Models**: Expand to include models for more diseases (e.g., brain tumor detection, pneumonia classification).  
- **Explainability Features**: Include LIME and SHAP for better model explainability.  
- **More Visualizations**: Add interactive visualizations for results and diagnosis explanations.  
- **Mobile App**: Create a mobile-friendly version of the DocBot platform.  

---

## **📈 Key Performance Metrics**  
- **Accuracy**: Achieving high prediction accuracy across models.  
- **F1-Score**: Ensuring a balance between precision and recall.  
- **Execution Time**: Reduce processing time for large medical datasets.  

---

## **🙌 Acknowledgments**  
This project is a result of continuous research, development, and collaboration. Special thanks to the contributors, mentors, and educators who supported the project. Special gratitude to **Professor [Insert Name]** for their guidance and encouragement.  

---

## **👥 Team Members**  
- **Karim Mohammed Aboelazm** (Lead Developer, AI Specialist, Odoo Expert)  

---

## **📜 License**  
This project is licensed under the **MIT License**, allowing you to use, modify, and distribute the software.  

---

## **📢 How to Contribute**  
- Fork the repository.  
- Create a new branch (`git checkout -b feature/your-feature-name`).  
- Commit your changes (`git commit -m 'Add a new feature'`).  
- Push to the branch (`git push origin feature/your-feature-name`).  
- Open a pull request.  

---
