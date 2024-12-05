# Task Manager

Um gerenciador de tarefas simples criado em React para fins de aprendizado. Este projeto demonstra conceitos fundamentais do React, como criação de componentes, uso de **props** e renderização dinâmica de listas.

---

## 🚀 Funcionalidades

- **Exibição Dinâmica:** Renderiza uma lista de tarefas com base em dados fornecidos.
- **Componentização:** Uso de componentes reutilizáveis.
- **Validação de Propriedades:** Uso do **PropTypes** para garantir a integridade dos dados recebidos pelos componentes.

---

## 🛠️ Tecnologias Utilizadas

- **React**: Biblioteca para criação de interfaces de usuário.
- **PropTypes**: Biblioteca para validação de propriedades em componentes React.
- **CSS**: Para estilização (opcional, podendo ser expandido com Tailwind ou outros frameworks).

---

## 📂 Estrutura do Projeto

```bash
task-manager/
├── src/
│   ├── components/
│   │   ├── Header.js          # Cabeçalho do projeto
│   │   ├── TaskContainer.jsx  # Componente que gerencia a lista de tarefas
│   │   └── Task.jsx           # Componente que exibe uma tarefa individual
│   ├── App.js                 # Componente principal que organiza a aplicação
│   └── index.js               # Ponto de entrada do React
├── public/
│   └── index.html             # Arquivo HTML base
├── package.json               # Dependências e scripts do projeto
└── README.md                  # Documentação do projeto
