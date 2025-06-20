# 📋 Trello Clone - README

![Trello Clone Screenshot](./public/screenshot.png) <!-- Adicione uma screenshot depois -->

## ✨ Visão Geral

Um clone do Trello construído com as mais modernas tecnologias frontend para gerenciamento de projetos no estilo Kanban. Esta aplicação oferece quadros, listas e cartões totalmente interativos com persistência local.

## 🚀 Tecnologias Utilizadas

- **Frontend**:
  - ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
  - ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
  - ![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
  - ![Material UI](https://img.shields.io/badge/Material_UI-0081CB?style=for-the-badge&logo=mui&logoColor=white)

- **Funcionalidades**:
  - ![DnD Library](https://img.shields.io/badge/Drag&Drop-FF6B6B?style=for-the-badge)
  - ![Local Storage](https://img.shields.io/badge/Persistência_Local-4ECDC4?style=for-the-badge)

## 🌟 Funcionalidades Principais

✅ **Quadros Kanban completos** com Material UI  
✅ **Sistema de arrastar e soltar** intuitivo  
✅ **Design responsivo** para todos dispositivos  
✅ **Temas personalizáveis** (claro/escuro)  
✅ **Componentes estilizados** com Material UI  
✅ **Persistência automática** no localStorage  
✅ **Tipagem forte** com TypeScript  

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
│   ├── components/      # Componentes React com Material UI
│   ├── context/         # Contextos globais (tema, etc.)
│   ├── hooks/           # Custom hooks
│   ├── types/           # Tipos TypeScript
│   ├── styles/          # Estilos globais e temas
│   └── pages/           # Rotas da aplicação
├── public/              # Assets estáticos
└── package.json
```

## 🎨 Customização

Você pode personalizar:

1. **Tema Material UI**: Edite `src/styles/theme.ts`
2. **Componentes**: Modifique em `src/components/`
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

Feito com ❤️ por [Maria Rodrigues] | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maria-das-gra%C3%A7as-rodrigues-luciano-239b09148/)