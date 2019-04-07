# linear_regression_house_price
Simple Linear Regression model to predict house prices from sq ft. and number of bedrooms.

### Sample Data

    Sq.ft  |Rooms| Price
    1600.0 | 3.0 | 329900.0
    2400.0 | 3.0 | 369000.0
    1416.0 | 2.0 | 232000.0
    3000.0 | 4.0 | 539900.0
    1985.0 | 4.0 | 299900.0
    1534.0 | 3.0 | 314900.0
    1427.0 | 3.0 | 198999.0
    1380.0 | 3.0 | 212000.0
    1494.0 | 3.0 | 242500.0

### Regression Model

![image](https://user-images.githubusercontent.com/46073809/55689720-dfd99800-593c-11e9-9aa0-352779b444d6.png)
### Equations

![image](https://user-images.githubusercontent.com/46073809/55689749-2b8c4180-593d-11e9-859e-5c2d24615c1a.png)

![image](https://user-images.githubusercontent.com/46073809/55689758-465eb600-593d-11e9-85f8-2005861480a7.png)
![image](https://user-images.githubusercontent.com/46073809/55689770-71490a00-593d-11e9-9df0-150331610aed.png)

### Results

    Final weights = [0.6112004973868039, 170.24324016689596, 1.3369235114128564]
    
    Desired   | Predicted
    [345000.] | 362964.54693
    [549000.] | 717581.216198
    [287000.] | 368071.844135
    [368500.] | 283288.036685
    [329900.] | 381008.993465
    [314000.] | 437020.356403
    [299000.] | 204296.510171
    [179900.] | 145050.52567
    [299900.] | 315296.439684
    [239500.] | 204807.239892

![image](https://user-images.githubusercontent.com/46073809/55689808-25e32b80-593e-11e9-83a0-2e370d5e3eb9.png)

![image](https://user-images.githubusercontent.com/46073809/55689821-43b09080-593e-11e9-8589-9558d01a684c.png)
