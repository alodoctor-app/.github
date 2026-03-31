# 🏥 Alô Doctor

> **Ecossistema tecnológico para gestão de saúde e modernização do atendimento médico.**

O **Alô Doctor** é uma solução completa desenvolvida para transformar a comunicação entre pacientes e profissionais de saúde. O foco é eliminar gargalos em ambientes hospitalares, trazendo agilidade aos chamados clínicos e oferecendo aos gestores dados precisos sobre a qualidade do atendimento em tempo real.

---

## 🚀 Links Úteis

* 🔗 **Live Demo:** [alodoc.vercel.app](https://alodoc.vercel.app)
* 📚 **Documentação da API (Apidog):** [api-alodoctor.apidog.io](https://api-alodoctor.apidog.io)

---

## ✨ Funcionalidades Principais

* **🛎️ Sistema de Chamados em Tempo Real:** Pacientes podem solicitar assistência imediata através da interface web, com atualização instantânea para a enfermagem.
* **📊 Dashboard de Monitorização:** Painel interativo para profissionais de saúde gerirem chamados ativos e prioridades.
* **🛏️ Gestão de Leitos:** Controlo em tempo real da ocupação hospitalar, associando pacientes a leitos específicos de forma dinâmica.
* **🔐 Segurança e Acesso:** Autenticação baseada em tokens (JWT). O acesso é validado para garantir que apenas pacientes com internação ativa utilizem o sistema.
* **⭐ Pesquisa de Satisfação:** Coleta automatizada de feedback após cada atendimento para gerar métricas de performance (NPS).

---

## 🛠️ Tecnologias Utilizadas

O ecossistema utiliza uma stack moderna focada em performance, tipagem forte e escalabilidade:

* **Frontend:** [React.js](https://reactjs.org/) / [Next.js](https://nextjs.org/) com **TypeScript**.
* **Backend:** [Node.js](https://nodejs.org/) com **TypeScript**.
* **Estilização:** [Tailwind CSS](https://tailwindcss.com/) para uma interface responsiva e moderna.
* **Arquitetura:** Princípios de **Clean Architecture** e **SOLID** para garantir fácil manutenção.
* **Deploy/Hospedagem:** Vercel e serviços Cloud.

---

## 🏗️ Estrutura do Projeto

O ecossistema está dividido em dois repositórios focados na separação de responsabilidades:

1.  **[API Alô Doctor](https://github.com/alodoctor-app/api-alodoctor):** O motor do sistema. Gere regras de negócio, persistência de dados e autenticação.
2.  **[Web Alô Doctor](https://github.com/alodoctor-app/web-alodoctor):** A interface do utilizador, com fluxos distintos para Pacientes e Administradores Hospitalares.

---

## 🚀 Como Executar Localmente

### Pré-requisitos
* Node.js (v18+)
* NPM ou Yarn

### Instalação

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/alodoctor-app/web-alodoctor.git
    ```
2.  **Instale as dependências:**
    ```bash
    npm install
    ```
3.  **Configuração:**
    Crie um arquivo `.env` na raiz com base no `.env.example` fornecido nos repositórios.
4.  **Inicie o ambiente de desenvolvimento:**
    ```bash
    npm run dev
    ```

---

## 🔐 Credenciais de Teste (Demo)

Podes explorar as diferentes visões do sistema utilizando as credenciais abaixo:

| Perfil | Usuário/E-mail | Senha |
| :--- | :--- | :--- |
| **Paciente** | `teste@alodoctor.com.br` | `alodoctorpaciente` |
| **Hospital/Admin** | `adm` | `alodoctoradm` |

---

## 📩 Contato

Desenvolvido por **Victor Hugo Gutierrez**.

* **LinkedIn:** [linkedin.com/in/victorhugogutierrez](https://www.linkedin.com/in/victorhugogutierrez)
* **E-mail:** [hugovictorgutierrez@gmail.com](mailto:hugovictorgutierrez@gmail.com)

---
*Este projeto foi idealizado para modernizar fluxos de atendimento em instituições de saúde.*
