# Piano Simulator 🎹

Este é um simulador de piano virtual desenvolvido com HTML, CSS e JavaScript. O projeto permite tocar notas musicais clicando nas teclas do piano ou usando o teclado físico do seu computador. Inclui controles de volume e a opção de exibir ou ocultar as teclas.

**Acesse o repositório do seu projeto** no GitHub: [virtual-piano](https://nivaldo-nilngn.github.io/virtual-piano/).

## Funcionalidades

- Tocar notas musicais com o mouse ou teclado físico.
- Controle de volume integrado.
- Opção de exibir ou ocultar as teclas virtuais.
- Feedback visual nas teclas quando pressionadas.

## Tecnologias utilizadas

- **HTML**: Estrutura do piano e interface do usuário.
- **CSS**: Estilização do layout e teclas.
- **JavaScript**: Lógica de interação e reprodução dos sons.

## Como executar o projeto

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/Nivaldo-Nilngn/virtual-piano.git
   ```

2. **Navegue até o diretório do projeto**:
   ```bash
   cd piano-simulator
   ```

3. **Abra o arquivo `index.html` no seu navegador** para executar o piano virtual.

## Estrutura do projeto

```bash
piano-simulator/
├── src/
│   ├── script/
│   │   └── engine.js        # Código JavaScript responsável pela lógica do piano
│   ├── styles/
│   │   ├── reset.css        # Reset de estilo
│   │   └── main.css         # Estilização principal
│   └── tunes/               # Arquivos de áudio (.wav) para cada tecla
├── index.html               # Interface do piano virtual
└── README.md                # Instruções do projeto
```

## Controles

- **Teclas brancas**: A, S, D, F, G, H, J, K, L, Ç
- **Teclas pretas**: W, E, T, Y, U, O, P
- **Volume**: Controle deslizante para ajustar o volume do piano.

## Personalização

- Você pode adicionar ou substituir sons personalizados na pasta `src/tunes/`.
- As teclas podem ser estilizadas modificando o arquivo `main.css`. 

## Licença

Este projeto é de uso livre para estudos e personalizações. Sinta-se à vontade para melhorar o código e compartilhar!
