# ⚡ Residential Energy Consumption Predictor

A **Streamlit web app** that predicts residential energy usage (in kilowatt-hours) using either a **Random Forest** or **Linear Regression** model. Users can input household details like number of occupants, income, weather, and home system types. The app also visualizes contributing factors through **bar and pie charts** using Plotly.

## 🌟 Features

- 🔮 Predicts energy usage based on user inputs
- 🧠 Choose from Random Forest or Linear Regression models
- 🗓️ Includes seasonal & calendar-based features (weekend, season, etc.)
- 📊 Interactive visualizations with Plotly (Bar + Pie Charts)
- 🎨 Background styling with dark overlay

---

## 🧠 Models Used

- `Random_forest_model.pkl`
- `Linear_model.pkl`

> ⚠️ If your `.pkl` files are over 50MB, use [Git LFS](https://git-lfs.github.com/) or host them on Google Drive and use `gdown` in code to download.

---

## 🛠️ How to Run Locally


**2. Install Dependencies**

pip install -r requirements.txt

**3. Run the Streamlit App**

streamlit run app3_combo.py

**🧪 Sample Input Values**

| Feature              | Example  |
| -------------------- | -------- |
| num\_occupants       | 3        |
| house\_size\_sqft    | 1500     |
| monthly\_income      | 40000    |
| cooling\_type        | AC       |
| heating\_type        | Electric |
| manual\_override     | Yes      |
| energy\_star\_rating | Checked  |

**📦 Requirements**

streamlit
pandas
plotly
joblib


