Trabalho Escalonador com Listas de Prioridade

Professor/Mestre: Dimmy Magalhaes 

materia: algoritmos e estruturas de dados 

integrantes: 

Isac Araujo Albuquerque ( isac.albuquerque@somosicev.com );

Mardson Varela Lima (Mardson.lima@somosicev.com ); 

Vyctor Gabriel Machado Tôrres ( Vyctor.gabriel@somosicev.com ) 




link do Repositorio: https://github.com/PiedroCraft1379/Trabalho_Escalonador_com_Listas_de_Prioridade

descriçao do projeto: 

ListaCircular.java: permite inserir no fim da lista, remover do inicio e fim, exibir todos os elementos da lista, verificar se a lista esta vazia, obter o tamanho atual da lista 

Main.java: Cria alguns processos de exemplo e milhões de processos gerados dinamicamente com características aleatória; Executa a simulação por um número definido de ciclos, processando os processos no scheduler;Mostra progresso, estatísticas de execução e uso de recursos; Ao final, exibe um relatório geral com tempo total, taxa de criação de processos e memória utilizada.

Processos.java: é um modelo de objeto para armazenar e gerenciar informações de processos.

Scheduler.java: Ele cria processos com prioridade, número de ciclos e recursos necessários, organiza-os em filas e os executa ciclo a ciclo, aplicando políticas de prioridade, anti-inanição e bloqueio por recurso. No final, o sistema mostra estatísticas como quantidade de ciclos executados, processos finalizados e taxa de ociosidade da CPU.

instruções claras de comocompilar e executar o projeto:

COMPILADOR: Visual Code

REQUISITOS: java idk  = 11

BASH = javac ListaCircular.java Processos.java Scheduler.java Main.java

Exemplo de saida:

=== RELATÓRIO FINAL ===

=== ESTATISTICAS DO SISTEMA ===
Ciclos executados: 15084
Processos executados: 15084
Processos finalizados: 50
Ciclos ociosos: 0
Taxa de ociosidade: 0,0%
Processos pendentes: 0
===============================
ESTATÍSTICAS DO ARQUIVO:
   Total de processos lidos: 50
   Prioridade alta: 0
   Prioridade média: 0
   Prioridade baixa: 50
   Com recurso DISCO: 0
PERFORMANCE GERAL:
   Tempo total: 33,35s
   Memória utilizada: 51 MB
========================



