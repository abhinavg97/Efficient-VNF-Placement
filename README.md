# Efficient-VNF-Placement
Efficient VNF Placement


To run the algorithm, follow the below steps:

* g++ min_path.cpp -std=c++14
* ./a.out NUM_REQUESTS


*NUM_REQUESTS is the number of requests that is given to the algorithm*

In the repo scripts are present to automate the testing process and analyze the collected logs to give the final results

Run:

* bash automation.sh | tee stats.logs
* python3 log_processing.py

