Sam Wagstaff, Mason Lo, Prathik Nagulugari


Part 1:


Context Questions
Why it is important to our project
How does the aviation industry define and measure a flight delay?
We need a consistent definition to classify flights as delayed or not delayed.
What factors are associated with departure delays, such as weather, airport congestion, and air traffic control?
These factors could become features in our prediction models.
Do departure delays differ between airlines and airports?
This could help us identify patterns associated with particular airlines, airports, or hubs.
How do time of day, day of the week, and season affect departure delays?
These variables may help us identify periods when delays are more likely.
How accurately can machine learning models predict departure delays?
We need to compare models and determine whether they can predict delays better than a simple baseline.
What limitations exist in publicly available flight data?
Missing weather details, crew scheduling, maintenance information, and other operational factors may limit our predictions.
How could airline delay predictions affect passengers and airlines?
Predictions could help passengers plan trips and help airlines understand operational problems, although inaccurate predictions could also mislead users.



Part 2: 

Keywords:

Airline departure delays
Flight delay prediction
Aviation operations
Airport congestion
Weather and flight delays
Air traffic management
Machine learning


4 test searches


Search string
Platform
Goal
“Flight delays” and prediction
Google scholar
Find research on predicting flight delays
“Departure delays” and weather
Google scholar
Find studies examining weather-related delays
("flight delay" or "airline delay") and ("machine learning" or classification)
Atkins library
Find studies using machine learning to predict delays
"airport congestion" and "departure delay"
Atkins library
Find research on airport traffic and operational causes of delays


The first and third searches are good starting points because they directly connect flight delays with prediction methods. The second and fourth searches can help us understand specific factors that may influence delays. We should refine the searches by adding terms such as random forest, logistic regression, airport, or departure time if the initial results are too broad.


Part 3: 

Esmaeilzadeh, E., & Mokhtarimousavi, S. (2020). Machine learning approach for flight departure delay prediction and analysis. Transportation Research Record, 2674(8), 145–159. https://doi.org/10.1177/0361198120930014
Summary and relevance: This study uses machine learning to investigate flight departure delays at three major New York City airports. It examines factors such as ground operations, weather, and demand compared with airport capacity. It is directly relevant because our group wants to predict departure delays and identify which variables are most influential.
Role: Background, methods, and interpretation.

Ye, B., Liu, B., Tian, Y., & Wan, L. (2020). A methodology for predicting aggregate flight departure delays in airports based on supervised learning. Sustainability, 12(7), Article 2749. https://doi.org/10.3390/su12072749
Summary and relevance: This article investigates supervised learning methods for predicting airport departure delays using flight and weather information. It compares several models, including linear regression, support vector machines, and tree-based approaches. It can help us choose suitable models and understand how weather and airport-level variables might improve predictions.
Role: Methods and model comparison.

Kim, S., & Park, E. (2024). Prediction of flight departure delays caused by weather conditions adopting data-driven approaches. Journal of Big Data, 11, Article 11. https://doi.org/10.1186/s40537-023-00867-5
Summary and relevance: This study examines machine learning models that predict departure delays using weather and flight data from three airports. It compares predictions made at different time horizons before departure. It is useful for determining how weather variables and the timing of predictions affect model performance.
Role: Background, measurement, and methods.

Muros Anguita, J. G., & Díaz Olariaga, O. (2024). Prediction of departure flight delays through the use of predictive tools based on machine learning/deep learning algorithms. The Aeronautical Journal, 128(1319), 111–133. https://doi.org/10.1017/aer.2023.41
Summary and relevance: This article compares machine learning and deep learning approaches for predicting departure delay durations. It also examines feature importance to identify which flight attributes contribute most to predictions. It is relevant to our goal of identifying influential factors, although our group plans to classify flights into delayed and not delayed rather than predict the exact delay duration.
Role: Methods and interpretation.









Part 4:


Original prompt:
Find peer-reviewed academic studies about predicting airline departure delays using machine learning. Focus on weather, airport congestion, airline differences, and factors that influence delays of more than 15 minutes. Provide APA citations, DOI links, and summaries of the findings.
Follow-up prompt 1:
What are the limitations of using machine learning to predict airline departure delays? Explain how missing variables, class imbalance, and differences between airports could affect the results.
Follow-up prompt 2:
What variables should our group include when predicting departure delays using BTS data? Which variables could cause data leakage if they are recorded after the prediction would be made?

Dai, M. (2024). A hybrid machine learning-based model for predicting flight delay through aviation big data. Scientific Reports, 14, Article 4603. https://doi.org/10.1038/s41598-024-55217-z
Summary and relevance: This study develops a hybrid machine learning approach and uses feature-selection methods to identify influential indicators of flight delays. It could help our group explore how to select useful variables and compare the performance of different prediction models.
Role: Methods and feature selection.
Flight delay causality: Machine learning technique in conjunction with random parameter statistical analysis. (2023). International Journal of Transportation Science and Technology, 12(1), 230–244. https://doi.org/10.1016/j.ijtst.2022.01.007
Summary and relevance: This study combines machine learning with statistical analysis to investigate factors associated with flight delays. It is useful because it highlights the importance of accounting for differences between flights and recognizing that patterns associated with delays do not automatically prove causation.
Role: Interpretation and critical perspective.
Traditional academic searching gives us more control over the search terms and lets us inspect the original articles directly. AI-assisted research can help us discover additional papers, identify useful keywords, and understand unfamiliar research methods more quickly. However, AI can produce inaccurate citations or misrepresent findings, so we must verify every source using its publisher page, DOI, Google Scholar, or Atkins Library.

Part 5:
Two credible nonacademic sources:
1. Bureau of Transportation Statistics (BTS) https://transtats.bts.gov/ This is our main source for historical flight records, departure delays, and on-time performance. It will help us build the dataset and define our target variable.
2. Federal Aviation Administration (FAA) https://www.faa.gov/ The FAA provides information about air traffic management, airport operations, and factors that affect the national airspace system. This will help us understand the operational context behind the patterns in our dataset.



