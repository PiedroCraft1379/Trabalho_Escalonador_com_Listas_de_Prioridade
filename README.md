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

=== SIMULADOR DE SCHEDULER ===
Configuração:
   - Processos dinâmicos: 5.000.000
   - Ciclos de simulação: 50.000
   - Modo detalhado: NÃO

Adicionando processos de exemplo...
? 5 processos de exemplo adicionados

Adicionando 5.000.000 processos dinamicamente...
   Progresso: 999.995/5.000.000 (20,0%) - Tempo: 0s
   
   Progresso: 1.999.995/5.000.000 (40,0%) - Tempo: 0s
   
   Progresso: 2.999.995/5.000.000 (60,0%) - Tempo: 0s
   
   Progresso: 3.999.995/5.000.000 (80,0%) - Tempo: 0s
   
   Progresso: 4.999.995/5.000.000 (100,0%) - Tempo: 0s
? Geração concluída em 0 segundos
   Distribuição:
   
     Alta (1): 1.665.849 processos
     
     Média (2): 1.666.397 processos
     
     Baixa (3): 1.667.754 processos
     
     Com DISCO: 100 processos

Iniciando simulação...

(Modo silencioso ativado para melhor performance)

=== CICLO 1 ===

-> EXECUTANDO: Processo P1 (Prioridade 1, Ciclos restantes: 6)

-> REQUEUE: Processo P1 voltou para fila (restam 5 ciclos)

--- ESTADO DAS FILAS ---



