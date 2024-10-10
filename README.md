# Classificador de Nível de Herói

Este projeto foi desenvolvido como parte de um desafio da **Digital Innovation One (DIO)**, com o objetivo de criar um sistema que classifique um herói baseado na sua quantidade de experiência (XP). Dependendo do valor de XP, o herói será classificado em diferentes níveis.

## 📝 Descrição do Projeto

O objetivo do projeto é criar um classificador de nível de herói usando conceitos de programação como variáveis, operadores, laços de repetição e estruturas de decisão. O sistema solicita o nome do herói e a quantidade de experiência (XP), e em seguida, exibe uma mensagem com o nome e o nível do herói de acordo com a quantidade de XP.

### 🛠️ Tecnologias Utilizadas

- **JavaScript** (Node.js)
- Git e GitHub para versionamento
- Editor de código: Visual Studio Code


## ⚙️ Como Funciona

O sistema utiliza uma estrutura de decisão para classificar o herói nos seguintes níveis, com base na quantidade de XP informada:

- **Ferro**: XP < 1.000
- **Bronze**: XP entre 1.001 e 2.000
- **Prata**: XP entre 2.001 e 5.000
- **Ouro**: XP entre 5.001 e 7.000
- **Platina**: XP entre 7.001 e 8.000
- **Ascendente**: XP entre 8.001 e 9.000
- **Imortal**: XP entre 9.001 e 10.000
- **Radiante**: XP ≥ 10.001

### Exemplo de Saída

```bash
Digite o nome do herói: Thor
Digite a quantidade de XP: 6500
O Herói de nome Thor está no nível de Ouro
