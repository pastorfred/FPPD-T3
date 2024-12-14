Para executar versão sequencial:

compilar arquivo ms_seq.c

gcc ms_seq.c -o seq.out

executar o arquivo de output na linha de comando com os parâmetros:

./seq.out [tarefas] [tamanho] qsort/bsort

Para executar versão paralela:

compilar arquivo ms_mpi.c

mpicc -g ms_mpi.c -o mpi.out

executar o arquivo da mesma maneira que o sequencial:

./mpi.out [tarefas] [tamanho] qsort