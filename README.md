# 🚗 Carro Inteligente (Algoritmo de Evolução de Gerações)
Este repositório contém o desenvolvimento de um trabalho simples utilizando Inteligência Articifial: 
- Como possuo interesse em algoritmos genéticos, desenvolvi este código inicial para aprender a manipular ferramentas de IA.
- Utilizando NEAT(NeuroEvolution of Augmenting Topologies/ NeuroEvolução de Topologia Aumentada), que é um código de evolução geracional que relaciona algoritmos de genética com redes neurais, criamos um carro entradas de neurônios, e seu objetivo é aprender a andar dentro da pista e concluir o percurso.

## 🔍 Objetivo
O objetivo do carro é através de evolução genética e utilizando seus sensores, concluir o percurso.

## 🔧Informações
1. O Carro possui 5 sensores: Esquerda/Direita, Diagonais Frontais Esquerda/Direita e Frente
2. Com os inputs destes neurônios, o carro poderá fazer 4 movimentos (Saídas/Outputs dos Neurônios): Curvar para Esquerda/Direita, Acelerar e Diminuir Velocidade.
3. E é com estes valores que faremos mutações e novas variações genéticas baseado em seu Fitness(Métrica de validação de resultado, neste caso será a distância percorrida), misturando códigos genéticos e criando novos carros, em busca de concluir o trajeto. De acordo com o Fitness, o carro poderá receber ou perder pontos, sendo bonificado ou penalizado de acordo com seu resultado, e as gerações com mais pontos passarão seu genes adiante.

## 🚀 Por que N.E.A.T.?
- Ao invés de algoritmos genéticos comuns, o NEAT é superior porque evolui simultaneamente tanto a topologia quanto os pesos das redes neurais, começando com estruturas simples que se tornam gradualmente mais complexas, quando comparado com outros algoritmos, o NEAT se sai melhor pois sua evolução não é baseada no conjunto de movimentos ou ações, mas nos valores dos inputs dos neuronios, ou seja, algoritmos simples de genética apenas reunem movimentos pré-definidos e os organiza de forma correta para que uma geração consiga realizar o percurso, enquanto NEAT explora uma rede neural que evolui o processamento e decisões de input/output dos neurônios, sendo muito mais eficiente na realização de desafios mais complexos.

## 📝 Conteúdo do Repositório
- `Self_Driving_Car` - Notebook contendo o código.
- `Arquivo_Neat.txt` - Configurações do NEAT
- `Carro.png` - Desenho do Carro
- `Pista().png` - Desenhos dos Trajetos
- `README.md` - Documento explicativo sobre o projeto.

## 🔬 Tecnologias Utilizadas
- **Linguagem:** Python (NEAT, Math, Random e PyGame)
- **Ambiente:** Google Collaboratory e Jupyter Notebook
