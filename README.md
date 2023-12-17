Este repositório é uma implementação de algoritmos de aprendizado por reforço utilizando os exemplo MountainCar e CarRacing disponíveis no playground Gymanasium da OpenAi. Trata-se de um trabalho feito durante a disciplina de IA do Programa de Pós-Graduação em Computação Aplicada do Instituto Federal do Espírito Santo. Turma 2023/02

### Executando o algoritmo

Abra o arquivo `main.ipynb` e execute célula-a-célula. Todas as instalações necessárias estão implementadas. Antes de cada célula existe uma breve descrição do que ela faz.

### Resultados

Para cada tentativa de treinamento existe uma pasta do tipo `TryX` (X = número da tentativa). Esta pasta contém um arquivo txt com a arquitetura implementada durante o treinamento, o vídeo do agente em ação e o gráfico de recompensa média (a partir da tentativa 6)

Os gráficos de recompensa média das tentativas 8 a 12 são cumulativos. Então, apesar da legenda dizer 0 - 400 mil steps, são somados os 400 mil anteriores.

- No caso do **CarRacing** o melhor resultado está em `CarRacing\Try11`.
- No caso do **MountainCar** o melhor resultado está em `MountainCar\Try2`
