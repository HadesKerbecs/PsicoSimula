# 🧠 PsicoSimula

Plataforma web educacional desenvolvida como Trabalho de Conclusão de Curso (TCC) em Engenharia de Software, utilizando Inteligência Artificial Generativa para criação de casos clínicos hipotéticos voltados ao ensino da psicopatologia.

O sistema permite que estudantes e profissionais da área da saúde mental gerem cenários clínicos personalizados através de parâmetros configuráveis, proporcionando uma experiência de aprendizagem interativa, dinâmica e adaptável.

---

## 🎯 Problema Resolvido

O estudo da psicopatologia frequentemente depende de livros, exemplos estáticos e discussões teóricas.

O PsicoSimula foi desenvolvido para permitir a geração dinâmica de casos clínicos simulados, possibilitando que cada usuário explore diferentes cenários e níveis de complexidade sem depender de casos previamente cadastrados.

A solução utiliza Inteligência Artificial Generativa para criar situações clínicas inéditas, promovendo maior engajamento e estímulo ao raciocínio clínico.

---

## 🚀 Principais Funcionalidades

### 🤖 Geração de Casos Clínicos com IA

* Integração com OpenAI API
* Criação dinâmica de casos clínicos hipotéticos
* Geração contextualizada de conteúdo
* Respostas personalizadas em tempo real

### ⚙️ Personalização dos Cenários

O usuário pode configurar parâmetros como:

* Idade
* Histórico médico
* Contexto social
* Complexidade do caso
* Características clínicas específicas

### 💬 Interação Dinâmica

* Interface conversacional
* Fluxo contínuo de interação
* Geração de conteúdo em tempo real
* Experiência semelhante a um ambiente de simulação

### 🗃️ Histórico de Interações

* Armazenamento das conversas realizadas
* Persistência de dados
* Consulta de simulações anteriores

### 📱 Interface Responsiva

* Compatível com desktop e dispositivos móveis
* Navegação simplificada
* Experiência focada em usabilidade

---

## 🧠 Desafios Técnicos Resolvidos

Durante o desenvolvimento foram implementadas soluções para:

* Integração entre Django e OpenAI API
* Construção de prompts para geração consistente dos casos clínicos
* Persistência do histórico das interações
* Gerenciamento de sessões de usuários
* Atualização dinâmica da interface durante a geração das respostas
* Tratamento de respostas provenientes da IA

---

## 🛠️ Tecnologias Utilizadas

### Backend

* Python
* Django

### Frontend

* HTML5
* CSS3
* JavaScript

### Banco de Dados

* SQLite

### Inteligência Artificial

* OpenAI API (ChatGPT)

### Ferramentas

* Git
* GitHub

---

## 🏗️ Arquitetura da Solução

```text
Usuário
   │
   ▼
Frontend (HTML, CSS, JS)
   │
   ▼
Backend Django
   │
   ▼
OpenAI API
   │
   ▼
Geração do Caso Clínico
```

---

## 📷 Demonstração

### Tela Inicial

*(Inserir screenshot)*

### Configuração do Caso Clínico

*(Inserir screenshot)*

### Caso Clínico Gerado

*(Inserir screenshot)*

### Histórico de Conversas

*(Inserir screenshot)*

---

## 📚 Estrutura do Projeto

```text
PsicoSimula/
├── ferramentaweb/
│   ├── templates/
│   ├── static/
│   ├── views.py
│   ├── models.py
│   └── urls.py
│
├── tcc/
├── db.sqlite3
└── manage.py
```

---

## 🚀 Executando Localmente

### Pré-requisitos

* Python 3.10+
* pip
* Chave da OpenAI API

### Clonar o projeto

```bash
git clone https://github.com/HadesKerbecs/PsicoSimula.git
cd PsicoSimula
```

### Criar ambiente virtual

```bash
python -m venv venv
```

### Ativar ambiente virtual

Windows:

```bash
venv\Scripts\activate
```

Linux/macOS:

```bash
source venv/bin/activate
```

### Instalar dependências

```bash
pip install -r requirements.txt
```

### Configurar variável de ambiente

```env
OPENAI_API_KEY=sua_chave_aqui
```

### Executar migrações

```bash
python manage.py migrate
```

### Iniciar aplicação

```bash
python manage.py runserver
```

Acesse:

```text
http://127.0.0.1:8000
```

---

## 🎓 Contexto Acadêmico

**Curso:** Engenharia de Software

**Projeto:** Trabalho de Conclusão de Curso (TCC)

**Autor:** Eduardo Tristão Melo

**Tema:** Ferramenta Web para Geração e Apresentação de Casos Clínicos Hipotéticos em Psicopatologia utilizando Inteligência Artificial Generativa

---

## 📌 Objetivos do Projeto

* Apoiar o ensino da psicopatologia
* Estimular o raciocínio clínico
* Explorar aplicações práticas de IA Generativa
* Aplicar conceitos de Engenharia de Software em um projeto real
* Demonstrar integração entre aplicações web e modelos de IA

---

## ⚠️ Aviso

* Todos os casos gerados são fictícios.
* Não são utilizados dados reais de pacientes.
* A ferramenta possui finalidade exclusivamente educacional.
* Não substitui avaliação ou diagnóstico profissional.

---

## 📄 Documentação

O projeto possui documentação acadêmica completa descrevendo:

* Fundamentação teórica
* Metodologia de desenvolvimento
* Arquitetura da solução
* Resultados obtidos
* Discussões e conclusões
