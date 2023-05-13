# mlops
notebooks: - model tracking
mlflow ui --backend-store-uri sqlite:///mlflow.db
 --> artifacts are stored under the local ./mlruns directory, and MLflow entities are inserted in a SQLite database file mlruns.db.

Orchestration
src.models.train_model.py

References:-
https://github.com/DataTalksClub
https://www.youtube.com/@datasciencesimplified
https://www.udemy.com/course/complete-mlops-bootcamp-from-zero-to-hero-in-python-2022/
