# ml-practice-lgbm-catboost
Practice comparing Random Forest, LightGBM, and CatBoost on the Titanic dataset.
# Titanic Ensemble Models

This project demonstrates how to compare classic ensemble methods — **Random Forest**, **LightGBM**, and **CatBoost** — on the famous **Titanic dataset**.

## 📊 What’s inside?

- 🗂️ Clean Titanic dataset
- ✅ Feature engineering (Title, Cabin, Embarked, etc.)
- 🔍 Model training:
  - Random Forest (Bagging)
  - LightGBM (Boosting)
  - CatBoost (Boosting, automatic categorical handling)
- 📈 Feature importance comparison (Split vs Gain)
- ⚙️ Cross-validation
- 🔮 Submission file generation (optional)

## 🚀 How to run

1. **Create Conda environment:**

    ```bash
    conda create -n titanic-ml python=3.9
    conda activate titanic-ml
    ```

2. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Start Jupyter Notebook:**

    ```bash
    jupyter notebook
    ```

4. **Open `titanic_ensemble.ipynb` and run step by step.**

## ⚙️ Dependencies

See `requirements.txt`.

## 📄 License

This project is licensed under the MIT License.
