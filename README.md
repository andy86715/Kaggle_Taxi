# Kaggle 紐約計程車預測價錢競賽
「機器學習導論」課程期末報告

https://www.kaggle.com/c/new-york-city-taxi-fare-prediction
## Reports
[書面報告](https://github.com/andy86715/Kaggle_Taxi/blob/master/final%20report/機器學習期末報告書.docx)

[投影片簡報](https://github.com/andy86715/Kaggle_Taxi/blob/master/final%20report/機器學習期末報告.pptx)

## Methods
### - 探索式資料分析 (小資料)
競賽提供的資料集一共有5千5百多萬筆資料 (5.7GB)，因此先隨機切出10萬筆資料簡易查看

[01_簡易EDA for 10萬筆資料.ipynb](https://github.com/andy86715/Kaggle_Taxi/blob/master/01_簡易EDA%20for%2010萬筆資料.ipynb)

### - 資料轉換
將CSV檔轉成feather格式，加快讀取時間

[02_匯入所有資料&轉換.ipynb](/02_匯入所有資料&轉換.ipynb/)

### - 資料前處理
針對所有資料進行資料清整以及查看

[03_前處理 for all data.ipynb](https://github.com/andy86715/Kaggle_Taxi/blob/master/03_前處理%20for%20all%20data.ipynb)

[04_EDA for all data.ipynb](https://github.com/andy86715/Kaggle_Taxi/blob/master/04_EDA%20for%20all%20data.ipynb)

### - 進行預測
Random Forest Regression & XGboost Regression

[05_ML.ipynb](/05_ML.ipynb/)
