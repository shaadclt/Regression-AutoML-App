# Regression AutoML App

This is a sample application that demonstrates how to build a regression AutoML app using Streamlit, Pandas Profiling, and PyCaret. The application allows users to upload a dataset, perform exploratory data analysis (EDA) using Pandas Profiling, and then build and evaluate regression models using PyCaret.

## Installation

To run the application, follow these steps:

1. Clone the repository:

   ```
   git clone https://github.com/your-username/regression-automl-app.git
   ```

2. Change into the project directory:

   ```
   cd regression-automl-app
   ```

3. Create a virtual environment (optional but recommended):

   ```
   python3 -m venv venv
   source venv/bin/activate
   ```

4. Install the required dependencies:

   ```
   pip install -r requirements.txt
   ```

5. Run the application:

   ```
   streamlit run app.py
   ```

   This will start the Streamlit development server and open the application in your web browser.

## Usage

Once the application is running, you can follow these steps to perform regression using AutoML:

1. Upload your dataset by clicking on the Upload option in the sidebar and selecting the dataset file.
2. After the dataset is uploaded, click on the Profiling menu to generate an exploratory data analysis report using Pandas Profiling. This will provide you with insights into the dataset's structure, missing values, distributions, correlations, and more.
3. Once the EDA report is generated, you can scroll through it to understand your data better.
4. After reviewing the EDA report, select the Modelling menu in the sidebar and choose the target column and then click on the "Run Modelling" button to start building a regression model using PyCaret's AutoML capabilities. PyCaret will automatically preprocess the data, perform feature engineering, and train multiple regression models.
5. Once the model building process is complete, PyCaret will display a summary of the best-performing models, including their evaluation metrics.
6. The best model can be downloaded by selecting the Download menu from sidebar and then clicking the "Download Model" button.

Feel free to customize the application based on your specific requirements. You can modify the app layout, add additional features, or integrate other libraries to enhance its functionality.

## Contributing

Contributions to this project are welcome! If you encounter any issues or have ideas for improvements, please submit a pull request or open an issue on the GitHub repository.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). You are free to use, modify, and distribute this application for personal or commercial purposes.
