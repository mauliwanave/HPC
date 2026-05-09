1. BFS & DFS (OpenMP)

File:

✅ Compile:
g++ 1_BFS_DFS.cpp -o bfsdfs -fopenmp
✅ Run:
./bfsdfs
🔵 2. Parallel Bubble + Merge Sort

File:

✅ Compile:
g++ 2_parallel_bubble_merge.cpp -o sort -fopenmp
✅ Run:
./sort
🔵 3. Parallel Reduction (OpenMP)

File:

⚠️ Important:
Works best on Linux / WSL
Windows normal compiler may fail
✅ Compile:
g++ 3_parallel_reduction.cpp -o reduction -fopenmp
✅ Run:
./reduction
🔵 4. CUDA Programs (.cu files)

👉 Files:

3_parallel_reduction.cu
4_matrix_multiplication.cu
4_vector_addition.cu
✅ Compile (for ANY .cu file):
nvcc filename.cu -o output
Example:
nvcc 4_matrix_multiplication.cu -o matrix
✅ Run:
./matrix

👉 Same for others:

nvcc 4_vector_addition.cu -o vector
./vector
🔵 5. Mandelbrot (Python CUDA - Numba)

File:

✅ Install dependencies (if not installed):
pip install numpy matplotlib numba
✅ Run:
python 5_mandelbrot_numba.py
