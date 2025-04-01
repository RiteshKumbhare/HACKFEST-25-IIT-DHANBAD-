# HACKFEST-25-IIT-DHANBAD-
This repository contains the Performance & Feedback Management Module designed for integration with GoFloww's Atom HR platform. The module streamlines employee performance reviews, enables continuous feedback loops, and provides AI-powered sentiment analysis to extract meaningful insights from employee reviews.

🚀 Key Features:
Performance Review Dashboard: Track performance metrics, feedback, and goal progress.
360-Degree Feedback Collection: Multi-source feedback from colleagues, managers, and subordinates.
AI-Driven Sentiment Analysis: Uses Logistic Regression (TF-IDF) and DistilBERT Transformer to classify feedback as positive, neutral, or negative, helping managers identify trends.
Analytics and Reporting: Generates actionable insights from performance data.
User-Friendly Interface: Simple, intuitive UI for employees and managers.
Secure & Scalable: Implements JWT authentication, data encryption, and seamless REST API integration with Atom HR.

🧠 AI-Powered Sentiment Analysis:
This module integrates a dual-model sentiment analysis system:
1. Logistic Regression (TF-IDF) – Traditional ML-based text classification.
2. DistilBERT Transformer – A deep learning model for more nuanced sentiment classification.

#Use Case in HR:
Detect trends in employee feedback.
Identify departments with high negative sentiment in reviews.
Provide data-driven insights for better decision-making.

⚙️ Technologies Used:
Frontend: React.js, HTML, CSS, JavaScript
Backend: Node.js, Express.js, FastAPI (for ML integration)
ML Pipeline: Python, Transformers, Sklearn, PyTorch
Database: MongoDB (or an alternative relational DB)
Security: JWT Authentication, HTTPS, Data Encryption


