# TempleOS: Estudo e Análise de um Sistema Operacional

## Sobre o Projeto

Este repositório contém o material desenvolvido para a disciplina de **Sistemas Operacionais** do curso de **Ciência da Computação** da **UNINASSAU**.

O trabalho tem como objetivo apresentar um estudo sobre o sistema operacional **TempleOS**, abordando sua história, arquitetura, kernel, linguagem de programação, instalação em máquina virtual e demonstrações práticas realizadas durante sua utilização.

---

## Integrantes

* Natan Gabriel de Souza Miranda
* João Victor Soares de Lima
* Kamilly Stephany Saraiva Santos
* Samuel Alexandre Correia da Silva
* Crytian Pinheiro Aguiar
* Roberto Matheus Nunes dos Santos
* Paulo Israel Pinho Filho

**Professor:** Anderlan

**Disciplina:** Sistemas Operacionais

---

## O que é o TempleOS?

TempleOS é um sistema operacional de 64 bits criado por Terry A. Davis.

O projeto se destaca por ter sido desenvolvido praticamente por uma única pessoa e por incluir seu próprio:

-  Kernel
- Sistema de arquivos
- Interface gráfica
- Compilador
- Linguagem de programação (HolyC)

Seu principal objetivo é educacional, permitindo que estudantes e entusiastas compreendam conceitos fundamentais de sistemas operacionais de forma simplificada.

---

## Kernel

O TempleOS utiliza um **kernel monolítico**, modelo em que os principais serviços do sistema executam diretamente dentro do núcleo do sistema operacional.

### Principais características

- Arquitetura monolítica
- Execução em 64 bits
- Sistema de arquivos próprio
- Gerenciamento de memória simplificado
- Interface gráfica integrada
- Baixa complexidade estrutural

---

## Linguagem HolyC

HolyC é a linguagem de programação oficial do TempleOS.

Baseada em C e C++, ela foi criada para integrar-se completamente ao sistema operacional.

Exemplo simples:

```c
U0 Main()
{
    "Olá Mundo\n";
}
```

Uma das principais características do TempleOS é possuir um compilador integrado, permitindo criar e executar programas diretamente dentro do sistema.

---

## Instalação

A instalação foi realizada utilizando o VirtualBox.

### Etapas realizadas

1. Download da ISO do TempleOS;
2. Criação da máquina virtual;
3. Configuração de memória RAM e disco virtual;
4. Inicialização pela ISO;
5. Instalação do sistema operacional;
6. Reinicialização da máquina virtual.

### Configuração utilizada

RAM - 512 MB
CPU - 1 Núcleo
Disco Virtual - 2 GB
Virtualizador - VirtualBox

---

## Demonstrações Realizadas

Durante os testes foram explorados diversos recursos do sistema:

* Navegação pela interface gráfica;
* Sistema de ajuda integrado;
* Execução de jogos;
* Visualização de código-fonte;
* Execução de programas HolyC;
* Exploração dos menus e demos do sistema.

## Comandos e Atalhos Básicos

O TempleOS possui diversos atalhos de teclado que ajudam na navegação e na execução rápida de tarefas. Alguns exemplos básicos são:

* `F1` – abre o sistema de ajuda do TempleOS.
* `SHIFT+F7` – exibe uma passagem bíblica ou chama a Bíblia integrada ao sistema.
* `ESC` – volta ao menu ou fecha janelas abertas.
* `F7` – abre menus de demonstração, exemplos ou edições de código dependendo do contexto.
* `CTRL+S` – geralmente salva o arquivo ou o documento em edição.

Esses atalhos fazem parte da interface simples e direta do TempleOS e podem ser úteis durante a exploração do sistema.

---

## Tecnologias Utilizadas

* TempleOS
* VirtualBox
* GitHub
* Overleaf
* LaTeX

---

## Referências

* TempleOS Official Website
* TempleOS Documentation
* Andrew S. Tanenbaum — Sistemas Operacionais Modernos

---

## Repositório Acadêmico

Projeto desenvolvido exclusivamente para fins acadêmicos na disciplina de Sistemas Operacionais da UNINASSAU.
