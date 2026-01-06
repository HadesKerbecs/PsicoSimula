🧠 PsicoSimula — Ferramenta Web para Ensino de Psicopatologia com IAG

O PsicoSimula é uma ferramenta web educacional desenvolvida como Trabalho de Conclusão de Curso (TCC) em Engenharia de Software, com o objetivo de auxiliar o ensino e o estudo da psicopatologia por meio da Inteligência Artificial Generativa (IAG).
A plataforma permite a geração de casos clínicos hipotéticos personalizados, proporcionando uma experiência de aprendizado interativa, dinâmica e adaptável para estudantes e profissionais da área da saúde mental.

🎓 Contexto Acadêmico

* Projeto: Trabalho de Conclusão de Curso (TCC)
* Curso: Engenharia de Software
* Autor: Eduardo Tristão Melo
* Tema: Ferramenta web para geração e apresentação de casos clínicos hipotéticos em psicopatologia utilizando Inteligência Artificial Generativa

✨ Funcionalidades

* Geração automática de casos clínicos hipotéticos com apoio de IA
* Personalização de parâmetros clínicos:
  * Idade
  * Histórico médico
  * Contexto social
  * Complexidade do caso
* Interface web responsiva e interativa
* Feedback automatizado para apoio ao raciocínio clínico
* Armazenamento do histórico de interações do usuário
* Ambiente voltado ao aprendizado prático e simulado, sem uso de dados reais

🧱 Tecnologias Utilizadas
Frontend
* HTML5
* CSS3
* JavaScript

Backend
* Python
* Django

Banco de Dados
* SQLite (armazenamento do histórico de interações)

Inteligência Artificial
* OpenAI API (ChatGPT)

📂 Estrutura do Projeto
PsicoSimula/
├── ferramentaweb/        # Aplicação principal Django
│   ├── templates/        # Templates HTML
│   ├── static/           # Arquivos estáticos (CSS, JS, imagens)
│   ├── views.py
│   ├── models.py
│   └── urls.py
├── tcc/                  # Configurações do projeto Django
├── db.sqlite3
└── manage.py

🚀 Como Rodar o Projeto Localmente
🔹 Pré-requisitos

Antes de iniciar, certifique-se de ter instalado:

* Python 3.10 ou superior
* pip
* Conta na OpenAI (para geração da chave da API)

🔹 Clonar o repositório
git clone https://github.com/HadesKerbecs/PsicoSimula.git
cd PsicoSimula

🔹 Criar ambiente virtual (opcional, mas recomendado)
python -m venv venv


Ativar o ambiente virtual:

Windows
venv\Scripts\activate

Linux / macOS
source venv/bin/activate

🔹 Instalar dependências
pip install -r requirements.txt

🔹 Configurar a chave da OpenAI
Crie um arquivo .env na raiz do projeto ou configure diretamente nas variáveis de ambiente:

OPENAI_API_KEY=sua_chave_openai_aqui

🔐 Nunca versionar a chave da API no repositório

🔹 Executar migrações do banco
python manage.py migrate

🔹 Iniciar o servidor
python manage.py runserver

A aplicação estará disponível em:
http://127.0.0.1:8000/

⚠️ Observações Importantes

* Todos os casos clínicos gerados são hipotéticos
* A ferramenta não substitui diagnóstico profissional
* O projeto possui finalidade educacional e acadêmica
* Não são utilizados dados reais de pacientes

📌 Objetivo do Projeto

O PsicoSimula foi desenvolvido com foco em:
* Apoiar o ensino da psicopatologia
* Estimular o raciocínio clínico
* Explorar o uso de IA generativa em contextos educacionais
* Aplicar conceitos de Engenharia de Software em um projeto real

📄 Documentação Acadêmica

O texto completo do projeto está disponível no Trabalho de Conclusão de Curso (TCC), que descreve:
* Fundamentação teórica
* Metodologia
* Desenvolvimento da ferramenta
* Resultados e discussões
