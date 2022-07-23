# Stream_Micros
stream benchmark tests to measre memory bandwith 

# Compile Commands:
Single Processor:
gcc -O stream.c -o stream

Multi Processor:
gcc -fopenmp -D_OPENMP stream.c -o stream 
export OMP_NUM_THREADS=2
