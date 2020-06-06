=======
<p align="center">
  <img src="https://github.com/datasmartlab/frontend-challenge/blob/master/.github/assets/logo.png" height="150" width="150" alt="Datasmart" />
</p>

<h3 align="center">Datasmart</h3>

<p align="center">Desafio para os candidatos à vaga de desenvolvedor Frontend na Datasmart.</p>

<p align="center">:pushpin: Local de trabalho: Avaré - SP</p>

<br>

<div align="center">
  <a href="#memo-apresentação">Apresentação</a>   |   <a href="#clipboard-instruções">Instruções</a>   |   <a href="#wrench-especificações-técnicas">Especificações técnicas</a>   |   <a href="#gear-especificações-funcionais">Especificações funcionais</a>   |   <a href="#heavy_check_mark-o-que-será-avaliado">O que será avaliado?</a>   |   <a href="#question-dúvidas">Dúvidas</a>
</div>

<br>

## :memo: Apresentação

O desafio é desenvolver uma aplicação responsiva consumindo os dados da API da Marvel, seguindo todas as especificações abaixo.

Esse desafio é um teste de nivelamento e para avaliarmos o quão bom você é :)

O desafio é público e todos os interessados que fizerem pull request receberão um feedback da nossa equipe.

Esperamos que todas as pessoas que queiram trabalhar conosco tentem realizá-lo.

A Datasmart trabalha sempre com feedbacks construtivos e, portanto, daremos sempre uma atenção especial para todos que submeterem o teste. Vale a pena tentar! :)

## :clipboard: Instruções

1. Faça um fork desse projeto;

2. Crie uma branch para o seu desafio no padrão: `git checkout -b frontend-challenge/seu-nome-sobrenome`;

3. Realize o desafio seguindo a seção de especificações;

4. Crie um README com uma descrição e instruções para compilar e rodar o projeto;

5. Adicione seu desafio para transferência `git add .`;

6. Faça commit do seu desafio `git commit -m 'Challenge'`;

7. Faça o push da branch: `git push origin frontend-challenge/seu-nome-sobrenome`;

8. Abra um pull request com o nome `Challenge: Seu Nome Sobrenome`;

9. Envie um email para `vagas@datasmart.com.br` com o título: `Desenvolvedor Frontend - Seu Nome Sobrenome`. Adicione seu telefone, LinkedIn, seu perfil do GitHub e em anexo seu currículo.

## :wrench: Especificações técnicas

- Utilizar framework ReactJS;

- Usar Redux para estado dos componentes;

- Utilizar Material UI para design;

- Usar styled-components para CSS;

- Mobile first e responsivo;

- Cores, layout e imagens são livres para sua criatividade;

- Utilizar a [API da Marvel](https://developer.marvel.com) para consumir os dados. É necessário se cadastrar no site e obter suas chaves de API.

## :gear: Especificações funcionais

### Tela Inicial

- Essa tela terá um cabeçalho com o nome da aplicação e uma listagem de personagens vindos da API da Marvel.

- O retorno desta requisição da API com a lista dos personagens deve ser gravado no Redux.

- A listagem deve ser construída consumindo o estado do Redux.

- A listagem deve possuir os campos: thumbnail, nome e um link para a página de detalhes do personagem.

- Essa página deverá ter paginação, utilizando os recursos de paginação da API.

### Tela de Detalhes

- O usuário ao clicar em algum personagem, ele irá para a tela de detalhes. Ao entrar nesta tela, deve ser feito uma nova requisição para consumir os dados deste personagem e exibir em uma lista, os detalhes não precisam serem gravados no Redux.

- A partir desse retorno, deve-se montar na tela uma listagem com os campos: nome, descrição, número de histórias em quadrinhos (comics), séries (series) e histórias (stories).

- Essa tela deve ter um botão para voltar à tela inicial.

## :heavy_check_mark: O que será avaliado?

- Conhecimento do framework React e suas bibliotecas utilizadas;

- Boas práticas com o código (lint, indentação, padrões, etc);

- Organização e estrutura do projeto;

- Código HTML, CSS e Javascript;

- Uso de componentização;

- Uso do Git;

- Design e criatividade;

- Perfomance;

- Documentação.

## :question: Dúvidas

Em caso de dúvidas, crie uma issue ou envie um e-mail para `vagas@datasmart.com.br`.

Boa sorte!

---

Desenvolvido com 💖 por Datasmart
>>>>>>> fd5a5ed06da23042b4d09f06bd3fa67e465c902f
