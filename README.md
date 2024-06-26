# Projeto de Energia Limpa e Acessível

## Objetivo

O objetivo do projeto é desenvolver uma aplicação que auxilia o acesso a energia limpa de forma acessível, ajudando no desenvolvimento sustentável.

## Problema

Por conta da energia limpa não ser um assunto muito discutido, o projeto busca informar mais as pessoas e auxiliar na adoção de tecnologias que utilizam ou geram energia limpa e acessível.

## Tipo de solução

A solução é uma página web que oferece informações para conscientização sobre energia limpa, além de ajudar na implementação dessas tecnologias com manuais para instalações e recomendações de compras para certos produtos relacionados à energia limpa.

## Requisitos Funcionais

- Realizar consultas sobre produtos disponíveis e redirecionar para o site de vendas.
- Fornecer suporte sobre o uso dos produtos.
- Auxiliar com informações sobre a importância da energia limpa.
- Disponibilizar manuais sobre os produtos recomendados.

## Requisitos Não Funcionais

- Desempenho eficiente.
- Compatibilidade com diversos tipos de dispositivos.
- Páginas simples e de fácil uso.
- Organização do código para possíveis atualizações.
- 
## Casos de uso
![Diagrama sem nome drawio](https://github.com/ViniciusCasF/Trabalho_Pratico/assets/162627005/0f00bcb8-2cb2-45fd-856e-bb32e3a16d4d)

## Modelo da arquitetura
![Diagrama sem nome (2) drawio](https://github.com/ViniciusCasF/Trabalho_Pratico/assets/162627005/26a59175-d741-4972-b020-94feb85d1b72)

## As escolhas de tecnologias
O meu projeto vai usar as tecnologias:

**HTML** Para a formatação das paginas.

**CSS** Para melhorar o design.

**JAVASCRIPT** Para fazer as interações das paginas.

## O projeto arquitetural elaborado
O meu projeto foi feito se baseando no C4 model, onde no **diagrama de contexto** do sistema possui o sistema e o usuário interagindo com o mesmo,
e o meu sistema é composto por 4 páginas web, que nada mais são que os meus **containers**, e a primeira apresenta um pouco sobre o projeto, além de apresentar mais 3 páginas, a de dicas, que vai ser composta por alguns textos e dados
estatísticos para incentivar o usuário que visitou a página para investir em energia limpa e acessível. A outra é uma página com 
indicações de onde e quais produtos comprar, com algumas sugestões de preços, e um link de redirecionamento 
para sites de terceiros. E por fim as páginas possuem os **componentes**, a primeira possui um banner com frases sobre a energia limpa e acessível, além de 3
botões que vão direcionar para as outras 3 páginas, na de dicas possui uma caixa de texto que vai conter as informações já apresentadas, na página 
de indicações vai ter caixas de texto para fazer uma breve descrição do produto que está sendo apresentado, além de uma imagem e o link de redirecionamento 
para o site de venda, e por fim a página de instruções, que possui uma caixa de texto com o nome do produto, e dois links de redirecionamento, um para baixar
o manual do produto e o outro com um vídeo de explicação do manuseio do produto recomendado.

## A justificativa do modelo escolhido
O modelo escolhido foi o de camadas, e isso se deve pela simplicidade que é entender o mesmo, além de como o meu 
projeto não é grande, a estrutura do mesmo fica bem mais organizada.


## Casos de teste

### Página Principal
#### Teste 1: Verificação do Comportamento do Banner
**Passos:**

Acesse a página principal.
Leia as mensagens do banner até ele completar o ciclo e voltar para a primeira mensagem.

**Resultado esperado:** As mensagens devem trocar e não apresentar nenhum erro de design e ortografia.

#### Teste 2: Verificação do Botão da Página de Dicas
**Passos:**

Acesse a página principal.
Clique no botão de dicas.

**Resultado esperado:** Deve acontecer o redirecionamento para a página de dicas.

#### Teste 3: Verificação do Botão da Página de Indicações
**Passos:**

Acesse a página principal.
Clique no botão de indicações.

**Resultado esperado:** Deve acontecer o redirecionamento para a página de dicas.

### Página de Dicas
#### Teste 1: Verificação do Layout da Página
**Passos:**

Acesse a página principal.
Clique no botão de dicas.
Acesse a página de dicas.
Analise a página e cheque se o layout está de acordo.

**Resultado esperado:** Uma página com um layout estilizado.

#### Teste 2: Verificação do Texto das Dicas
**Passos:**

Acesse a página principal.
Clique no botão de dicas.
Acesse a página de dicas.
Leia o conteúdo das dicas.

**Resultado esperado:** As dicas devem ter informações condizentes e com a gramática adequada.

#### Teste 3: Verificação das Imagens das Dicas
**Passos:**

Acesse a página principal.
Clique no botão de dicas.
Acesse a página de dicas.
Analise todas as imagens disponíveis na página.

**Resultado esperado:** As imagens devem se relacionar com o que está sendo dito no texto, além de ter uma boa qualidade.

### Página de Indicações
#### Teste 1: Verificar os Produtos da Página
**Passos:**

Acesse a página principal.
Clique no botão de indicações.
Acesse a página de indicações.
Analise os produtos que estão sendo anunciados.

**Resultado esperado:** Todos os produtos devem ser sobre o tema de energia limpa e acessível.

#### Teste 2: Verificar os Links de Redirecionamento
**Passos:**

Acesse a página principal.
Clique no botão de indicações.
Acesse a página de indicações.
Clique no link de redirecionamento.

**Resultado esperado:** O usuário é redirecionado para a página de compra do produto indicado.

#### Teste 3: Verifica se as Imagens dos Produtos Condizem com os Nomes
**Passos:**

Acesse a página principal.
Clique no botão de indicações.
Acesse a página de indicações.
Visualize todas as imagens disponíveis na página.

**Resultado esperado:** Todas as fotos estão relacionadas com os nomes dos produtos indicados.

### Página de Instruções
#### Teste 1: Verificar se os Nomes dos Produtos são os Mesmos dos Indicados
**Passos:**

Acesse a página principal.
Clique no botão de instruções.
Acesse a página de instruções.
Leia todos os nomes dos produtos.

**Resultado esperado:** Todos os nomes são os mesmos dos indicados, e eles estão na mesma ordem da página de indicados.

#### Teste 2: Verifica se o Redirecionamento de Download Funciona
**Passos:**

Acesse a página principal.
Clique no botão de instruções.
Acesse a página de instruções.
Clique no botão para fazer o download do manual do produto.

**Resultado esperado:** O usuário deve ser redirecionado para fazer o download do manual do produto em português.

#### Teste 3: Verifica se o Vídeo Relaciona com o Produto Indicado
**Passos:**

Acesse a página principal.
Clique no botão de instruções.
Acesse a página de instruções.
Clique no botão de redirecionamento do vídeo de ajuda para o manuseio do produto.

**Resultado esperado:** O usuário deve ser redirecionado para um vídeo que ajude de forma simples e rápida de como usar o produto indicado.

