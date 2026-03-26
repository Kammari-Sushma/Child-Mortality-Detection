# Child-Mortality-Detection

Child Mortality Detection using Machine Learning

This project is a web-based application built with Django that leverages Machine Learning to predict and analyze child mortality rates. It provides a platform for data management, model training, and visualization to help identify key factors contributing to child mortality.

🚀 Features
Data Upload & Management: Import and manage health datasets (CSV format).

Machine Learning Integration: Implemented using algorithms like Decision Trees for classification and prediction.

Interactive Dashboard: A user-friendly interface to visualize data distribution and model results.

Admin Panel: Secure administrative control for managing system users and backend data.

Responsive UI: Built with Bootstrap and custom CSS for a seamless experience on both desktop and mobile.

📁 Repository Structure  
Plaintext  
├── ChildMortality/           # Main Django Project Directory  
│   ├── AdminApp/             # Logic for Admin interface and ML processing  
│   ├── ChildMortality/       # Core project settings and URL configuration  
│   ├── Static/               # Assets (Bootstrap, Fonts, CSS, Images)  
│   ├── Templates/            # HTML Frontend files  
│   └── dataset/              # Dataset files (e.g., data1.csv)  
├── architecture.docx         # Technical documentation of the system  
├── manage.py                 # Django command-line utility  
├── db.sqlite3                # Local database  
└── run.bat                   # Batch script to launch the project quickly  
🛠️ Installation & Setup  
Prerequisites  
Python 3.x  

Django  

Scikit-learn, Pandas, and NumPy

Step-by-Step Guide  
Clone the Repository  

Bash  
git clone https://github.com/your-username/child-mortality-detection.git  
cd child-mortality-detection  
Install Dependencies  

Bash  
pip install django pandas scikit-learn numpy  
Database Migration  

Bash  
python manage.py migrate  
Run the Application  
You can either double-click run.bat (on Windows) or run:  

Bash  
python manage.py runserver  
Access the App  
Open your browser and go to: http://127.0.0.1:8000/  

📊 How it Works  
Login: Access the system through the Admin or User login.  

Dataset: The system processes health-related parameters from the provided dataset/ folder.

Training: The ML model (Decision Tree) splits the data into training and testing sets to achieve high accuracy.

Prediction: Input specific health metrics to receive a prediction regarding mortality risk.

🛠️ Technologies Used  
Backend: Django (Python)  

Frontend: HTML5, CSS3, JavaScript, Bootstrap

Machine Learning: Scikit-learn

Database: SQLite

📝 License  
This project is for educational purposes. Feel free to use and modify it.

Developed by Kammari Sushma
