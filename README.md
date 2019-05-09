# TSP4

### Prerequisites

You must use c++17 and g++-8 for pthreads to compile correctly.


### Installing

Donload and Unzip TSP4 file. Navigate to TSP4 file in Terminal. Use make comand to compile.
The ./tsp program takes 3 arguments, filename for cities, population size, mutation rate.

# Questions 
### Which parameters did you choose? 
Our best tour came while experimenting. We had:

NUM_ITER = 9'000'000

pop_size = 1'000

mut_rate = 10 

nthread  = 4

More Specifically,

time ./tsp challenge.tsv 1000 10 4

### How long is the resulting best tour you found?
Our best tour was  5708.72

### What is the run time? 
My computer has 4 cores, and each test was run with the parameters mentionde above.

With 4 threads the real time is 29.723 seconds. This is about 34% of the real time with 1 thread. The real time with 1 thread is 1 minute and 21.48 seconds. With 2 threads the run time is 37.846 seconds. This is 46% of 1 threads real time.

## Authors

* **Becca Luff** - *Initial work* - [BeccaLuff](https://github.com/BeccaLuff)
* **Devin Arrants** - *Initial work* - [DevinArrants](https://github.com/DevinArrants)

