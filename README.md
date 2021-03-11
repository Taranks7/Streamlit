 # Stock closing prices of S&P 500 companies 

- using the streamlit framework to create a web application 
- view application (when running) at: http://192.168.81.130:8501
![sc](https://user-images.githubusercontent.com/74196907/110850488-bf908180-82a7-11eb-942c-2b04b9091d69.png)

## Setting up the environment:
```
cd stockprice_webscrape
# CREATE VIRTUAL ENVIRONMENT
# virtualenv venv -p python3
source venv/bin/activate
```
- The data are presumed to be at ~/stockprice_webscrape
- Install dependencies: pip install -r requirements.txt

## Run 
```
streamlit run sp500.py
```
