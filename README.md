# 🛒 Online Retail Recommendation System
This project builds a recommendation system that suggests products to users based on customer purchase patterns. It uses collaborative filtering and cosine similarity techniques to personalize the experience for online retail users.
## Features
- Recommends top 10 products based on customer ID
- Uses cosine similarity on user-item matrix
- Built with Python and scikit-learn
- Easy to expand into web application using Flask
## Dataset
You can use the [Online Retail Dataset](https://1drv.ms/x/c/376ce3e57debd49e/EYyjl25-ChZPtOShsmpCmuQBP1N-Gn_0K805Jr9RnN6jsw?e=O4KMGz) or any similar Excel-based retail dataset. Ensure the dataset has `CustomerID`, `StockCode`, and `Description` columns.
## How to Run
1. Install dependencies:
pip install -r requirements.txt
2. Place your dataset file (`OnlineRetail.xlsx`) in the same folder.
3. Run the script:
python recommender.py
4. Enter a valid `CustomerID` when prompted.
## Sample Output
Enter a valid Customer ID from the dataset :  17850
Recommended Products for Customer ID 17850
           Description                        
StockCode  WOODEN FRAME ANTIQUE WHITE             50
           WHITE HANGING HEART T-LIGHT HOLDER     39
           WOODEN PICTURE FRAME WHITE FINISH      37
           WOOD 2 DRAWER CABINET WHITE FINISH     36
           WOOD S/3 CABINET ANT WHITE FINISH      26
           WOOD BLACK BOARD ANT WHITE FINISH      25
           CHOCOLATE HOT WATER BOTTLE             18
           LOVE BUILDING BLOCK WORD               17
           3 DRAWER ANTIQUE WHITE WOOD CABINET    15
           KNITTED UNION FLAG HOT WATER BOTTLE    15
dtype: int64

## Technologies
- Python
- Pandas
- Scikit-learn
- Excel dataset

## Future Improvements
- Add Flask-based web interface
- Support hybrid recommendations (content + collaborative)
- Handle cold-start problems
## Author
chirra Sathwika, B.Tech CSE