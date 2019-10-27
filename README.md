# Deep Learning

Esse repositório contempla os códigos utilizados na disciplina COC891 da COPPE/UFRJ que aborda Deep Learning. A disponibilização do código aqui presente tem o objetivo de facilitar futuras consultas nessa área, assim como auxiliar futuros estudantes da disciplina.

## Trabalho inicial

A disciplina de Deep Learning possui um trabalho que deve ser desenvolvido ao longo do curso. O objetivo do mesmo é ser um trabalho investigativo sobre as tecnologias utilizadas relacionadas com o tema, mas com alguma aplicação de interesse do aluno.

Dessa forma, o tema de criptografia foi explorado, em especial a utilização de curvas elípticas do tipo ED25519. A proposta do trabalho era avaliar a capacidade de uma rede neural de prever alguns bits das chaves privadas com base nas chaves públicas, tema que seria de extremo interesse do autor.

Devido a complexidade do tema, o problema foi dividido entre:
1. determinar se redes neurais com memória podem fazer as operações básicas da criptografia (soma, resto/mod, rotação).
2. definir uma arquitetura de redes neurais para a proposta.

Logo, para esse trabalho estamos apenas interessados nos primeiros aspectos, especificamente em determinar se uma rede neural recorrente é capaz de realizar operações de resto com elevada acurácia.

Os arquivos que estão disponíveis no repositório podem ser executados utilizando o [Google Colaboratory](https://colab.research.google.com) ou o ambiente [Gradient da PaperSpace](https://gradient.paperspace.com/).

## Referências

ZAREMBA, Wojciech; SUTSKEVER, Ilya. Learning to Execute. arXiv [cs.NE], 2014. Disponível em: <https://arxiv.org/abs/1410.4615>.