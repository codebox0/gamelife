To compile:
$ mpicc gamelife.c -o gamelife -fopenmp

To execute:
  With Sequential or openMP method:
  $ ./gamelife [options] -m [0|1]
  $ OMP_NUM_THREADS=N ./gamelife [options] -m 1
  
  With MPI method:
  $ mpirun -np N gamelife [options] -m 2
  
  With MPI optimized method:
  $ mpirun -np N gamelife [options] -m 3

Authors
  José Iván López González
  Jacob David Rodríguez Bordón
  

https://github.com/joseivanlopez/gamelife
