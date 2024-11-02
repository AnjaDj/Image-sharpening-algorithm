# Analysis & Comparison Methods for Accelerating an Image Sharpening Algorithm

First, we measure the execution time of the base algorithm using the function <i><b> void BaseAlgorithm(string inputFile, string outputFile).</b></i><br>
Next, we track the execution time for different optimization approaches: <br>
1. parallelization on a multi-core processor with <i><b> void ParallelAlgorithm(string inputFile, string outputFile)</b></i><br>
2. cache optimization with <i><b> void CacheAlgorithm(string inputFile, string outputFile)</b></i><br>
3. combination of parallelism and cache optimization with <i><b> void ParallelCacheAlgorithm(string inputFile, string outputFile)</b></i><br>

