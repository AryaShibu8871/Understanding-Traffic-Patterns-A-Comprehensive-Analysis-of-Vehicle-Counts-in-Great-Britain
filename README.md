##OVerview

This project presents a comprehensive analysis of road traffic patterns across Great Britain, leveraging machine learning to forecast vehicle counts based on spatial and temporal factors. It was developed as part of my MSc dissertation in Big Data Analytics at Sheffield Hallam University.

Using historical traffic data, the project explores how vehicle volumes vary by location, year, month, and day of the week. Advanced models including LSTM, GRU, and SVM are trained to predict traffic volumes for multiple vehicle categories. The best-performing models are deployed in a web application that enables users to forecast traffic based on custom inputs.

##Objectives

Analyze traffic trends across regions and time periods

Visualize traffic patterns using exploratory data analysis

Build predictive models for different vehicle types

Evaluate model performance using standard metrics

Deploy top-performing models in a user-friendly web app

##Tools & Technologies

Data Processing: Pandas, NumPy

Visualization: Matplotlib, Seaborn, Plotly

Machine Learning: Scikit-Learn (Random Forest, XGBoost)

Deep Learning: TensorFlow/Keras (LSTM, GRU)

Environment: Jupyter Notebook / Python

##Dataset
Source: Kaggle - Road Traffic Dataset (https://www.kaggle.com/datasets/arashnic/road-trafic-dataset)
Features include: location, year, month, day of week, vehicle type, and traffic counts
Data pre-processing and cleaning performed using Python and Pandas

##Machine Learning Models
| Model | Description | Strengths | |-------|-------------|-----------| | **LSTM** | Deep learning model for time-series forecasting | Captures long-term dependencies and seasonal patterns | | **GRU** | Efficient variant of LSTM | Faster training with comparable accuracy | | **SVM** | Regression model for high-dimensional data | Effective for non-linear relationships and robust predictions |

##Web Application
A Streamlit-based web app is included to allow users to input location, date, and vehicle type to receive traffic volume predictions. It integrates the trained LSTM and GRU models for real-time forecasting.

##Results

- LSTM and GRU models outperformed SVM in forecasting accuracy
- Visualizations revealed strong regional and seasonal traffic variations
- The web app successfully predicts traffic volumes with high reliability


