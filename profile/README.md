# 🏥 Alô Doctor

O **Alô Doctor** é uma aplicação web desenvolvida para revolucionar a comunicação entre pacientes e profissionais de saúde em ambientes hospitalares, promovendo maior eficiência, agilidade e qualidade no atendimento clínico.

## 🚀 Acesse a Aplicação (Live Demo)

O sistema já está em produção e você pode testá-lo agora mesmo.

🔗 **Link da Aplicação:** [https://alodoc.vercel.app](https://alodoc.vercel.app)

### 🔐 Credenciais de Teste

Para explorar as diferentes visões do sistema, utilize os acessos abaixo:

**Acesso Visão Paciente:**
* **E-mail:** `teste@alodoctor.com.br`
* **Senha:** `alodoctorpaciente`

**Acesso Visão Hospital (Profissional/Admin):**
* **Usuário:** `adm`
* **Senha:** `alodoctoradm`

## 📚 Documentação da API

Toda a estrutura de endpoints, regras de requisição, schemas e métodos de autenticação da nossa API está documentada e disponível para consulta pública.

🔗 **Acesse a Documentação (Apidog):** [https://api-alodoctor.apidog.io](https://api-alodoctor.apidog.io)

---

## ✨ Principais Funcionalidades

* **Sistema de Chamados:** A principal funcionalidade da plataforma. Permite a criação de chamados em tempo real pelo paciente, que são exibidos em um painel interativo para acompanhamento imediato pelos profissionais de saúde.
* **Controle de Leitos e Internação:** Mapeamento em tempo real identificando em qual leito cada paciente está alocado.
* **Controle de Acesso Inteligente:** Implementação de segurança baseada em tokens. O paciente só tem acesso ao sistema de chamados se estiver ativamente associado a um leito hospitalar.
* **Pesquisa de Satisfação:** Coleta de feedback automatizada realizada após a conclusão do atendimento para métricas de qualidade hospitalar.

## 🏗️ Estrutura do Projeto

O ecossistema é dividido em dois repositórios focados na separação de responsabilidades (Clean Architecture):

* 💻 **[Web Interface (Frontend)](https://github.com/alodoctor-app/web-alodoctor):** Interface intuitiva e responsiva desenvolvida em TypeScript.
* ⚙️ **[API REST (Backend)](https://github.com/alodoctor-app/api-alodoctor):** Motor de regras de negócio, autenticação e persistência de dados.
