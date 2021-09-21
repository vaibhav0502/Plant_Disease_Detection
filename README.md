# Machine_learning_and_AI


# Plant Disease Prediction

## Setup for Python:
```
pip install -r training/requirements.txt
```

## Setup for ReactJS
```
cd frontend
npm install --from-lock-json
npm audit fix
```

## Data Collection
1. [Dataset is taken from this kaggle dataset](https://www.kaggle.com/arjuntejaswi/plant-village)
2. From each class random 600 images are picked for model building.
3. To create train and test dataset run this script `training/create_train_test_folder.ipynb`

## Training the Model
1. Open `training/All_plant_disease_new_selected.ipynb` in Jupyter Notebook.
2. Update dataset path from your local
3. Run all the Cells one by one
4. Copy the generated model into `model` folder.

## Running the API
1. Go to `api` folder.
2. Run the FastAPI Server using uvicorn `python main.py`

## Running the Frontend
1. Go to `frontend` folder.
```
cd frontend
npm run start
```

https://user-images.githubusercontent.com/42543380/134180491-2fea831a-3d7b-4630-8d4d-1f04760b8acc.mov
