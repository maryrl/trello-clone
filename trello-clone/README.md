# 📋 Trello Clone - README

![Trello Clone Screenshot](./public/screenshot.png) <!-- Adicione uma screenshot depois -->

## ✨ Visão Geral

Um clone do Trello construído com tecnologias modernas para gerenciamento de projetos no estilo Kanban. Esta aplicação oferece quadros, listas e cartões totalmente interativos com persistência local.

## 🚀 Tecnologias Utilizadas

- **Frontend**:
  - ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
  - ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
  - ![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
  - ![Material UI](https://mui.com/material-ui/pt/)

- **Funcionalidades**:
  - ![DnD Library](https://img.shields.io/badge/Drag&Drop-FF6B6B?style=for-the-badge)
  - ![Local Storage](https://img.shields.io/badge/Persistência_Local-4ECDC4?style=for-the-badge)

## 🌟 Funcionalidades Principais

✅ **Quadros Kanban completos**  
✅ **Drag-and-drop intuitivo** de listas e cartões  
✅ **Modo claro/escuro**  
✅ **Sistema de tags coloridas** para organização  
✅ **Persistência automática** no localStorage  
✅ **Responsividade** para todos os dispositivos  
✅ **Animações fluidas** com Framer Motion  

## 🛠️ Como Executar Localmente

### Pré-requisitos
- Node.js (v18+)
- npm ou yarn

### Passos para Instalação

1. **Clone o repositório**
   ```bash
   git clone https://github.com/seu-usuario/trello-clone.git
   cd trello-clone
   ```

2. **Instale as dependências**
   ```bash
   npm install
   # ou
   yarn install
   ```

3. **Execute o servidor de desenvolvimento**
   ```bash
   npm run dev
   # ou
   yarn dev
   ```

4. **Acesse no navegador**
   ```
   http://localhost:3000
   ```

## 📂 Estrutura do Projeto

```
trello-clone/
├── src/
│   ├── components/      # Componentes React
│   ├── context/         # Contextos globais (tema, etc.)
│   ├── hooks/           # Custom hooks
│   ├── types/           # Tipos TypeScript
│   ├── styles/          # Estilos globais
│   └── pages/           # Rotas da aplicação
├── public/              # Assets estáticos
└── package.json
```

## 🎨 Customização

Você pode personalizar:

1. **Cores do tema**: Edite `tailwind.config.js`
2. **Tags padrão**: Modifique em `src/types/index.ts`
3. **Dados iniciais**: Ajuste em `src/hooks/useLocalStorage.ts`

## 🤝 Contribuição

Contribuições são bem-vindas! Siga estes passos:

1. Faça um fork do projeto
2. Crie uma branch (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

---

Feito com ❤️ por [Seu Nome] | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/seu-perfil/)