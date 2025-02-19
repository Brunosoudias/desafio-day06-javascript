# Quiz Application

Este projeto é uma aplicação de quiz simples desenvolvida com HTML, CSS e JavaScript. A aplicação apresenta uma série de perguntas de múltipla escolha e calcula a pontuação do usuário com base nas respostas corretas.

## Estrutura do Projeto

O projeto possui a seguinte estrutura de arquivos:

index.html prize.png questions.js script.js style.css

### Arquivos

- **index.html**: Contém a estrutura HTML da aplicação.
- **prize.png**: Imagem exibida na área de pontuação.
- **questions.js**: Contém as perguntas do quiz.
- **script.js**: Contém a lógica principal do quiz.
- **style.css**: Contém os estilos CSS para a aplicação.

## Descrição dos Arquivos

### `index.html`

Este arquivo define a estrutura básica da aplicação, incluindo a barra de progresso, a área de perguntas, a área de pontuação e o rodapé. Ele também inclui os scripts `questions.js` e `script.js`.

### `prize.png`

Imagem exibida na área de pontuação quando o quiz é finalizado.

### `questions.js`

Este arquivo contém um array de objetos, onde cada objeto representa uma pergunta do quiz. Cada pergunta possui uma propriedade `question` (texto da pergunta), `options` (array de opções) e `answer` (índice da resposta correta).

### `script.js`

Este arquivo contém a lógica principal do quiz, incluindo as seguintes funções:

- `showQuestion()`: Exibe a pergunta atual e suas opções.
- `optionClickEvent(e)`: Manipula o evento de clique em uma opção.
- `finishQuiz()`: Calcula e exibe a pontuação final do usuário.
- `resetEvent()`: Reinicia o quiz.

### `style.css`

Este arquivo contém os estilos CSS para a aplicação, incluindo estilos para a barra de progresso, área de perguntas, área de pontuação e outros elementos.

## Como Executar

1. Clone o repositório ou baixe os arquivos.
2. Abra o arquivo `index.html` em um navegador web.

### Passos Detalhados

1. **Clonar o Repositório**
   ```sh
   git clone <URL_DO_REPOSITORIO>

ou baixe os arquivos diretamente.

Navegar até o Diretório do Projeto

Abrir o Arquivo HTML

No Windows, você pode simplesmente clicar duas vezes no arquivo index.html.
Ou, no terminal, você pode usar:
Funcionalidades
Exibição de perguntas de múltipla escolha.
Cálculo da pontuação com base nas respostas corretas.
Exibição de uma barra de progresso.
Exibição de uma área de pontuação com feedback baseado na pontuação do usuário.
Opção de reiniciar o quiz.

# Autor
Criado por Bruno Sousa.
