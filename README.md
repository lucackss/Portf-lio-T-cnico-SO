# 🖥️ Portfólio Técnico: Mapeando o Sistema Operacional

**Nome:** Seu Nome  
**Data:** 07/05/2025

---

## 🔍 Visão Geral: O Papel dos Sistemas Operacionais

O **sistema operacional (SO)** é o software responsável por gerenciar os recursos do hardware de um computador e oferecer uma interface entre o usuário e a máquina. Ele controla a execução de programas, organiza o armazenamento de dados, e coordena a comunicação com dispositivos de entrada e saída.

Exemplos: **Linux, Windows, macOS, Android.**

---

## 🧠 Gerenciamento de Memória

O gerenciamento de memória garante que os processos tenham acesso seguro e eficiente à memória RAM.

### Principais Conceitos:

- **Paginação:** Divide a memória em páginas (processos) e quadros (memória física). Permite alocação não contígua e evita fragmentação externa.
- **Segmentação:** Organiza a memória em segmentos lógicos (como código, pilha, dados), o que facilita o compartilhamento e a proteção.
- **Substituição de Páginas:** Quando a memória está cheia, o sistema escolhe uma página para remover com algoritmos como:
  - **FIFO (First-In, First-Out)**
  - **LRU (Least Recently Used)**
  - **Ótimo (teórico)**

---

## 📂 Sistemas de Arquivos

Os sistemas de arquivos organizam, armazenam e gerenciam os dados em dispositivos de armazenamento como HDDs e SSDs.

### Estrutura de Diretórios:

- Organização hierárquica (em árvore)
- Pastas e subpastas para agrupar arquivos
- Exemplo: `/home/aluno/documentos/trabalho.txt`

### Implementações Comuns:

- **FAT32** – Usado em pendrives e sistemas antigos
- **NTFS** – Padrão no Windows
- **EXT4** – Comum em sistemas Linux

### Operações:

- Criar, ler, escrever, mover, excluir arquivos
- Gerenciar permissões e metadados

---

## ⌨️ Entrada/Saída (E/S)

O sistema de E/S lida com a comunicação entre o computador e dispositivos externos.

### Camadas de E/S:

1. **Hardware** – dispositivos físicos (teclado, impressora, HD, etc.)
2. **Drivers** – programas que traduzem comandos do SO para o dispositivo
3. **Chamadas de sistema** – interface entre aplicativos e o SO
4. **Bibliotecas de alto nível** – como `stdio.h` (C) ou `java.io`

### Tipos de Dispositivos:

- **Entrada:** Teclado, mouse
- **Saída:** Monitor, impressora
- **Entrada/Saída:** Disco rígido, pendrives

### Clientes Magros (Thin Clients):

Dispositivos que dependem de servidores remotos para processamento, usados em empresas para reduzir custos e centralizar a administração.

---

## 🧠 Reflexão Final

A elaboração deste portfólio me permitiu consolidar e revisar os conceitos fundamentais de sistemas operacionais. Compreendi como cada módulo atua em conjunto para garantir o funcionamento eficaz de um sistema computacional.

Se eu pudesse aprimorar o projeto, incluiria animações ou simulações interativas para explicar melhor o funcionamento interno dos processos.

No mercado de trabalho, esse conhecimento é essencial para áreas como **infraestrutura, cibersegurança, computação em nuvem e desenvolvimento de sistemas embarcados**.

---

## 📎 Referências

- Tanenbaum, A. S. – *Sistemas Operacionais Modernos* (4ª edição)  
- Documentação oficial do Linux  
- Cursos e materiais de sistemas operacionais (Coursera, YouTube, etc.)

---

