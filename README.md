# Cab Fare Prediction

This project aims to predict cab fares using data science techniques. By analyzing cab ride data in conjunction with weather conditions, a linear regression model is developed to estimate fare amounts. The project demonstrates the process of data preprocessing, feature engineering, and model building, providing insights into the factors influencing cab fares.

## Dataset

The project utilizes two datasets:
- `cab_rides.csv`: Contains information about cab rides, including pickup and drop-off locations, timestamps, distance traveled, and fare amounts.
- `weather.csv`: Includes weather-related features such as temperature, humidity, precipitation, etc.

## Project Structure

The project is structured as follows:
- `data/`: Directory to store the dataset files.
- `notebooks/`: Jupyter notebooks containing the data preprocessing, exploratory data analysis, and model building steps.
- `README.md`: This file, providing an overview of the project.

## Requirements

To run the project, you need the following dependencies:
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Usage

1. Clone the repository:
   git clone https://github.com/FebaRoy/cab-fare-prediction.git
   
2. Install the required dependencies:
   pip install -r requirements.txt

3. Place the dataset files (`cab_rides.csv` and `weather.csv`) in the `data/` directory. Remember to unzip the `cab_rides.csv` and use. (It is compressed to a zip due to its size.)

4. Open the Jupyter notebooks in the `notebooks/` directory and run them sequentially.

## Results

The project aims to achieve accurate fare predictions by leveraging linear regression. The evaluation of the model's performance will be discussed within the notebooks.

## Contributing

Contributions to the project are welcome. If you encounter any issues or have suggestions for improvement, please create an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).


