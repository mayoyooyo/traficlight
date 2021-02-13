# Traffic-light
![parking-lot](parking-lot-exceed.png)

A website that shown the parking lot status and compute the total payment for the user including real-time graph
while collecting data through dbmongo.

## Requirements (For running in local)
```
pip install flask_pymongo
```

## Features
* Hardware
    - Maximum 4 parking places.
    - Able to check that if the parking lot is available or not.
    - Able to collect and represent the data of parking period.
    
* Website
    - Able to show the available parking places.
        - Red will be shown if the car is at car park.
        - Green will be shown if the car park is available.
    - Able to compute the parking lot payment due to period of time.
    - A real-time updated graph that represent total-money VS. time-interval.
    
* Computation
    - The amount of payment is equal to 20 XCoin per minute

## Link
* [Database](http://158.108.182.0:4321/app/exceed_backend/exceed_backend/g17/view/1)
    