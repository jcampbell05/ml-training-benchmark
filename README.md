# ml-training-benchmark

An easy to use CreateML project for benchmarking ML for evaluating ML performance on Macbooks when using Apple's optimised ML tools.

Steps:

1. Install Xcode
2. Download this project (Must be a fresh copy for each Mac)
3. Open the Benchmark.mlproj file
4. Click the dropbox under training data, click select files and then click the "training_images" folder.
5. Click the dropbox under testing data, click select files and then click the "testing_images" folder.
6. Wait for CreateML to finish loading the data.
7. Make sure iterations are set to 100 and all augemtnations are enabled.
8. Click Train at the top and wait until it has finished.
9. Results will be on the right hand side.

## Results

Feel free to open a PR adding your machine to this list.

- Macbook 13" 2020 i5 2.0Ghz 16GB RAM: 53 minutes
- Macbook 16" 2019 i9 1.3GHz 32GB RAM: 55 minutes
- Macbook 14" 2021 M1 Pro 10 Core 16GB RAM: 23 Minutes
