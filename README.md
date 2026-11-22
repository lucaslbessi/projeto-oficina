# Controle de Ferramental e Oficina

## 1. Identificação da dupla
- Lucas Martins da Silva Bessi – RA: 1630482611029
  - Trabalho feito de forma individual devido a minha ausência na aula 
  que o trabalho foi proposto. Optei por fazer sozinho por não estar afim de
  ficar procurando dupla.

## 2. Motivo da escolha do tema
Trabalho na Sabó - Indústria e Comércio de Autopeças, na área de manutenção. Já
temos um sistema semelhante a esse no nosso almoxarifado. Optei por esse tema por   
já ter facilidade e por conhecer como o sistema funciona, facilitando minha lógica
e codificação.

## 3. Como modelamos o problema
- **Divisão de tarefas: Bom, como já foi dito, o trabalho foi feito de forma individual.
Separei os dias pra cada parte do projeto e organizar minha rotina pra conseguir finalizar
meu projeto. Com certeza teve alguns pontos que acabei pedindo um auxílio da IA para clarear   
um pouco a idéia, mas poucas vezes, apenas quando eu travava em algum ponto do trabalho e não
podia prolongar tanto, mesmo assim, fiz do uso da IA para aprender e aplicar.
- **Arquitetura:** ferramenta.h (interface), ferramenta.c (TAD),
  main.c (menu).
- **Memória:** vetor de 100 ponteiros iniciados em NULL; malloc só
  quando cadastra/carrega; free de todos ao sair.
- **Arquivo:** dados.txt, um registro por linha, campos separados por ";".
  Se não existir, o sistema inicia vazio.
- **Decisões:** código único validado; leitura com fgets+sscanf para
  evitar problemas de buffer; ';' digitado nos textos vira ','.
- **Relatório:** valor total patrimonial (quantidade × valor) e item de
  maior valor acumulado.

## 4. Compilação e execução
    gcc main.c ferramenta.c -o oficina -Wall
    ./oficina