t1_IA
Tic Tac Toe com IA

Este projeto implementa uma IA para o jogo da velha (Tic Tac Toe) utilizando algoritmos de classificação como k-NN, MLP, Árvores de Decisão e SVM. O projeto também inclui um front-end em linha de comando, onde um jogador humano pode jogar contra a IA. A IA verifica o estado do jogo e fornece feedback ao jogador após cada jogada.
Como executar o projeto
Requisitos

    Python 3.x
    Bibliotecas: pandas, numpy, scikit-learn, jupyter, matplotlib


Instale as dependências necessárias executando o seguinte comando:

bash

    pip install -r requirements.txt

    Abra os arquivos .ipynb no VSCode com o Jupyter Notebooks habilitado.

    Execute o notebook t1_IA.ipynb para treinar os modelos de IA (k-NN, MLP, Árvores de Decisão e SVM).

    Após o treinamento dos modelos, execute o notebook main.ipynb para iniciar o jogo da velha e jogar contra a IA.

Escolhendo o Modelo

Após o treinamento dos modelos no notebook t1_IA.ipynb, o jogador pode escolher qual modelo usar para prever o estado do jogo (k-NN, MLP, Árvores de Decisão ou SVM). O modelo escolhido será utilizado para verificar o estado do jogo após cada jogada.
Arquivos do Projeto

    t1_IA.ipynb: Notebook para o treinamento dos modelos de IA.
    requirements.txt: Lista de dependências do projeto.