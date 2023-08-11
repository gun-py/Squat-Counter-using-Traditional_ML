### Packages used
- prophet
- pandas
- numpy
- seaborn
- datetime
- sklearn
- tensorflow
- keras
- certifi
- json
- math
- joblib
- os
- urllib
- flask
- warnings

### 3 Folders, it is advisable to maintain this structure while calling the API
    -> model1 -> app.py
                Base: http://127.0.0.1:5000
                Get Preds for 10 Days: http://127.0.0.1:5000/forecast/<stock_id>
    -> model2 -> app.py
                Base: http://127.0.0.1:5000`
                Get Preds for 10 Days: http://127.0.0.1:5000/forecast/<stock_id>
    -> model3 -> app.py
                Base: http://127.0.0.1:5000
                Get Preds for 10 Days: http://127.0.0.1:5000/forecast/<stock_id>

### Example Request for Stock QQQ:
    http://127.0.0.1:5000/forecast/QQQ
    
### Example Response for Stock QQQ:
`{"items": ["day1", "day2", "day3", "day4", "day5", "day6", "day7", "day8", "day9", "day10"], 
"values": [371.0381164550781, 367.29608154296875, 371.8160400390625, 365.5264587402344, 370.934814453125, 370.8857727050781, 369.0135803222656, 365.74957275390625, 366.057861328125, 372.68017578125]}`

