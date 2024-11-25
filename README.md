# TaskApp  

Uma aplicação React para gerenciamento de tarefas, permitindo organizar, criar e acompanhar atividades de forma eficiente.  

## 🚀 Tecnologias  

- **React** (v18.3.1)  
- **React Router DOM** (v6.28.0)  
- **Firebase** (v11.0.2)  
- Ferramentas de teste:  
  - **Testing Library**  
  - **Jest**  
- Scripts baseados no **React-Scripts**  

## 🛠️ Funcionalidades  

- Cadastro, edição e exclusão de tarefas.  
- Navegação entre páginas utilizando React Router.  
- Integração com Firebase para armazenamento e autenticação (se aplicável).  

## 📦 Instalação  

1. Clone este repositório:  
   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd taskapp
   ```

2. Instale as dependências:  
   ```bash
   npm install
   ```

## 💻 Uso  

Inicie o servidor de desenvolvimento:  
```bash
npm start
```  

Acesse a aplicação em [http://localhost:3000](http://localhost:3000).  

## ⚙️ Configuração do arquivo `.env`  

A aplicação utiliza um arquivo `.env` para armazenar variáveis de ambiente necessárias para sua execução. Certifique-se de criar este arquivo na raiz do projeto e configurar os seguintes valores:  

```env
REACT_APP_FIREBASE_APIKEY=          # Chave da API do Firebase
REACT_APP_FIREBASE_AUTHDOMAIN=      # Domínio de autenticação do Firebase
REACT_APP_FIREBASE_PROJECTID=       # ID do projeto Firebase
REACT_APP_FIREBASE_STORAGEBUCKET=   # Bucket de armazenamento do Firebase
REACT_APP_FIREBASE_MESSAGINGSENDERID= # ID do remetente de mensagens do Firebase
REACT_APP_FIREBASE_APPID=           # ID do aplicativo Firebase
REACT_APP_FIREBASE_MEASUREMENTID=   # ID de medição do Firebase Analytics
```

> **Nota**: Nunca compartilhe suas variáveis de ambiente publicamente. Essas informações são sensíveis e podem comprometer a segurança do projeto.  

## 🏗️ Build  

Para gerar a versão de produção:  
```bash
npm run build
```  

Os arquivos otimizados serão criados na pasta `build/`.  

## 🧪 Testes  

Execute os testes disponíveis:  
```bash
npm test
```  

## 🌐 Compatibilidade  

Compatível com os navegadores:  
- Chrome  
- Firefox  
- Safari  

## 📜 Licença  

Este projeto é privado. Consulte o autor para mais informações.