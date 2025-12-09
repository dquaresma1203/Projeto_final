# Projeto_final
# Sincronização em Sistemas de Tempo Real: Produtor-Consumidor com Threads POSIX
# Objetivo: demonstração do domínio dos mecanismos de programação concorrente e sincronização entre threads, que são cruciais para a construção de Sistemas Eletrônicos de Tempo Real
# Mecanismos de Sincronização (IPC/Threads)
O projeto utiliza Threads POSIX dentro de um único processo para simular as tarefas de aquisição e processamento. Os mecanismos de sincronização empregados são:
1. Mutexes ('pthread_mutex_t')
2.Variáveis de Condição ('pthread_cond_t')
# Para compilar
gcc prod_cons.c -o prod_cons -pthread
# Para executar
./prod_cons
