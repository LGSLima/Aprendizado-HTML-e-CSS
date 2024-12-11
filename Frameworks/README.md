# Aprendizado sobre Bootstrap: Minicurso sobre Frameworks CSS

Este repositório mostra o aprendizado sobre o framework Bootstrap, um dos frameworks CSS mais populares no desenvolvimento web.

Durante as aulas no Senai uma atividade onde a turma foi dividida em grupos e lhes foi dada a tarefa de criação de um minicurso sobre frameworks, no qual o grupo de que faço parte foi selecionado para apresentar o Bootstrap.

O Bootstrap fornece uma série de ferramentas e componentes prontos para uso, como grids, botões, formulários e navegação, que permitem aos desenvolvedores focar na funcionalidade e experiência do usuário, sem se preocupar com os detalhes do design.

## Objetivos do Aprendizado

- Consolidação do conhecimento: Aprofundar o entendimento sobre o Bootstrap, explorando suas funcionalidades, vantagens e como utilizá-lo em projetos reais.
- Habilidades de comunicação e apresentação: Desenvolver habilidades para compartilhar conhecimentos sobre o Bootstrap com colegas e explicar seus conceitos de forma clara.
- Trabalho em equipe: Colaborar com colegas na criação de materiais didáticos, apresentações e demonstrações práticas sobre o Bootstrap.
Autonomia: Explorar de maneira independente as funcionalidades do Bootstrap, tomando decisões sobre como aplicá-lo de acordo com as necessidades do projeto.

## Participantes do Projeto

- Expedita - [Github](https://github.com/ExpeditaNogueira)
- Jonnattan - [Github](https://github.com/JonnattanSS)
- Lucas Goebel - [Github](https://github.com/lgoebel)
- Luís Lima - [Github](https://github.com/LGSLima)

# Etapas do Minicurso

## Introdução ao Bootstrap

O que é o Bootstrap?

O Bootstrap é um framework front-end que facilita a criação de layouts responsivos e interativos. Criado por Mark Otto e Jacob Thornton no Twitter, o framework agora é mantido por uma comunidade ativa de desenvolvedores.

## Características principais

- Sistema de grid flexível: Organiza os elementos em 12 colunas, facilitando a criação de layouts responsivos.
- Componentes prontos: Botões, navegação, cards, tabelas, modais, etc.
- Customização fácil: Permite personalizar o design e os componentes de acordo com o projeto.
- Compatibilidade entre navegadores: Funciona de maneira consistente nos principais navegadores.

## Componentes e Funcionalidades do Bootstrap

Sistema de Grid O sistema de grid do Bootstrap permite que você crie layouts fluidos e responsivos com facilidade. Ele usa uma divisão em 12 colunas, e as colunas podem ser combinadas de várias formas para criar o layout desejado.

Exemplo de grid com 2 colunas:

```
<div class="row">
  <div class="col-md-6">Coluna 1</div>
  <div class="col-md-6">Coluna 2</div>
</div>
```

Botões O Bootstrap fornece uma maneira simples de criar botões com estilos prontos. Exemplo de botão:

```
<button class="btn btn-primary">Botão Primário</button>
```

Navegação O Bootstrap também oferece componentes para criar barras de navegação (navbars) altamente customizáveis. Exemplo de navbar:

```
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">Minha Empresa</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav">
      <li class="nav-item active">
        <a class="nav-link" href="#">Início</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Sobre</a>
      </li>
    </ul>
  </div>
</nav>
```

Formulários O framework também oferece uma maneira simples de criar formulários com inputs, checkboxes, e labels estilizados. Exemplo de formulário:

```
<form>
  <div class="form-group">
    <label for="exampleInputEmail1">Email</label>
    <input type="email" class="form-control" id="exampleInputEmail1" placeholder="Digite seu email">
  </div>
  <button type="submit" class="btn btn-primary">Enviar</button>
</form>
```

## Pesquisa e Preparação

O grupo deve realizar uma pesquisa sobre o Bootstrap, aprofundando-se nos seguintes tópicos:

- História e principais características: A evolução do Bootstrap e suas funcionalidades principais.
- Vantagens e desvantagens: Análise de prós e contras do uso do Bootstrap em projetos de diferentes tamanhos e complexidades.
- Componentes: Exploração dos componentes prontos, como grid, botões, formulários, modais, etc.
- Exemplos de projetos reais: Investigar como o Bootstrap é utilizado em sites e projetos reais para entender sua aplicabilidade.
- Documentação oficial: Referência para o uso de cada componente, personalização e melhores práticas.

## Criação do Material Didático

O grupo criará um material didático abrangente para o minicurso sobre o Bootstrap, incluindo:

- Slides de Apresentação: Para explicar o que é o Bootstrap e como usá-lo.
- Exercícios Práticos: Atividades interativas para aplicar o Bootstrap em exemplos reais.
- Demonstrações ao Vivo: Exemplo de como implementar o Bootstrap em um projeto real.

[Slide de Apresentação](https://www.canva.com/design/DAGXtiV-I8E/i544_ftIgBzOp20LMlBEGQ/edit?utm_content=DAGXtiV-I8E&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

## Sites e artigos

Sites e artigos que foram usados como material de pesquisa:

- Alura: Artigo sobre o framework, origem e suas definições do Bootstrap. [Acesse](https://www.alura.com.br/artigos/bootstrap).
- Documentação Oficial do Bootstrap: A principal fonte de informação para as explicações e demonstrações de funcionalidades e componentes do Bootstrap. [Acesse](https://getbootstrap.com).
- Home Host: Artigo sobre definições gerais, vantagens e desvantagens e considerações sobre a utilização do mesmo. [Acesse](https://www.homehost.com.br/blog/tutoriais/o-que-e-bootstrap/).
- Trybe: Artigo sobre responsividade, trazendo definições sobre o termo e argumentações sobre o uso da técnica. [Acesse](https://blog.betrybe.com/tecnologia/responsividade/).
- Hashtag: Artigo sobre as definições do framework, sobre sua utilização em projetos, importância, vantagens e desvantagens e um breve tutorial sobre como iniciar projetos com o mesmo. [Acesse](https://www.hashtagtreinamentos.com/bootstrap-o-que-e#como-usar-o-bootstrap-na-pratica).
- Napoleon: Breve artigo sobre o sistema de layout do Bootstrap Grid descrevendo sua funcionalidade, mostrando benefícios e dicas sobre o uso. [Acesse](https://napoleon.com.br/glossario/o-que-e-bootstrap-grid/).
- Loja de Temas: Artigo sobre a origem do Framework, além de seus recursos, características, estrutura e componentes. [Acesse](https://www.lojadetemas.com.br/bootstrap/).
- Mundo JS: Artigo sobre as mudanças do Bootstrap 5 em relação com sua versão anterior, mostrando novas funcionalidades, funcionalidades retiradas do framework, entre outras mudanças. [Acesse](https://www.mundojs.com.br/2020/09/11/bootstrap-5-mudancas/).

## Apresentação do Minicurso

Cada grupo apresentará seu minicurso sobre Bootstrap com uma duração entre 1h10min e 2h, explicando suas funcionalidades, demonstrando exemplos práticos, executando exercícios juntamente à turma e respondendo perguntas pertinentes.

# Conclusão

Este minicurso permite a criação e aprendizagem sobre sites responsivos e interativos, utilizando um framework que oferece recursos interessantes e prontos para uso. Além disso, o aprendizado envolve habilidades de pesquisa, trabalho em equipe, criação de material didático e habilidades de comunicação, preparando os alunos para projetar soluções práticas e eficientes no desenvolvimento web.

## Licença

Este projeto está licenciado sob a MIT License.