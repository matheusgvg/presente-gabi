# Presente Gabi

Uma página interativa e responsiva criada como homenagem de aniversário para a Gabriela.

O projeto apresenta uma experiência temática com cartas, animações, efeitos sonoros por vibração, confetes e pequenas interações de celebração.

## Demonstração

Como o projeto é composto por arquivos estáticos, ele pode ser executado diretamente no navegador ou publicado no GitHub Pages.

```text
https://github.com/matheusgvg/presente-gabi
```

## Funcionalidades

- Tela de abertura com animação e confetes
- Cartões interativos sobre liderança, disciplina e vocação
- Carta personalizada de homenagem
- Mini-game "Resgate em Chamas"
- Pontuação e recorde da partida durante a sessão
- Mensagens reveladas por meio de estrelas
- Interação final para acender a chama dos sonhos
- Design responsivo para celulares e computadores
- Suporte a vibração em dispositivos compatíveis
- Suporte a movimento reduzido por meio da preferência do sistema

## Tecnologias

- HTML5
- CSS3
- JavaScript
- [Canvas Confetti](https://github.com/catdad/canvas-confetti)
- Google Fonts
- SVG

Não é necessário instalar frameworks ou gerenciadores de pacotes.

## Como executar

### Abrir diretamente

1. Baixe ou clone este repositório:

```bash
git clone https://github.com/matheusgvg/presente-gabi.git
```

2. Entre na pasta do projeto:

```bash
cd presente-gabi
```

3. Abra o arquivo `index.html` no navegador.

### Executar com servidor local

Com Python instalado:

```bash
python -m http.server 8080
```

Depois, acesse `http://localhost:8080`.

Também é possível usar a extensão **Live Server** no VS Code.

## Estrutura do projeto

```text
presente-gabi/
├── .gitattributes
├── .gitignore
├── LICENSE
├── README.md
└── index.html
```

Todo o conteúdo, os estilos e os comportamentos JavaScript estão concentrados em `index.html`.

## Personalização

Para adaptar a página:

- Edite o título e o texto da homenagem em `index.html`
- Ajuste as cores no bloco `:root`
- Altere as mensagens das estrelas na constante `M`
- Modifique as regras e a pontuação do mini-game no script principal
- Substitua as fontes ou o tema visual no bloco `<style>`

## Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais informações.

## Autor

Desenvolvido por [Matheus Vieira](https://github.com/matheusgvg).

Portfólio: [matheus-portfolio-kappa.vercel.app](https://matheus-portfolio-kappa.vercel.app)

