# multithreading
1.Matrix Multiplication Function (matrix_multiply): This function performs the matrix multiplication operation between two matrices A and B, storing the result in the result list at the specified index.

2.Threaded Execution (run_with_threads): This function orchestrates the parallel execution of matrix multiplication using multiple threads. It measures the time taken to execute the matrix multiplication using the specified number of threads.

3.Input Data:

-Matrix A is a constant 1000x1000 matrix.

-results is a list to store the results of matrix multiplication.

-matrices is a list containing 100 randomly generated 1000x1000 matrices.

4.Execution and Time Measurement:

The run_with_threads function is called with different numbers of threads (1 to 10).
For each number of threads, the time taken to execute the matrix multiplication is recorded.

5.Result Table:
The result table displays the time taken for matrix multiplication using different numbers of threads.

6.Result Graph:
The result graph visualizes the relationship between the number of threads and the time taken for matrix multiplication. Each point on the graph represents the time taken for a specific number of threads.

X-axis: Number of Threads

Y-axis: Time taken (seconds)

Title: No of threads vs Time taken

Grid: Enabled for better visualization


-->Interpretation:
As the number of threads increases, the time taken for matrix multiplication decreases.
There's a diminishing return in performance improvement beyond a certain number of threads, indicating that adding more threads doesn't significantly reduce the computation time.
The graph helps in identifying the optimal number of threads for efficient execution, balancing between parallelism and overhead.
