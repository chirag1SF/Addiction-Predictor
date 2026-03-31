# Phone Addiction Predictor

A data-driven web application that predicts an individual's **Addiction Level** based on their daily smartphone habits and lifestyle metrics. The project features a **Linear Regression** model served via a **Flask** web interface.

---

## Features

- **Behavioral Analysis**: Predicts addiction levels based on screen time, sleep patterns, and academic impact.
- **Predictive Modeling**: Uses `scikit-learn` Linear Regression to find correlations between phone usage and dependency.
- **Persistent Model**: Model is serialized using `pickle` (`addict.pkl`) for seamless integration with the Flask frontend.
- **Real-time Prediction**: User-friendly web interface for instant feedback.

---

## Tech Stack

| Category       | Technology              |
|----------------|------------------------|
| **Language**   | Python 3.x            |
| **Data Science** | `pandas`, `scikit-learn` |
| **Web Framework** | `Flask`             |
| **Serialization** | `pickle`            |

---

## Input Features

The model analyzes the following variables to determine the addiction score:

| Feature                | Description                              |
|------------------------|------------------------------------------|
| **Daily Usage Hours**  | Average hours spent on the phone per day |
| **Sleep Hours**        | Average hours of sleep per night         |
| **Academic Performance**| GPA or performance rating                |
| **Phone Checks Per Day**| Frequency of checking notifications     |
| **Weekend Usage Hours**| Usage spikes during non-working days     |

---

## Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/phone-addiction-predictor.git
cd phone-addiction-predictor
```

### 2. Install Dependencies
```bash
pip install pandas scikit-learn flask
```

### 3. Launch the Web App
```bash
flask run
```

Visit [http://127.0.0.1:5000](http://127.0.0.1:5000) in your browser.
