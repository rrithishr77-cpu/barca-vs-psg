# ⚽ Barcelona vs PSG: Football Match Prediction Using Machine Learning

> **I won! My model predicted PSG as the more likely winner against
> Barcelona --- and PSG actually won!**

This project explores how football statistics and machine learning can
be used to analyze team performance and predict match outcomes.

```{=html}
<!-- Add your project banner or main screenshot here -->
```
```{=html}
<p align="center">
```
`<img src="images/project-banner.png" alt="Barcelona vs PSG project banner" width="85%">`{=html}
```{=html}
</p>
```
> **Add your image:** Create an `images/` folder in the repository and
> upload your banner as `project-banner.png`. Change the filename above
> if needed.

## 📌 Project Overview

The project compares Barcelona and PSG using league performance data and
historical UEFA Champions League head-to-head encounters. It examines
team form, attacking performance, and home-versus-away patterns before
comparing machine learning models for match outcome prediction.

## 📊 Analysis and Visualizations

Add your charts or screenshots in the spaces below. Save each image in
the `images/` folder and update the filename if needed.

### 1. Current Team Form

```{=html}
<!-- Add chart: images/current-form.png -->
```
```{=html}
<p align="center">
```
`<img src="images/current-form.png" alt="Current form comparison" width="80%">`{=html}
```{=html}
</p>
```
### 2. Attacking Quality

```{=html}
<!-- Add chart: images/attacking-quality.png -->
```
```{=html}
<p align="center">
```
`<img src="images/attacking-quality.png" alt="Attacking quality comparison" width="80%">`{=html}
```{=html}
</p>
```
### 3. Home vs Away Performance

```{=html}
<!-- Add chart: images/home-away.png -->
```
```{=html}
<p align="center">
```
`<img src="images/home-away.png" alt="Home and away performance comparison" width="80%">`{=html}
```{=html}
</p>
```
### 4. Machine Learning Predictions

```{=html}
<!-- Add chart: images/model-predictions.png -->
```
```{=html}
<p align="center">
```
`<img src="images/model-predictions.png" alt="Machine learning model predictions" width="80%">`{=html}
```{=html}
</p>
```
### 5. Actual Match Result

```{=html}
<!-- Add screenshot: images/actual-result.png -->
```
```{=html}
<p align="center">
```
`<img src="images/actual-result.png" alt="Actual match result" width="80%">`{=html}
```{=html}
</p>
```
## 🧠 Machine Learning Models

I compared three classification models:

-   **Logistic Regression**
-   **Random Forest**
-   **Gradient Boosting**

The models were used to assess which team was more likely to win based
on the features available in the project.

## 🗂️ Data Sources

The analysis uses datasets covering:

-   La Liga --- current and previous seasons
-   Ligue 1 --- current and previous seasons
-   Historical UEFA Champions League head-to-head encounters between
    Barcelona and PSG

Refer to the notebook for the exact files, columns, preprocessing steps,
and match records used.

## 🛠️ Tech Stack

-   Python
-   Pandas
-   Scikit-learn
-   Data visualization
-   Jupyter Notebook

## 🚀 Getting Started

### 1. Clone the repository

``` bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd <YOUR_REPOSITORY_FOLDER>
```

### 2. Create a virtual environment (recommended)

``` bash
python -m venv .venv
```

Windows:

``` bash
.venv\Scripts\activate
```

macOS/Linux:

``` bash
source .venv/bin/activate
```

### 3. Install dependencies

A typical starting point:

``` bash
pip install pandas scikit-learn matplotlib seaborn jupyter
```

Add any other packages required by your notebook.

### 4. Run the notebook

``` bash
jupyter notebook
```

Open the project notebook and update dataset paths to match your local
folder structure before running the cells.

## 📁 Suggested Repository Structure

``` text
barcelona-vs-psg-prediction/
├── images/
│   ├── project-banner.png
│   ├── current-form.png
│   ├── attacking-quality.png
│   ├── home-away.png
│   ├── model-predictions.png
│   └── actual-result.png
├── data/                         # Share datasets only if permitted
├── barca_vs_psg_ml_models.ipynb
├── requirements.txt              # Optional
└── README.md
```

## 🔍 Key Takeaway

This experiment was an exciting example of using data to make a football
prediction. The model predicted PSG as the more likely winner, and PSG
went on to win.

**Important:** One correct prediction does not establish that a model is
reliable. A stronger evaluation would test it on multiple unseen matches
and report metrics such as accuracy, precision, recall, F1-score, and a
confusion matrix. Avoid data leakage and use only information that would
have been available before each match.

## 🔮 Future Improvements

-   Evaluate models on multiple unseen matches.
-   Add cross-validation and compare evaluation metrics.
-   Tune model hyperparameters.
-   Include reliable features such as recent goals, shots, possession,
    and player availability.
-   Compare predicted probabilities with actual outcomes.
-   Build a web dashboard to display the analysis.

## 👤 Author

**Your Name**

-   GitHub: `https://github.com/rrithishr77-cpu`
-   LinkedIn: `https://www.linkedin.com/in/YOUR_PROFILE/`

------------------------------------------------------------------------

If you find this project interesting, consider giving the repository a
⭐.
