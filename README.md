# 🦆 Purple Duck: Legacy of the Ancient Flock

Um jogo 2D no estilo *roguelike*, desenvolvido em JavaScript, com o objetivo de demonstrar na prática o funcionamento de **matrizes bidimensionais** por meio de uma experiência interativa.

O jogador controla o último representante da linhagem ancestral dos patos e precisa atravessar arenas, enfrentar inimigos, derrotar chefes e sobreviver a ondas cada vez mais difíceis.
<img width="1317" height="600" alt="image" src="https://github.com/user-attachments/assets/00425ded-c3cf-4dca-9504-4cd7e054fefa" />


## 🎯 Objetivo do projeto

O projeto foi desenvolvido com finalidade acadêmica, utilizando a lógica de um jogo para tornar conceitos de programação mais visuais e compreensíveis.

Seu principal objetivo é demonstrar como uma matriz 2D pode representar um ambiente virtual e controlar a posição de diferentes elementos dentro dele.

## 🧠 Conceitos aplicados

O jogo utiliza uma matriz de **17 colunas por 12 linhas** para representar o mapa.

Cada posição da matriz armazena um valor que identifica o elemento presente naquela célula:

| Valor | Representação |
|---|---|
| `0` | Espaço vazio |
| `1` | Parede |
| `2` | Jogador |
| `3` | Inimigo |
| `4` | Item |
| `5` | Saída |
| `6` | Chefe (Boss) |

Além da representação do mapa, o projeto demonstra:

- Matrizes bidimensionais e acesso por índices `[linha][coluna]`;
- Geração procedural de mapas;
- Atualização dinâmica de posições;
- Detecção de colisões;
- Movimentação e lógica de inimigos;
- Cálculos de distância e movimentação;
- Manipulação de elementos gráficos com Canvas.

## 🖥️ Painel demonstrativo

Um dos principais recursos do projeto é o painel técnico lateral, que acompanha a execução do jogo em tempo real.

Nele é possível visualizar:

- A matriz que representa o mapa;
- A posição atual do jogador;
- Coordenadas em pixels e índices da matriz;
- Velocidade e movimentação;
- Quantidade de inimigos e projéteis;
- Cálculos utilizados durante a execução;
- Registro de eventos do jogo.

A proposta é conectar o que acontece visualmente na tela com as estruturas de dados responsáveis pelo funcionamento do jogo.

## 🎮 Controles

| Tecla / Ação | Função |
|---|---|
| `W` `A` `S` `D` | Movimentar o personagem |
| Mouse | Mirar e atirar |
| `SHIFT` | Dash |
| `SPACE` | Pular |
| `Q` | Ativar escudo |
| `E` | Disparo radial |
| `R` | Habilidade ultimate |

## 🛠️ Tecnologias utilizadas

- **HTML5:** estrutura da aplicação;
- **CSS3:** estilização e interface;
- **JavaScript:** lógica do jogo, movimentação, colisões e manipulação da matriz;
- **Canvas API:** renderização dos elementos gráficos.

O projeto não depende de frameworks ou bibliotecas externas.

## ▶️ Como executar

1. Faça o download ou clone este repositório.
2. Abra a pasta do projeto.
3. Execute o arquivo `purple_duck_corrigido.html` diretamente no navegador.

Não é necessário instalar dependências ou configurar um servidor.

## 📚 Aprendizados

O desenvolvimento deste projeto permitiu explorar a aplicação de estruturas de dados em um cenário interativo, relacionando conceitos teóricos de programação com comportamentos visíveis na execução de um software.

Mais do que representar uma matriz em código, a proposta foi demonstrar como ela pode ser utilizada para organizar, interpretar e controlar os elementos de um ambiente virtual.

---

**Projeto acadêmico | Análise e Desenvolvimento de Sistemas**
