<h1 align="center" >
  <img alt="VFlows" title="VFlows" src=".github/logo.png" width="200px" style="background:#373435; padding:16px"/>
</h1>

<h3 align="center">
  Desafio Front-End
</h3>

<blockquote align="center">Tecnologia que flui!</blockquote>

<p align="center">
  <a href="#-Sobre-o-desafio">Sobre o desafio</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-Requisitos">Requisitos</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-Layout">Layout</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-Entrega">Entrega</a>
</p>

## 🚀 Sobre o desafio

O objetivo deste desafio é avaliar seus conhecimentos técnicos, como lida com os requisitos e capacidade de pensar em soluções.

Durante esse desafio vamos construir um formulário para cadastro de fornecedores e produtos.

O desenvolvimento do formulário deve seguir o layout existente na guia: **Layout**


## 📋 Requisitos


- **HTML**: na versão 5;
- **JAVASCRIPT**: Dar preferência a ao ECMA-6 no desenvolvimento do código; 
- **BOOTSTRAP**:  
  - [CSS](https://fluig.totvs.com/style-guide/css/fluig-style-guide.min.css)
  - [JQUERY-3.5.1 ](https://jquery.com/download/)

- **Outras Considerações**:
  - Usar documentação de recursos e estilos conforme este [link](https://style.fluig.com/)
  - Não deverão ser utilizados outros recursos tecnológicos para desenvolvimento 
  
 

### Sobre o preenchimento dos campos existentes no formulário de cadastro

- **Razão Social**: obrigatório
- **Nome Fantasia**: obrigatório
- **CNPJ**: obrigatório
- **Inscrição Estadual**: opcional
- **Inscrição Municipal**: opcional
- **Endereço**: obrigatório (deve ser preenchido automaticamente usando a API via CEP)
- **Nome da pessoa de contato**: obrigatório
- **Telefone**: obrigatório
- **E-mail**: obrigatório
- **Tabela de Produtos**: obrigatório a inclusão de pelo menos 1 item
  - **Descrição**: obrigatório
  - **Unidade de Medida**: obrigatório
  - **Quantidade em Estoque**: obrigatório
  - **Valor Unitário**: obrigatório
  - **Valor Total**: obrigatório (bloqueado, deve ser preenchido automaticamente considerando o valor unitário x a quantidade em estoque)
- **Tabela de Anexos**: obrigatório a inclusão de pelo menos 1 documento
  - Os documentos anexados deverão ser armazenados em memória (blob e session storage) para envio
  - O Botão Excluir (lixeira) - Ao excluir o documento, deverá ser excluído da memória
  - O Botão Visualizar (olho) - Ao visualizar o documento, deve ser feito o download
- **Botão Salvar Fornecedor**: ao clicar no botão, deverá ser aberto modal de loading de envio, e deverá ser formatado um JSON com os dados a serem enviados, conforme exemplo: [jsonExemplo](./jsonExemplo/) 
  - **OBS Sobre o JSON**: o JSON de resultado pode ser baixado ou apenas exibido no console do browser.

## O que será avaliado no projeto

- Qualidade de código.
- Estruturas de pastas.
- Criação de componentes.
- Soluções encontradas.
- Tolerância a exceções do código.
- Uso das tecnologias.

## 🎨 Layout

O layout do desafio está em anexo na pasta [docs](./docs/) deste repositório.

## 📅 Entrega

Esse desafio **deve ser entregue em um repositório público** do github e enviar um e-mail para `contato@vflows.com.br` **com o link** do repositório e com o assunto **`Entrega de desafio front-end`** para correção. (☞ ﾟヮﾟ)☞
NÃO COMPILAR EM REACT!!!! O DESAFIO É APENAS EM HTML+CSS+JS, SERÃO DESCONSIDERADOS PROJETOS EM REACT/NODE. 

---

Made by [VFlows](https://vflows.com.br)
