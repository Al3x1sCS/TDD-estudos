# TDD-estudos
# Repositório de Estudos TDD

Este repositório é destinado aos estudos sobre Test Driven Development (TDD). Aqui serão abordados temas como:

## O que é TDD?
- [Definição do que é TDD.](#o-que-é-tdd-afinal)

## Por que usar TDD?
- [Discussão sobre os benefícios do uso do TDD.](#por-que-usar)

## Problemática
- [Video que explica o problema com o TDD](https://github.com/Al3x1sCS/TDD-estudos/blob/main/README.md#como-n%C3%A3o-usar)

## Red, Green, Refactor!
- [Red-green-refactor](https://github.com/Al3x1sCS/TDD-estudos/blob/main/README.md#o-que-%C3%A9-red-green-refactor)

## Como funciona o TDD?
- Análise do funcionamento do TDD, incluindo seus passos básicos e sua aplicação na prática.

## Os 3 passos básicos do TDD
- Escrever um teste
- Executar todos os testes e ver se falha
- Escrever o código mínimo para passar no teste

## Diferenças entre TDD e teste manual
- Comparação entre as técnicas de TDD e teste manual, incluindo suas vantagens e desvantagens.

## Como escrever testes eficientes
- Dicas e boas práticas para escrever testes eficientes e eficazes.

## Como usar frameworks de teste
- Uso de frameworks de teste como XCTest, JUnit, NUnit, entre outros.

## Como automatizar seus testes
- Discussão sobre a automatização de testes e sua importância no processo de TDD.

## Como integrar TDD com seu processo de desenvolvimento de software
- Integração do TDD em um processo de desenvolvimento de software, incluindo sua implementação na prática.

## Como garantir a qualidade do seu código com TDD
- Discussão sobre a garantia da qualidade do código ao usar o TDD.

Este repositório é uma ferramenta para quem deseja aprender sobre TDD e como aplicá-lo na prática. Fique à vontade para contribuir com seus conhecimentos e aprender juntos.

# O que é TDD afinal?

Test-Driven Development (TDD) é uma metodologia de desenvolvimento de software que se concentra na escrita de testes antes de escrever o código propriamente dito. Em outras palavras, você escreve um teste para a funcionalidade que deseja implementar e só então implementa o código para passar neste teste.

A ideia por trás do TDD é que, ao escrever testes antes do código, você pode ter certeza de que o seu código funciona como esperado, sem bugs ou erros. Além disso, você também pode ter uma visão mais clara da funcionalidade que deseja implementar, o que pode ajudar a evitar problemas de design e a garantir uma implementação mais eficiente e clara.

É uma boa ideia praticar o TDD em seus projetos pessoais ou em projetos de estudo. E também estudar sobre frameworks de teste como XCTest, JUnit, NUnit, entre outros.

Referências:
- [O que é TDD?](https://dzone.com/articles/what-is-test-driven-development-tdd)
- [Is TDD Dead?](https://martinfowler.com/articles/is-tdd-dead/)

# Por que usar?

Test-Driven Development (TDD) é uma metodologia de desenvolvimento de software que se concentra na escrita de testes antes de escrever o código propriamente dito. Esta abordagem tem sido amplamente adotada pela comunidade de desenvolvimento de software, e há vários argumentos que justificam sua utilização.

Uma das vantagens mais importantes do TDD é que ele ajuda a garantir a qualidade do código. Ao escrever testes antes do código, os desenvolvedores podem ter certeza de que o seu código funciona como esperado, sem bugs ou erros. Além disso, ao escrever testes primeiro, os desenvolvedores também são obrigados a pensar na funcionalidade que desejam implementar antes de começar a codificar. Isso pode ajudar a evitar problemas de design e a garantir uma implementação mais eficiente e clara.

Outra vantagem do TDD é que ele ajuda a tornar o código mais fácil de manter e atualizar. Ao ter testes automatizados para cada pequena parte do código, os desenvolvedores podem ser mais confiantes ao fazer alterações no futuro, pois sabem que seus testes serão executados automaticamente e avisarão se algo estiver quebrado.

Além disso, o TDD também ajuda a melhorar a colaboração entre os membros da equipe. Ao escrever testes primeiro, todos os envolvidos na equipe têm uma visão clara da funcionalidade que está sendo implementada, o que pode ajudar a evitar mal-entendidos e garantir que todos trabalhem na mesma direção.

Em resumo, o TDD é uma metodologia de desenvolvimento de software altamente recomendada que pode ajudar a garantir a qualidade do código, torná-lo mais fácil de manter e atualizar, e melhorar a colaboração entre os membros da equipe. Ao adotar o TDD em seus projetos de software, você pode ter mais confiança no código que está escrevendo e pode garantir que sua equipe trabalhe de forma mais eficiente e colaborativa.

Referências:
- [Why Test-Driven Development (TDD)](https://marsner.com/blog/why-test-driven-development-tdd/)

# Como não usar!

Ian Cooper, explica os problemas que ele notou com a forma como as pessoas estão praticando o TDD (Desenvolvimento Guiado por Testes) e por que houve crescente resistência ao TDD. Ele vem praticando TDD desde 2004 e escreveu extensas suites de testes. Ao longo do tempo, ele notou que algumas das suites de teste eram muito difíceis e caras de manter. Ele notou que havia muita resistência ao TDD em 2005-2006, com muitos desenvolvedores dizendo que não queriam fazê-lo e que era uma ideia louca. Alguns desenvolvedores inteligentes que ele respeitava eram resistentes ao TDD, apesar de seus esforços para explicar seus benefícios.

O principal problema com o TDD, de acordo com Cooper, é que se tornou uma "guerra religiosa". As pessoas se tornaram apegadas (atached) a certas práticas do TDD e não ouvirão outras ideias. Isso resultou em uma falta de inovação e progresso no TDD.

Cooper sugere que a maneira de resolver esse problema é reiniciar a prática do TDD e retornar às suas raízes. Ele sugere olhar para ideias como red-green-refactor, refatoração de código green, etc. e entender como essas ideias devem ser aplicadas. Ele também sugere olhar para onde foram feitos erros na prática do TDD que levaram a formas adversas de fazer TDD.

Ele também fala sobre a importância de se concentrar nas seções iniciais do TDD e como equipes podem trabalhar juntas para passar pelas seções posteriores. Ele enfatiza que o TDD não é apenas um conjunto de regras a seguir, mas uma forma de pensar sobre o desenvolvimento de software. O objetivo deve ser escrever um código limpo e mantível que seja fácil de testar.

Referências:
- [TDD, Where Did It All Go Wrong (Ian Cooper)](https://www.youtube.com/watch?v=EZ05e7EMOLM)

# O que é red-green-refactor?

Red-green-refactor é uma metodologia de TDD que se concentra em criar testes antes de escrever o código. A metodologia é dividida em três etapas:

1. Vermelho (Red) - Primeiro, você escreve um teste para a funcionalidade que você deseja implementar. Quando você executa o teste, ele falhará, pois você ainda não implementou a funcionalidade.

2. Verde (Green) - Na segunda etapa, você implementa o código o mais simples possível para passar no teste que você escreveu na etapa anterior.

3. Refatorar (Refactor) - Na última etapa, você refatora o seu código, melhorando a sua estrutura e qualidade, sem mudar a funcionalidade.

A metodologia Red-green-refactor é útil para garantir que você esteja construindo software de qualidade e testável, sem se preocupar com a implementação excessivamente complexa desde o início.

Referências:
- [Red, Green, Refactor!](https://medium.com/@tunkhine126/red-green-refactor-42b5b643b506)

# Links para aprender mais sobre TDD

- [Test-Driven Development - Martin Fowler](https://martinfowler.com/bliki/TestDrivenDevelopment.html)
- [The basics of Test-Driven Development - Agile Alliance](https://www.agilealliance.org/glossary/tdd/)
