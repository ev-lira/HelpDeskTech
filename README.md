# 🚀 HelpDeskTech - Sistema de Gestão de Atendimentos

Este projeto foi desenvolvido em *Java* para a disciplina de Estrutura de Dados, com o objetivo de implementar e demonstrar o funcionamento prático das estruturas de dados fundamentais: *Fila, **Pilha, **Lista* e *Árvore Binária de Busca (ABB)*.

## 🛠️ Como Compilar e Executar o Programa

O projeto é composto por diversas classes Java (Arquivos .java).

## 🧠 Resumo da Lógica Implementada
O projeto utiliza um design orientado a objetos:

Classes Modelo: Chamado, Cliente, Servico definem os dados que serão armazenados.
Classes de Gerenciamento: GerenciadorChamados, GerenciadorOperacoes, GerenciadorClientes, e ArvoreServicos encapsulam a lógica específica de cada estrutura de dados.
Classe Principal: HelpDeskTech gerencia a interface do usuário (os menus) e atua como a cola, chamando os métodos apropriados dos gerenciadores em resposta às escolhas do usuário.

Principais Pontos de Lógica:

Pilha e Fila em Conjunto: Toda vez que um chamado é inserido (Fila) ou atendido (Fila), uma string correspondente é imediatamente empilhada (Pilha), criando o histórico de operações de forma automática.
Busca na Lista: A busca de clientes é feita por iteração (laço for) na ArrayList, comparando o ID ou parte do nome em cada elemento.
Busca na Árvore: A busca de serviços é feita de forma recursiva, aproveitando a característica da ABB: se o código procurado for menor que o nó atual, a busca continua à esquerda; se for maior, continua à direita.
Listagem Ordenada da Árvore: A listagem de serviços em ordem crescente é garantida pelo algoritmo de percurso In-Order (Esquerda -> Raiz -> Direita), que é o padrão para listar elementos de uma ABB em sua ordem natural.


### Requisitos

* *Java Development Kit (JDK):* Versão 8 ou superior.

### 1. Estrutura de Arquivos

Certifique-se de que todos os arquivos .java (incluindo HelpDeskTech.java, Chamado.java, Cliente.java, GerenciadorClientes.java, ArvoreServicos.java, etc.) estejam no *mesmo diretório* (pasta).

### 2. Compilação (Via Terminal/Prompt de Comando)

Navegue até o diretório onde os arquivos estão salvos e use o compilador Java (javac):

```bash
javac *.java
```

# Projeto de Estrutura de dados/ POO — 2025.2

Alunos:
### Erlon Vítor de Lira Mendes — 01649461
### Roselany Maria da Silva do Nascimento — 01625564
### Thiago Henrique Monteiro da Silva — 01650242

## Turma: 5NA — Análise e Desenvolvimento de Sistemas (Embarque Digital)
