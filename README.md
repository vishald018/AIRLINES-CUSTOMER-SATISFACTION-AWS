# ✈️ Airlines Customer Satisfaction - End-to-End ML App using AWS

This project is an end-to-end machine learning solution to predict airline customer satisfaction. It includes model training, Streamlit web app deployment, and hosting on AWS EC2 with CI/CD using GitHub Actions.

---

## 🚀 Features

- Streamlit frontend UI for predictions.
- Logistic Regression model trained on cleaned dataset.
- Deployment on AWS EC2 using GitHub Actions.
- Real-time predictions based on user inputs.

---

## 🧠 Machine Learning Model

- **Algorithm**: LightGBM or Light Gradient Boosting Machine
- **Training Accuracy**: ~95%  
- **Metrics Used**: Accuracy , R2 SCORE

---

## 🛠️ Tech Stack

- Python, Pandas, NumPy
- Scikit-learn
- Streamlit
- AWS EC2

---

## 🧪 How to Run the App Locally

```bash
git clone https://github.com/vishald018/AIRLINES-CUSTOMER-SATISFACTION-AWS.git
cd APP
pip install -r requirements.txt
streamlit run app.py
````

---

## ☁️ Deployment (CI/CD + AWS EC2)

* EC2 instance setup with SSH.
* GitHub Actions triggers deployment on push.
* App automatically restarts using `nohup` + `streamlit`.

---

## 🖼️ App Interface

<p float="left">
  <img src="https://github.com/vishald018/AIRLINES-CUSTOMER-SATISFACTION-AWS/blob/main/APP/interface1.jpg?raw=true" width="700" />
  <img src="https://github.com/vishald018/AIRLINES-CUSTOMER-SATISFACTION-AWS/blob/main/APP/interface2.jpg?raw=true" width="700" />
</p>

---

## 📂 Project Structure

```
├── APP
│   ├── app.py
│   ├── model.pkl
│   ├── requirements.txt
│   └── interface1.jpg, interface2.jpg
├── .github
│   └── workflows
│       └── deploy.yml
├── dataset.csv
├── EC2_setup.md
└── README.md
```

---

## ✍️ Author

Made with ❤️ by Vishal
GitHub: [vishald018](https://github.com/vishald018)

