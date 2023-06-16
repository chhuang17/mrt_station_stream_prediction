# mrt_station_stream_prediction
This project aims to predict the stream of people for each MRT station in the Taipei Metro system in real-time. In this project, we applied three ML models:
* __AutoEncoder__: To help us conduct the dimension reduction works for the time-series data.
* __K-Means__: To classify all the MRT stations into suitable classes by the inbound and outbound pattern in each hour.
* __XGBoost__: To predict each station's inbound and outbound stream in the next hour.


The `stream_prediction.pdf` contains 5 slides for the summary of this project. You can check the code of this project in `stream_prediction.ipynb`; however, the instruction in the jupyter notebook is written in Mandarin.
