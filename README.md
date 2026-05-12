# Convert

![Cover do projeto](img/Cover.png
)

Uma pequena aplicação web de conversão de moedas que transforma valores em Dólares, Euros ou Libras para Reais.

Design no Figma: [https://www.figma.com/design/htZiMsnBLIogvVSxr1IVqQ/Conversor-de-Moedas--Community-?node-id=671-560&m=dev](https://www.figma.com/design/htZiMsnBLIogvVSxr1IVqQ/Conversor-de-Moedas--Community-?node-id=671-560&m=dev)

## Funcionalidades

- Conversão de valores para Real brasileiro (BRL)
- Suporte a três moedas: USD, EUR e GBP
- Validação para aceitar apenas números no campo de valor
- Exibição de taxa de câmbio e resultado formatado em `pt-BR`

## Arquivos principais

- `index.html` - estrutura HTML e formulário de entrada
- `styles.css` - estilos da interface e comportamento visual
- `script.js` - lógica de conversão e formatação de valores
- `img/` - imagens e ícones usados no layout

## Como usar

1. Abra `index.html` no navegador.
2. Insira o valor numérico a ser convertido.
3. Selecione a moeda de origem (`Dólar Americano`, `Euro` ou `Libra Esterlina`).
4. Clique em `Converter em reais`.
5. O resultado em Reais será exibido no rodapé.

## Câmbios usados

- `USD`: 4.87
- `EUR`: 5.32
- `GBP`: 6.08

## Observações

- A conversão é feita localmente no navegador, sem necessidade de servidor.
- A formatação do resultado utiliza o padrão `pt-BR` para moeda brasileira.
- Caso o valor não seja numérico, o aplicativo mostra um alerta pedindo correção.

## Estrutura de pastas

```
CONVERT/
├── index.html
├── script.js
├── styles.css
└── img/
    ├── bg.png
    ├── check.svg
    ├── chevron-down.svg
    └── logo.svg
```
