# AtividadeAPIBA-SEM4

Study Manager API (FastAPI) 📚
Este projeto é uma API desenvolvida com FastAPI para o gerenciamento de atividades acadêmicas e cronogramas de estudo. O foco é fornecer uma interface rápida e eficiente para organizar tarefas, prazos e conteúdos.

🚀 Tecnologias Utilizadas
FastAPI: Framework moderno e de alto desempenho para Python.

Pydantic: Para validação de dados e esquemas.

Uvicorn: Servidor ASGI para rodar a aplicação.

Python 3.10+

🔧 Como Rodar o Projeto
Clone o repositório:

Bash
git clone https://github.com/SanthiagoAbreu/AtividadeAPIBA-SEM4.git
cd AtividadeAPIBA-SEM4/StudyManagerFastAPI
Crie e ative um ambiente virtual:

Bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
# ou
.\venv\Scripts\activate  # Windows
Instale as dependências:

Bash
pip install fastapi uvicorn
Inicie o servidor:

Bash
uvicorn main:app --reload
📍 Endpoints Principais
Após iniciar o servidor, a documentação interativa estará disponível em:

Swagger UI: http://127.0.0.1:8000/docs

Redoc: http://127.0.0.1:8000/redoc

📝 Estrutura de Pastas
Plaintext
StudyManagerFastAPI/
├── main.py          # Ponto de entrada da aplicação
├── models/          # Modelos de dados (Pydantic/Entidades)
├── routers/         # Rotas divididas por contexto
└── database/        # Configurações de persistência (se houver)
🛠️ Funcionalidades Planejadas / Implementadas
[x] CRUD de Matérias/Disciplinas.

[x] Gerenciamento de Tarefas com prazos.

[ ] Autenticação de Usuário (OAuth2).

[ ] Integração com Banco de Dados.

Autor: Santhiago Abreu
