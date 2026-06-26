
# 📘 Assignment: Jogo da Forca

## 🎯 Objective

Construir um jogo da forca em Python que use strings, loops, condicionais e entrada de dados do usuário para permitir que o jogador adivinhe uma palavra ocultada.

## 📝 Tasks

### 🛠️ Configuração do jogo e seleção da palavra

#### Description
Crie a estrutura inicial do jogo e escolha uma palavra secreta aleatoriamente a partir de uma lista de opções.

#### Requirements
O programa completo deve:

- Selecionar uma palavra aleatória a partir de uma lista predefinida
- Inicializar a exibição da palavra oculta usando underscores
- Rastrear o número de tentativas incorretas restantes
- Registrar as letras já palpites pelo jogador

### 🛠️ Jogabilidade e interação com o usuário

#### Description
Implemente a lógica de palpites, atualização do progresso da palavra e mensagens de fim de jogo.

#### Requirements
O programa completo deve:

- Aceitar palpites de letras pelo jogador
- Mostrar o progresso atual usando um formato como `_ _ _`
- Revelar letras corretas nas posições correspondentes
- Diminuir o número de tentativas para palpites incorretos
- Encerrar o jogo quando a palavra for totalmente adivinhada ou quando as tentativas acabarem
- Exibir uma mensagem de vitória ou derrota no final