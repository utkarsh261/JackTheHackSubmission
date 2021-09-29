### Setup Instructions


**To start the Smart Bag app** 
1. `cd SmartBagWebApp`
1. `yarn`
2. `yarn start`


##### Project will open on port 3000

**To start the Vehicle Route Optimization app**
1. Simply open index.html in a browser.

**To Start Vehicle Optimization API**
1. `cd VehicleOptimizationAPI` 
2. Create a [virtual-env](https://docs.python.org/3/tutorial/venv.html)
3. Install requirements:
    ```
    pip3 install -r requirements.txt
    ```
4. Launch server
    ``` 
    cd src
    python3 server.py
    ```
5. Test (in a different terminal session while server is stll running)
    ```
    py.test
    ```



