# 📝 Todo List - JavaScript

![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)
![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg)
![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg)
![License](https://img.shields.io/badge/License-MIT-blue)

Uma aplicação de lista de tarefas moderna e responsiva, desenvolvida com JavaScript puro. Gerencie suas tarefas diárias com uma interface limpa e intuitiva.

## ✨ Funcionalidades

- ✅ **Adicionar novas tarefas**
- ✅ **Marcar/desmarcar como concluída** 
- ✅ **Excluir tarefas individualmente**
- 💾 **Persistência automática** (localStorage)
- 📱 **Design responsivo** (mobile-first)
- 🔄 **Contador em tempo real** de tarefas pendentes
- 🎯 **Feedback visual** imediato nas interações

## 🛠️ Stack Tecnológica

- **HTML5** - Estrutura semântica e acessível
- **CSS3** - Variáveis CSS, Flexbox e design responsivo
- **JavaScript ES6+** - Modules, Arrow Functions, Template Literals
- **LocalStorage API** - Persistência de dados no navegador

## 🚀 Instalação e Execução

### Pré-requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Git (opcional, para clonagem)

### Passos para execução local:

```bash
# 1. Clone o repositório
git clone https://github.com/MurilloSanttos/todo-list-js.git

# 2. Acesse o diretório
cd todo-list-js

# 3. Abra o projeto no navegador
# Opção 1: Abra o arquivo index.html diretamente
# Opção 2: Use um servidor local (recomendado)
python -m http.server 8000
# ou
npx serve .
```

## 📁 Estrutura de Pastas

```
todo-list-js/
├── index.html              # Página principal
├── src/
│   ├── css/
│   │   ├── reset.css      # Reset CSS consistente
│   │   ├── variables.css  # Variáveis e temas
│   │   └── main.css       # Estilos principais
│   └── js/
│       ├── modules/
│       │   ├── storage.js # Gerenciamento do localStorage
│       │   ├── tasks.js   # Lógica das tarefas
│       │   └── ui.js      # Manipulação da interface
│       └── app.js         # Inicialização da aplicação
├── assets/                # Recursos estáticos
└── README.md
```

## 🎯 Como Usar

1. **Adicionar tarefa**: Digite no campo de texto e pressione Enter ou clique no botão "+"
2. **Concluir tarefa**: Clique no círculo ao lado da tarefa
3. **Excluir tarefa**: Clique no ícone de lixeira
4. **As tarefas são salvas automaticamente** no seu navegador

## 🔧 Desenvolvimento

Este projeto segue boas práticas de desenvolvimento front-end:

- **Arquitetura modular** com separação de concerns
- **Event delegation** para performance
- **CSS methodologies** com BEM-inspired naming
- **Clean code** com funções puras e composição

## 🤝 Contribuindo

Contribuições são bem-vindas! Siga estes passos:

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Distribuído sob licença MIT. Veja `LICENSE` para mais informações.

## 👨‍💻 Autor

**Murillo Santos** 
- GitHub: [@MurilloSanttos](https://github.com/MurilloSanttos)
- Projeto: [Todo List JS](https://github.com/MurilloSanttos/todo-list-js)

---

**⭐️ Se este projeto te ajudou, considere dar uma estrela no repositório!**
