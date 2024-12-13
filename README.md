# SmartFarm Model

## Dataset Source
Dataset source: (https://www.kaggle.com/datasets/greegtitan/indonesia-climate)


## Model Description:
- Cleaning the data (including dropping unused columns, and removing duplicate data)
- Preprocessing (including one-hot encoding)
- Building the model using TensorFlow time series dan LSTM
- Recommendation output with value of model prediction result

All the steps bellow based on: https://www.tensorflow.org/tutorials/structured_data/time_series?hl=id


## Model Destinatik Source Code
This model was built by using a collaborative filtering method and the model code documentation is below:
[SmartFarm Source Code](https://github.com/SaintXCeed/C242PS165-Machine-Learning/blob/4595b515610f508e4b59619a8e82e84d082f0e82/SmartFarm-climate.ipynb) 


## Exported Model File
This model was saved:
- using `tf.saved_model()` at [SmartFarm_model_tfjs](https://github.com/destinatik-team/destinatik/tree/ml-path/destinatik_model_tfjs)
- and using terminal `!tensorflowjs_converter --input_format=tf_saved_model --output_format=tfjs_graph_model model_tfjs ./export_tfjs/` (tensorflowjs converter) [SmartFarm_model_tfjs](https://github.com/destinatik-team/destinatik/tree/ml-path/export_tfjs)
