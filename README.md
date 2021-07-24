# Advanced-Data-Analytics-D213

# Task 1

## Part I:  Research Question

A.  Describe the purpose of this data analysis by doing the following:

1.  Summarize one research question that is relevant to a real-world organizational situation captured in the selected data set and that you will answer using time series modeling techniques.

2.  Define the objectives or goals of the data analysis. Ensure that your objectives or goals are reasonable within the scope of the scenario and are represented in the available data.


Part II:  Method Justification

B.  Summarize the assumptions of a time series model including stationarity and autocorrelated data.


Part III:  Data Preparation

C.  Summarize the data cleaning process by doing the following:

1.  Provide a line graph visualizing the realization of the time series.

2.  Describe the time step formatting of the realization, including any gaps in measurement and the length of the sequence.

3.  Evaluate the stationarity of the time series.

4.  Explain the steps used to prepare the data for analysis, including the training and test set split.

5.  Provide a copy of the cleaned dataset.


Part IV:  Model Identification and Analysis

D.  Analyze the time series dataset by doing the following:

1.  Report the annotated findings with visualizations of your data analysis, including the following elements:

•   the presence or lack of a seasonal component

•   trends

•   auto correlation function

•   spectral density

•   the decomposed time series

•   confirmation of the lack of trends in the residuals of the decomposed series

2.  Identify an autoregressive integrated moving average (ARIMA) model that takes into account the observed trend and seasonality of the time series data.

3.  Perform a forecast using the derived ARIMA model.

4.  Provide the output and calculations of the analysis you performed.

5.  Provide the code used to support the implementation of the time series model.


Part V:  Data Summary and Implications

E.  Summarize your findings and assumptions, including the following points:

1.  Discuss the results of your data analysis, including the following:

•   the selection of an ARIMA model

•   the prediction interval of the forecast

•   a justification of the forecast length

•   the model evaluation procedure and error metric

2.  Provide an annotated visualization of the forecast of the final model compared to the test set.

3.  Recommend a course of action based on your results.


Part VI:  Reporting

F.  Create your report from part E using an industry-relevant interactive development environment (e.g., an R Markdown document, a Jupyter Notebook, etc.). Include a PDF or HTML document of your executed notebook presentation.

# Task 2

## Part I:  Research Question

A.  Describe the purpose of this data analysis by doing the following:

1.  Summarize one research question that you will answer using neural network models and NLP techniques. Be sure the research question is relevant to a real-world organizational situation and sentiment analysis captured in your chosen dataset.

2.  Define the objectives or goals of the data analysis. Be sure the objectives or goals are reasonable within the scope of the research question and are represented in the available data.

3.  Identify a type of neural network capable of performing a text classification task that can be trained to produce useful predictions on text sequences on the selected data set.


Part II:  Data Preparation

B.  Summarize the data cleaning process by doing the following:

1.  Perform exploratory data analysis on the chosen dataset, and include an explanation of each of the following elements:

•   presence of unusual characters (e.g., emojis, non-English characters, etc.)

•   vocabulary size

•   proposed word embedding length

•   statistical justification for the chosen maximum sequence length

2.  Describe the goals of the tokenization process, including any code generated and packages that are used to normalize text during the tokenization process.

3.  Explain the padding process used to standardize the length of sequences, including the following in your explanation:

•   if the padding occurs before or after the text sequence

•   a screenshot of a single padded sequence

4.  Identify how many categories of sentiment will be used and an activation function for the final dense layer of the network.

5.  Explain the steps used to prepare the data for analysis, including the size of the training, validation, and test set split.

6.  Provide a copy of the prepared dataset.


Part III:  Network Architecture

C.  Describe the type of network used by doing the following:

1.  Provide the output of the model summary of the function from TensorFlow.

2.  Discuss the number of layers, the type of layers, and total number of parameters.

3.  Justify the choice of hyperparameters, including the following elements:

•   activation functions

•   number of nodes per layer

•   loss function

•   optimizer

•   stopping criteria

•   evaluation metric


Part IV:  Model Evaluation

D.  Evaluate the model training process and its relevant outcomes by doing the following:

1.  Discuss the impact of using stopping criteria instead of defining the number of epochs, including a screenshot showing the final training epoch.

2.  Provide visualizations of the model’s training process, including a line graph of the loss and chosen evaluation metric.

3.  Assess the fitness of the model and any measures taken to address overfitting.

4.  Discuss the predictive accuracy of the trained network.


Part V:  Summary and Recommendations

E.  Provide the code used to save the trained network within the neural network.


F.  Discuss the functionality of your neural network, including the impact of the network architecture.


G.  Recommend a course of action based on your results.



Part VI: Reporting

H.  Create your neural network using an industry-relevant interactive development environment (e.g., an R Markdown document, a Jupyter Notebook, etc.). Include a PDF or HTML document of your executed notebook presentation.
