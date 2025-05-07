# 🖥️ Portfólio Técnico: Mapeando o Sistema Operacional

## 🔍 Visão Geral

O sistema operacional (SO) é o software responsável por intermediar a comunicação entre o hardware e o software. Seu papel é garantir que os recursos do sistema — como CPU, memória e dispositivos de E/S — sejam alocados eficientemente entre os processos ativos. Ele atua como um gerente multitarefa, oferecendo abstrações e serviços que tornam o uso do computador mais seguro, eficiente e organizado.

---

## 🧠 Gerenciamento de Memória

### ✅ Conceito

A memória é um recurso escasso e essencial. O SO gerencia quais processos ocupam quais áreas da memória, garantindo isolamento e segurança entre eles.

### 📌 Principais Técnicas

- **Paginação**: Divide a memória em blocos fixos (páginas). Cada processo recebe páginas, que são mapeadas para quadros físicos. Permite alocação não contígua e fácil substituição.
  
- **Segmentação**: Divide a memória com base em blocos lógicos (código, dados, pilha). Melhora a organização e permite proteção por segmento.

- **Substituição de Páginas**:
  - FIFO (First-In, First-Out)
  - LRU (Least Recently Used)
  - Clock

### 💡 Estudo de Caso

Um navegador com várias abas abertas pode ocupar muitos MB de RAM. O SO aloca páginas para cada aba, e se a memória acabar, as páginas menos usadas são movidas para o disco (swap).

---

## 📂 Sistemas de Arquivos

### ✅ Conceito

Responsável por organizar, armazenar, recuperar e proteger dados em dispositivos de armazenamento.

### 📌 Componentes

- **Estrutura de Diretórios**: Hierárquica (como uma árvore), com suporte a caminhos absolutos e relativos.
- **Implementações Populares**:
  - FAT32 (Windows, pendrives)
  - NTFS (Windows)
  - ext4 (Linux)
  - APFS (macOS)

### 💡 Exemplo Prático

```bash
# Em sistemas Linux:
df -h        # mostra uso do sistema de arquivos
ls -l        # exibe permissões e organização
