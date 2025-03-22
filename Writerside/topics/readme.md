# 🏮 Sistema de Gestão Quilombo Pena Branca 🏮


![Logo.png](Logo.png)
#### ✨ Preservando tradições através da tecnologia ✨

---

## 📜 Sobre o Projeto

O Sistema de Gestão Quilombo Pena Branca é uma aplicação web completa desenvolvida para administrar e organizar as atividades da comunidade Quilombo Pena Branca. A plataforma oferece ferramentas completas para o gerenciamento de membros, cargos, obrigações religiosas e usuários do sistema, combinando uma API robusta com uma interface amigável.

## 🧩 Funcionalidades Principais

### 👥 Gerenciamento de Membros
- **📋 Cadastro completo** com dados pessoais, documentos e endereço
- **🔍 Busca avançada** por pseudônimo, cargo e status
- **📱 Visualização detalhada** do perfil do membro
- **⭐ Indicação de rodante** para participantes de rituais específicos
- **👨‍👩‍👧‍👦 Registro de filiação** biológica e espiritual

### 🔐 Controle de Usuários
- **🛡️ Níveis de permissão** para acesso ao sistema
- **🔗 Vinculação** de usuários a membros existentes
- **🔑 Gerenciamento de senhas** com recuperação via administrador
- **📊 Listagem e filtragem** de operadores do sistema

### 👑 Administração de Cargos
- **✏️ Cadastro e edição** de cargos com descrições
- **🏅 Atribuição** de cargos aos membros
- **📇 Consulta rápida** por nome de cargo

### 📝 Registro de Obrigações
- **📆 Controle de obrigações religiosas** dos membros
- **📚 Histórico de atividades** por membro
- **📒 Formulários dedicados** para registro de informações específicas

### 📍 Gestão de Endereços
- **🔍 Integração com CEP** para facilitar cadastro de endereços

### 📋 Registros de Log
- **📊 Acompanhamento** de atividades realizadas no sistema

## 🚀 Tecnologias Utilizadas

### 🌐 Frontend
- **Angular 19.1.0** como framework principal
- **Angular Forms** para validação de formulários
- **FontAwesome** para ícones
- **ngx-mask** para formatação de campos
- **date-fns** para manipulação de datas

### ⚙️ Backend
- **☕ Java 21**
- **🍃 Spring Boot 3.4.1**
- **🔒 Spring Security com JWT**
- **📊 Spring Data JPA**
- **🗄️ MySQL**
- **📝 Lombok**
- **📚 OpenAPI/Swagger**

### 🔒 Segurança
- **JWT** para autenticação
- **Controle de acesso** baseado em permissões
- **Proteção de rotas** para áreas restritas

### 🐳 DevOps
- **Docker Compose** para ambiente containerizado

## 🧙‍♂️ Menu Lateral

O sistema conta com um menu lateral intuitivo para navegação rápida:

- 👤 Gestão de Membros
- ➕ Adicionar Membros
- 📜 Registrar Obrigações
- ⚙️ Gerenciar Operadores
- 👑 Administrar Cargos

## 🔰 Níveis de Acesso
- **🔱 Administrador**: Acesso completo ao sistema
- **🔆 Operador**: Acesso limitado conforme permissões concedidas

## 📋 Pré-requisitos

### Backend
- Java 21
- Docker e Docker Compose (opcional para ambiente containerizado)
- Maven

### Frontend
- Node.js (versão recomendada: 18.x ou superior)
- NPM (geralmente instalado com o Node.js)
- Angular CLI 19.x

## 🛠️ Instalação e Configuração

### Backend

1. **Clone o repositório**
   ```bash
   git clone https://github.com/senzalla/quilombo-api.git
   cd quilombo-api
   ```

2. **Usando Docker (recomendado)**
   ```bash
   docker-compose up -d
   ```

3. **Ou configure manualmente**
    - Configure as variáveis de ambiente no arquivo `.env`
    - Execute o aplicativo:
   ```bash
   ./mvnw spring-boot:run
   ```

### Frontend

1. **Clone o repositório**
   ```bash
   git clone https://github.com/seu-usuario/quilombo-app.git
   cd quilombo-app
   ```

2. **Instale as dependências**
   ```bash
   npm install
   ```

3. **Inicie o servidor de desenvolvimento**
   ```bash
   npm start
   ```

4. **Acesse a aplicação**
    - Abra o navegador em `http://localhost:4200`

## 📚 Documentação da API

A documentação da API está disponível através do Swagger UI após iniciar a aplicação:

```
http://localhost:8080/swagger-ui.html
```

## 🌐 Endpoints Principais

- **Autenticação**: `/api/v1/auth`
- **Usuários**: `/api/v1/users`
- **Membros**: `/api/v1/members`
- **Obrigações**: `/api/v1/obligations`
- **Posições**: `/api/v1/positions`
- **CEP**: `/api/v1/zipcode`

## 🧪 Desenvolvimento

### ⚡ Comandos Úteis Frontend
- **Iniciar servidor**: `npm start`
- **Construir para produção**: `npm run build`
- **Executar testes**: `npm test`
- **Criar novo componente**: `ng generate component caminho/componente`

## 🌟 Sobre o Desenvolvedor

### Senzalla Technology
![Senzalla_Tech.webp](Senzalla_Tech.webp)


A **Senzalla Technology** é uma empresa especializada no desenvolvimento de soluções tecnológicas. Com foco em comunidades tradicionais, a empresa combina expertise tecnológica com profundo respeito pelos valores e práticas culturais.

#### Missão
Desenvolver tecnologias que preservem e fortaleçam a identidade cultural de comunidades tradicionais, promovendo inclusão digital e valorização do patrimônio imaterial.

#### Projetos
- Sistema de Gestão Quilombo Pena Branca
- [Sistema de Controle Financeiro Metakyasshu](https://bomsalvez.github.io/metakyasshu-docs/metakyasshu.html)

#### Contato
- [📧 Email](mailto:bomsalvez@gmail.com) | [🌐 Website](https://senzalla.dev) | [🐱 GitHub](https://github.com/senzalla) | [📱 Contato](mailto:contato@senzalla.dev) | [🔗 LinkedIn](https://www.linkedin.com/in/bomsalvez-freitas/)

## 📋 Suporte e Contribuição

### 🐛 Reportando Problemas
Para relatar bugs ou sugerir melhorias, abra uma issue no repositório do projeto detalhando:
- Passos para reproduzir o problema
- Comportamento esperado vs. observado
- Capturas de tela (se aplicável)

### 🤝 Contribuindo com o Projeto
1. Faça um fork do repositório
2. Crie uma branch para sua feature
3. Faça commit das alterações
4. Envie para o GitHub
5. Abra um Pull Request

---

<div align="center">
  <h3>🌙 Quilombo Pena Branca 🌙</h3>
  <p>Honrando nossas raízes, construindo nosso futuro</p>
</div>