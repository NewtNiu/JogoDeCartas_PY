<div align="center">

# Atividade 3 – Jogo de Cartas em Python

</div>

**Componente Curricular:** Algoritmos e Programação  
**Professor:** Felipe Grando / Jefferson Caramori  
**Data de entrega:** 2024/2  
**Aluno:** Niumar Girardi  
**Curso:** Ciência da Computação – UFFS  

---

## 1. Objetivo

O objetivo desta atividade é desenvolver, em linguagem Python, a abstração de um jogo de cartas utilizando conceitos fundamentais de algoritmos e programação, como estruturas de dados, funções, controle de fluxo e interação com o usuário via terminal.

O jogo simula uma partida entre dois jogadores, seguindo regras pré-definidas, incluindo embaralhamento de cartas, distribuição, validação de jogadas e definição automática do vencedor ou empate.

---

## 2. Estrutura de Pastas

O trabalho é composto por apenas um arquivo, conforme especificado na descrição da atividade:

```
📁 jogo-de-cartas/  
├── jogoDeCartas.py   
├── DescricaoDaAtividade.pdf
└── README.md       
```

- `jogoDeCartas.py`: contém todo o código-fonte do jogo.
- `DescricaoDaAtividade.pdf`: Documento fornecido pelo professor para a realização da Atividade.
- `README.md`: documentação do projeto.

## 3. Código

O código foi desenvolvido totalmente em Python e utiliza a biblioteca padrão `random` para realizar o embaralhamento das cartas.

### Principais partes do código:

#### 🔹 Biblioteca utilizada
```python
import random
```
Responsável por embaralhar o baralho de forma aleatória.

---

🔹 **Função `tela_inicial()`**

Responsável por exibir o menu principal do jogo, permitindo ao usuário:

- Iniciar uma nova partida
- Visualizar as regras
- Encerrar o programa

---

🔹 **Função `mostrar_regras()`**

Exibe as regras básicas do jogo diretamente no terminal, facilitando o entendimento do funcionamento antes de iniciar a partida.

---

🔹 **Função `iniciar_jogo()`**

É a função principal do jogo, responsável por:
- Solicitar o nome dos jogadores
- Criar e embaralhar o baralho (40 cartas)
- Distribuir 5 cartas para cada jogador
- Definir a carta inicial da mesa
- Controlar os turnos dos jogadores
- Validar se a carta jogada possui mesma cor ou número
- Permitir compra de carta quando não houver jogadas possíveis
- Encerrar o jogo quando houver vencedor, empate ou quando o baralho acabar

---

🔹 **Estrutura das cartas**

As cartas são representadas por dicionários Python, contendo:

- `numero:` valor da carta (1 a 9)
- `cor:` cor da carta (azul, vermelha, amarela ou verde)

Exemplo:

```py
{'cor': 'azul', 'numero': 5}
```

---

## 4. Compilação / Execução

Como o projeto foi desenvolvido em Python, não é necessário compilação.

**Para executar o jogo:**

1. Certifique-se de ter o Python 3 instalado.
2. No terminal, navegue até a pasta do projeto.
3. Execute o comando:

```py
python jogoDeCartas.py
```
ou, dependendo do sistema:

```py
python3 jogoDeCartas.py
```

---

## 5. Desenvolvido por:

Trabalho desenvolvido para a disciplina Algoritmos e Programação
Universidade Federal da Fronteira Sul – UFFS

Desenvolvido por Niumar Girardi – Ciência da Computação
2024/2