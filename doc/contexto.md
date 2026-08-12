# Site de Leilões

## Objetivo do projeto

Desenvolver um site de **leilões de produtos colecionáveis e diversos**, como:

- Cards colecionáveis
- Discos de vinil
- Action figures
- Itens de coleção
- Brinquedos
- Outros produtos relacionados

Todo o desenvolvimento das páginas deve ser realizado dentro da pasta `telas`.

##  Tecnologias

Utilizar **exclusivamente** as seguintes tecnologias:

- HTML
- CSS

### Restrições

- Não utilizar JavaScript.
- Não utilizar frameworks ou bibliotecas externas.
- Não instalar dependências adicionais.
- Não utilizar pré-processadores de CSS.
- Não utilizar tecnologias que não estejam especificadas neste documento.

O projeto deve funcionar utilizando somente **HTML e CSS**.

##  Estrutura de pastas

A estrutura do projeto deve ser organizada de maneira clara e padronizada.

Dentro da pasta `telas`, devem existir duas pastas principais:
telas/
├── html/
└── css/
##  Padrão de nomenclatura
-Para uma página chamada 'index.html' deve existir index.css
- Todas as páginas devem seguir um padrão de nomenclatura consistente.
  -O nome do arquivo HTML deve ser exatamente correspondente ao nome do seu arquivo CSS.
-Para cada página HTML, deve existir um arquivo CSS específico para ela.
 -Não utilizar nomes genéricos ou pouco descritivos, como style.css pagina1.css teste.css estiloNovo.css

##  Organização dos arquivos
-Cada página deve possuir seu próprio arquivo CSS contendo sua estilização específica.

## Fontes
- Não utilizar fontes externas ou importar fontes da internet.
 -Devem ser utilizadas somente as fontes já disponíveis no banco de fontes do projeto.
-Todas as fontes utilizadas pelo projeto devem estar armazenadas na pasta fonte/
  -Não utilizar Google Fonts.
  -Não utilizar fontes carregadas por URLs externas.
  -Não adicionar novas fontes ao projeto sem autorização.
  -Não utilizar uma fonte que não esteja disponível na pasta fonte/

## CSS
-Cada página deve possuir um arquivo CSS próprio.
-O CSS de cada página deve conter principalmente os estilos específicos daquela página.
-Evitar criar um único arquivo CSS gigante contendo toda a estilização do projeto.

## Regras gerais de desenvolvimento
- Manter uma estrutura de arquivos simples e organizada.
- Utilizar nomes de arquivos claros e descritivos.
- Manter o mesmo padrão de nomenclatura em todo o projeto.
- Utilizar somente HTML e CSS.
- Não instalar dependências.
- Não utilizar frameworks.
- Não utilizar bibliotecas externas.
- Não utilizar JavaScript.
- Não utilizar fontes externas.
- Manter as fontes utilizadas dentro da pasta fonte.
- Criar um arquivo CSS correspondente para cada página HTML.
- Manter os arquivos HTML dentro de telas/html.
- Manter os arquivos CSS dentro de telas/css.
##  Estrutura esperada


Ao final, a estrutura básica do projeto deve seguir este padrão:

projeto/
│
├── fonte/
│   └── [fontes permitidas pelo projeto]
│
├── telas/
│   │
│   ├── html/
│   │   ├── index.html
│   │   ├── login.html
│   │   ├── cadastro.html
│   │   ├── produtos.html
│   │   └── leilao.html
│   │
│   └── css/
│       ├── index.css
│       ├── login.css
│       ├── cadastro.css
│       ├── produtos.css
│       └── leilao.css
│
└── [demais arquivos necessários]

A estrutura pode receber novas páginas conforme o desenvolvimento do sistema, desde que elas sigam as mesmas regras de organização e nomenclatura.  


