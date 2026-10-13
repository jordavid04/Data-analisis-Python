# Electoral Data Analysis System | Análise de Dados Eleitorais 📊🗳️

[![Python Version](https://img.shields.io/badge/Python-3.x-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![GUI](https://img.shields.io/badge/GUI-Tkinter-brightgreen?style=flat)](#overview)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](#license)

> **Language switch / Idiomas:** [English](#english) | [Português](#português)

---

<a name="english"></a>
## 🇬🇧 English

A desktop application featuring a graphical user interface (GUI) built in Python for parsing, exploring, and analyzing election datasets formatted in CSV. Developed as the final capstone project for **Programming II (PG II)**.

### 👤 Author Information
* **Developer:** Jorge David Bolognesi
* **Student ID / Matrícula:** 2024001052
* **Course / Turma:** 2

---

### ✨ Key Features
* **Desktop GUI (`Tkinter`):** Clean and intuitive graphical environment that abstracts away command-line interaction.
* **Dynamic File Selector:** Built-in file dialog to easily locate and load `.csv` election records directly from the filesystem.
* **Modular Function Execution:** Checkbox-driven architecture allowing users to trigger isolated or batch analyses (`Function 1` through `Function 6`).
* **Batch Controls:** One-click shortcuts to select or deselect all analytical queries.
* **Optimized CSV Ingestion:** Ingestion logic prepared for delimited records (`;` delimiter with `latin-1` encoding, standard for open electoral data platforms).

---

### 🛠️ Tech Stack & Requirements
* **Language:** Python 3.8+
* **Libraries:**
  * `tkinter` (Standard GUI toolkit)
  * `csv` (Built-in data reader/writer)

> *Note: No external third-party packages are required; all modules are included in the Python Standard Library.*

---

### 🚀 Getting Started

#### 1. Clone the repository
```bash
git clone https://github.com/your-username/analise-dados-eleitorais.git
cd analise-dados-eleitorais
```

#### 2. Run the application
```bash
python "Análise de Dados Eleitorais.py"
```

---

### 🖥️ How It Works
1. **Browse File:** Click **"Procurar"** to select your target CSV dataset.
2. **Configure Analysis:** Choose one or multiple tasks (`Função 1` to `Função 6`), or use **"Marcar todos"** to execute all.
3. **Execute:** Click **"Realizar"** to start the data parsing and view reports/results.

---

### 📂 Repository Structure
```text
├── Análise de Dados Eleitorais.py   # Main entry point with Tkinter GUI logic
├── dados.csv                       # Sample dataset / input data file
└── README.md                       # Documentation
```

---

<a name="português"></a>
## 🇧🇷 Português

Aplicação desktop com interface gráfica (GUI) desenvolvida em Python para carregamento, processamento e análise de bases de dados eleitorais em formato CSV. Projeto desenvolvido como Trabalho Final da disciplina **Programação II (PG II)**.

### 👤 Informações do Autor
* **Autor:** Jorge David Bolognesi
* **Matrícula:** 2024001052
* **Turma:** 2

---

### ✨ Funcionalidades
* **Interface Gráfica (`Tkinter`):** Ambiente intuitivo e de fácil utilização.
* **Carregamento Dinâmico de Arquivos:** Seletor nativo para importar arquivos `.csv` do sistema de arquivos.
* **Execução Modular:** Controle individual ou em lote das análises via caixas de seleção (`Função 1` a `Função 6`).
* **Ações Rápidas:** Botões para selecionar ou desselecionar todas as opções com um clique.
* **Processamento de CSV:** Estrutura pronta para lidar com arquivos delimitados por `;` e codificação `latin-1`.

---

### 🚀 Como Executar

```bash
# Clonar o repositório
git clone https://github.com/seu-usuario/analise-dados-eleitorais.git
cd analise-dados-eleitorais

# Executar a aplicação
python "Análise de Dados Eleitorais.py"
```

---

<a name="license"></a>
## 📄 License
This project was developed for academic and portfolio demonstration purposes. Distributed under the MIT License.