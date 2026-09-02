# E-Commerce Sales Forecasting

## Project Description

E-Commerce Sales Forecasting is a Machine Learning based web application developed using Python, Flask, and Scikit-learn.

The application predicts the expected sales of an item based on product and outlet-related information. Users can select different item and outlet attributes through a web interface and receive a predicted sales value.

This project demonstrates the integration of Machine Learning with a Flask web application for real-world sales prediction.

## Features

- Predict item sales using a trained Machine Learning model
- Simple and user-friendly web interface
- Dropdown-based input selection
- Flask backend for handling predictions
- Pre-trained Machine Learning model
- Label encoding for categorical features
- Separate prediction result page
- Responsive frontend using HTML, CSS, and Bootstrap

## Technologies Used

- Python
- Flask
- NumPy
- Pandas
- Scikit-learn
- HTML5
- CSS3
- Bootstrap
- Jupyter Notebook
- Machine Learning

## Project Structure

```text
E-Commerce-Sales/
│
├── models/
│   ├── model.pkl
│   ├── Establishment_Year_encoder_4.pkl
│   ├── Fat_Content_label_encoder_1.pkl
│   ├── Identifier_label_encoder_3.pkl
│   ├── Item_Type_label_encoder_2.pkl
│   ├── Location_Type_encoder_6.pkl
│   ├── Outlet_Type_encoder_7.pkl
│   └── Size_encoder_5.pkl
│
├── static/
│   ├── images.png
│   ├── style.css
│   └── style1.css
│
├── templates/
│   ├── index.html
│   └── result.html
│
├── analysis.ipynb
├── app.py
├── Train.csv
└── README.md
