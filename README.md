# Programação Aumentada por IA

> **Como utilizar Inteligência Artificial para aprender programação com mais eficiência, sem criar dependência da geração automática de código.**

---

## Sobre o projeto

Este repositório documenta o projeto desenvolvido no **NotebookLM** como parte do desafio da **DIO**.

Meu objetivo não foi criar um sistema que programa por mim, mas entender **como encaixar a IA dentro do processo de aprendizagem de programação**. Durante o estudo, percebi que meu maior atrito não era escrever código, e sim saber **o que estudar, como organizar o conhecimento e como transformar dúvidas em aprendizado contínuo**.

A proposta deste projeto é utilizar a IA como uma ferramenta de apoio para pesquisa, organização de conhecimento e revisão, buscando aumentar o aproveitamento do tempo de estudo e trabalho — inspirado na ideia de produtividade defendida por profissionais como **Fabio Akita**, onde eficiência vem do conhecimento potencializado por ferramentas, e não da substituição do programador.

---

# Objetivos

* Entender onde a IA realmente agrega valor na programação.
* Reduzir o tempo perdido procurando informações desconectadas.
* Criar um método de estudo reutilizável utilizando NotebookLM.
* Utilizar IA para aprender conceitos, revisar ideias e organizar conhecimento.
* Evitar a dependência da geração automática de código.

---

# O problema que motivou este projeto

Com a popularização das IAs capazes de gerar código, é muito fácil cair no hábito de copiar soluções prontas sem compreender os conceitos envolvidos.

Meu desafio pessoal era responder à seguinte pergunta:

> **Como usar IA para aprender mais rápido sem deixar de aprender de verdade?**

Foi essa pergunta que guiou todo o desenvolvimento deste NotebookLM.

---

# Metodologia

O NotebookLM foi utilizado como um ambiente de pesquisa e organização de conhecimento.

Durante o projeto utilizei três abordagens principais:

## 1. Curadoria de fontes

Selecionei conteúdos de programadores experientes, documentações e materiais técnicos para construir uma base confiável antes de fazer perguntas à IA.

## 2. Questionamento por tópicos

Em vez de pedir soluções prontas, passei a fazer perguntas que me obrigavam a pensar antes da resposta, pois mesmo que no basico já soubesse da resposta, a complexidade da resposta me dava outros horizontes para pensar.

Exemplos:

* Quais são os riscos de usar IA para gerar código?
* Como um programador iniciante deve utilizar LLMs?
* Quando vale mais a pena consultar documentação do que perguntar para uma IA?

Esse método transformou a IA em uma **tutora**, e não em uma programadora.

## 3. Mapas mentais

A funcionalidade que mais utilizei foi a geração automática de **mapas mentais**.

Ela me ajudou a visualizar:

* quais assuntos estudar primeiro;
* como os conceitos se conectavam;
* quais tópicos eu ainda precisava revisar.

### Mapa mental gerado

> **Insira aqui o mapa mental exportado do NotebookLM**

![Mapa Mental](./assets/mapa-mental.png)

---

# Curadoria de Fontes

## Fonte 1

**Título:** *Do Zero à Pós-Produção em 1 Semana - Como usar IA em Projetos de Verdade | Bastidores do The M.Akita Chronicles*

**Autor:** *Fabio Akita | AkitaOnRails*

**Tipo de fonte:** *Postagem no blog*

**Por que escolhi esta fonte?**

> Escolhi essa fonte porque mostra na prática como a IA pode ser usada em projetos reais sem simplesmente deixar ela fazer tudo. Gostei principalmente da ideia de usar a IA como uma parceira para acelerar tarefas e resolver atritos, enquanto as decisões continuam sendo do programador. Isso se conecta diretamente com a proposta do meu NotebookLM de aprender a usar IA de forma mais eficiente na programação.

---

## Fonte 2

**Título:** *A Melhor Forma de Programar Com IA em 2026*

**Autor:** *Felipe Rocha | Full Stack Club*

**Tipo de fonte:** *Video no YouTube*

**Por que escolhi esta fonte?**

> Escolhi essa fonte porque ela aborda diretamente como a programação com IA está mudando em 2026. Ela me ajudou a pensar em como utilizar essas ferramentas de forma mais eficiente no desenvolvimento, sem depender delas para fazer todo o trabalho. Isso se encaixa na minha ideia de usar a IA para aumentar meu aproveitamento de tempo e continuar desenvolvendo meu próprio conhecimento.

---

## Fonte 3

**Título:** *Como eu uso IA pra programar em 2026*

**Autor:** *Augusto Galego*

**Tipo de fonte:** *Video no YouTube*

**Por que escolhi esta fonte?**

> Escolhi essa fonte porque mostra uma experiência prática de como a IA pode ser incorporada ao dia a dia de um programador. Ela me ajudou a enxergar melhor onde a IA pode realmente economizar tempo e facilitar tarefas durante o desenvolvimento. Isso reforça minha ideia de usar a IA como uma ferramenta de apoio, enquanto continuo responsável por entender e tomar as decisões.

---

# Engenharia de Prompts

Durante o desenvolvimento percebi que **a qualidade da resposta depende muito mais da pergunta do que da IA**.

## Prompt 1 — Exploração de conceitos

> *Atue como um programador experiente e meu mentor.

Com base exclusivamente nas fontes deste NotebookLM, ensine como programadores utilizam Inteligência Artificial no dia a dia para aumentar a produtividade e reduzir tarefas repetitivas.

Não quero apenas uma lista de ferramentas. Quero entender:
- quais problemas do desenvolvimento podem ser resolvidos com IA;
- em quais situações um programador costuma recorrer à IA;
- como ele formula os pedidos;
- quais tarefas devem continuar sob responsabilidade do programador;
- quais são os riscos de depender demais da IA.

Explique de forma prática, utilizando exemplos de situações reais de desenvolvimento. Sempre que possível, mostre como um programador pensaria antes, durante e depois de utilizar a IA.*

**Objetivo**

Entender um conceito antes de escrever código e me passar as informações como se fosse um Programador com anos de pratica e que os modos de usar a IA para facilitar seja mais integrado e simples de pegar.

**Resultado**

> Escreva aqui o que funcionou.

---

# Cicatrizes (O que não funcionou)

Uma das partes mais importantes do projeto foi entender **o que não deu certo**.

| Situação                      | O problema                      | Como resolvi                                       |
| ----------------------------- | ------------------------------- | -------------------------------------------------- |
| Prompt muito genérico         | A IA respondia superficialmente | Passei a contextualizar melhor as perguntas        |
| Pedir código completo         | Eu entendia menos a solução     | Comecei a pedir explicações antes da implementação |
| Muito conteúdo ao mesmo tempo | Dificuldade para revisar        | Utilizei mapas mentais para organizar os estudos   |

---

# Meu método de estudo com IA

Após testar diferentes abordagens, cheguei a um fluxo simples que pretendo continuar utilizando.

## Etapa 1 — Entender o problema

Antes de abrir a IA, tento definir claramente o que quero aprender.

## Etapa 2 — Pesquisar boas referências

Primeiro consulto fontes confiáveis e só depois começo a fazer perguntas.

## Etapa 3 — Conversar com a IA

Utilizo perguntas abertas para explorar possibilidades e compreender conceitos.

## Etapa 4 — Organizar o conhecimento

Transformo as respostas em mapas mentais e listas de estudo.

## Etapa 5 — Implementar sozinho

A IA deixa de tratar a situação de forma leviana e realmente me da maneiras de usar IA no dia a dia.

---

# Mini Guia de Estudo

## O que aprendi

* IA não substitui fundamentos de programação.
* Bons prompts nascem de boas perguntas.
* Documentação continua sendo uma das fontes mais importantes.
* Mapas mentais aceleram a revisão e ajudam na retenção do conteúdo.
* A produtividade vem da organização do conhecimento, não apenas da geração de código.

---

# Glossário

| Termo         | Significado                                                      |
| ------------- | ---------------------------------------------------------------- |
| LLM           | Modelo de linguagem capaz de compreender e gerar texto           |
| Prompt        | Instrução enviada para a IA                                      |
| Contexto      | Informações fornecidas para orientar a resposta                  |
| Hallucination | Quando a IA gera informações incorretas com aparência de verdade |
| Code Review   | Processo de revisar código para identificar melhorias e erros    |

---

# Prompts reutilizáveis

## Para aprender um conceito

```text
Explique este conceito como se eu fosse um estudante de programação.
Não escreva o código primeiro. Quero entender a lógica.
```

## Para revisar meu código

```text
Analise meu código e aponte possíveis problemas, mas não reescreva a solução.
Faça perguntas que me ajudem a encontrar o erro.
```

## Para organizar estudos

```text
Crie um mapa mental com os principais tópicos que preciso dominar sobre este assunto.
Organize do básico ao avançado.
```

---

# Conclusão

Este projeto mostrou que a IA gera mais valor quando atua como uma **ferramenta de aprendizagem e produtividade**, e não como uma substituta do programador.

Mais do que escrever código mais rápido, o objetivo passou a ser **aprender melhor, organizar conhecimento e reduzir o atrito durante os estudos**. O NotebookLM se tornou um ambiente para conectar fontes, estruturar ideias e transformar dúvidas em um plano claro de aprendizado.

---
