# 🃏 Super Trunfo — Países em C

Projeto desenvolvido em **Linguagem C** como atividade prática de programação, utilizando o conceito do jogo **Super Trunfo** para cadastrar, calcular e comparar informações de cidades.

O objetivo do projeto é aplicar fundamentos importantes da linguagem C por meio de um programa executado no terminal.

---

## 📌 Sobre o projeto

O programa permite cadastrar informações de duas cartas representando cidades e realizar cálculos e comparações entre seus atributos.

Cada carta possui informações como:

- Estado;
- Código da carta;
- Nome da cidade;
- População;
- Área;
- PIB;
- Quantidade de pontos turísticos.

Além dos dados informados pelo usuário, o programa calcula automaticamente outros atributos importantes.

---

## ⚙️ Funcionalidades

O projeto permite:

- cadastrar duas cartas;
- receber os dados das cidades pelo terminal;
- calcular a densidade populacional;
- calcular o PIB per capita;
- calcular o chamado **Super Poder** da carta;
- comparar diferentes atributos das duas cartas;
- informar qual carta venceu cada comparação;
- permitir ao usuário selecionar atributos para realizar uma comparação.

---

## 🧠 Conceitos praticados

Durante o desenvolvimento deste projeto foram utilizados conceitos fundamentais da Linguagem C, como:

- declaração de variáveis;
- tipos de dados;
- entrada de dados com `scanf`;
- saída de dados com `printf`;
- operadores aritméticos;
- operadores relacionais;
- estruturas condicionais;
- cálculos matemáticos;
- comparação de valores;
- manipulação de strings;
- organização da lógica de um programa.

---

## 📊 Dados utilizados nas cartas

Cada carta possui os seguintes atributos:

| Atributo | Descrição |
|---|---|
| Estado | UF informada pelo usuário |
| Código | Identificação da carta |
| Cidade | Nome da cidade |
| População | Número de habitantes |
| Área | Área territorial em km² |
| PIB | Produto Interno Bruto da cidade |
| Pontos turísticos | Quantidade de pontos turísticos |
| Densidade populacional | População dividida pela área |
| PIB per capita | PIB dividido pela população |
| Super Poder | Valor calculado utilizando os atributos da carta |

---

## 🎮 Como funciona

Ao executar o programa, o usuário informa os dados da **Carta 1** e da **Carta 2**.

Exemplo:

```text
Carta 1

Digite a UF do Estado:
GO

Digite o Codigo da Carta:
A01

Digite o Nome da Cidade:
Goiania

Digite o numero de habitantes:
1437000
```

Após o cadastro, o programa realiza os cálculos necessários e apresenta as informações das cartas.

Em seguida, os atributos podem ser comparados para determinar qual carta apresenta o melhor resultado em cada categoria.

---

## ⚔️ Comparação das cartas

O programa realiza comparações utilizando atributos como:

- População;
- Área;
- PIB;
- Pontos turísticos;
- Densidade populacional;
- PIB per capita;
- Super Poder.

Na maioria dos atributos, vence a carta que possuir o **maior valor**.

Na densidade populacional, a lógica de comparação considera a regra específica utilizada no projeto.

---

## 🧮 Cálculos realizados

### Densidade Populacional

A densidade populacional é calculada utilizando:

```text
Densidade Populacional = População / Área
```

---

### PIB per Capita

O PIB per capita é calculado dividindo o PIB pela população:

```text
PIB per Capita = PIB / População
```

---

### Super Poder

O projeto também calcula um atributo chamado **Super Poder**, utilizando diferentes informações da carta para gerar um valor utilizado nas comparações.

---

## ▶️ Como executar

Para executar o projeto é necessário possuir um compilador C, como o **GCC**.

### 1. Clone o repositório

```bash
git clone https://github.com/WillianSaraiva/cadastro-cartas-williansg07.git
```

### 2. Entre na pasta do projeto

```bash
cd cadastro-cartas-williansg07
```

### 3. Compile o arquivo

```bash
gcc CartasSuperTrunfo.c -o CartasSuperTrunfo
```

### 4. Execute

No Windows:

```bash
CartasSuperTrunfo.exe
```

No Linux/macOS:

```bash
./CartasSuperTrunfo
```

---

## 🛠️ Tecnologia utilizada

![C](https://img.shields.io/badge/C-Language-A8B9CC?style=for-the-badge&logo=c&logoColor=black)

---

## 🎓 Contexto acadêmico

Este projeto foi desenvolvido como parte dos meus estudos em programação durante o curso de **Análise e Desenvolvimento de Sistemas**.

O objetivo principal é colocar em prática os fundamentos estudados e acompanhar minha evolução no desenvolvimento de software.

---

## 🚀 Próximos aprendizados

Conforme avanço nos estudos, pretendo continuar desenvolvendo projetos que permitam praticar:

- funções;
- estruturas;
- vetores;
- manipulação de arquivos;
- modularização de código;
- estruturas de dados;
- organização de projetos maiores.

---

## 👨‍💻 Autor

**Willian Saraiva**

Estudante de Análise e Desenvolvimento de Sistemas.

[![GitHub](https://img.shields.io/badge/GitHub-WillianSaraiva-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/WillianSaraiva)
