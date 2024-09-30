# Este projeto implementa um sistema de gerenciamento de treinamento voltado para cirurgias laparoscópicas e procedimentos médicos. O sistema acompanha o progresso dos alunos em diferentes treinamentos e exibe os resultados graficamente. Este notebook inclui funções de inicialização de treinamentos, atualizações de progresso, e visualização dos dados de desempenho dos alunos.

## Funcionalidades
- Inicialização de Treinamentos: Permite registrar novos alunos e atribuir treinamentos específicos.
- Atualização de Progresso: Registra o avanço de cada aluno em seus treinamentos.
- Finalização de Treinamentos: Indica a conclusão de um treinamento pelo aluno.
- Visualização Gráfica: Exibe gráficos de linha mostrando o progresso de cada aluno nos diferentes treinamentos.
- Estrutura do Código
  
## Funções principais:
- inicializar_treinamento(aluno_id, treinamento_nome): Inicializa um novo treinamento para o aluno.
- atualizar_progresso(aluno_id, treinamento_id, progresso): Atualiza o progresso de um aluno em um determinado treinamento.
- finalizar_treinamento(aluno_id, treinamento_id): Marca o treinamento como concluído.
- exibir_resultados(): Exibe o progresso e status dos treinamentos.
  
## Simulação de Uso:
- Exemplo com 3 alunos e 2 treinamentos, incluindo a atualização do progresso e finalização dos cursos.

## Visualização Gráfica:
- Utiliza a biblioteca matplotlib para gerar gráficos que mostram o progresso dos alunos.

## Requisitos
- Python 3.x
- Bibliotecas: matplotlib, numpy

## Como Executar
Clone o repositório, instale os requisitos ( pip install -r requirements.txt ) e abra o Jupyter Notebook e execute as células para simular o sistema de gerenciamento de treinamento.

# Alunos:
- Bryan Willian – RM:551305​
- Gabriel Freitas - RM:550187​
- Guilherme Daher - RM:98611​
- Gustavo Akio – RM:550241​
- Lucas Vassão - RM:98607​
