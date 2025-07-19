# 🏫 PySchool – Sistema de Gestão Escolar

Sistema web simples para cadastro e gerenciamento de alunos e livros, feito com **Python, Flask, SQLAlchemy e SQLite**.

---

## 🚀 Tecnologias Utilizadas

- [Python 3](https://www.python.org/)
- [Flask](https://flask.palletsprojects.com/)
- [Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/)
- [SQLite](https://www.sqlite.org/index.html)

---

## 📁 Estrutura do Projeto

    pyschool-flask-gestão-escolar/
    │
    ├── app/
    │ ├── models/
    │ ├── templates/
    │ ├── static/
    │ └── dados.db
    │
    ├── run.py
    ├── config.py
    ├── requirements.txt
    └── README.md

---

## ⚙️ Como Executar o Projeto

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/pyschool.git
cd pyschool

# Crie e ative o ambiente virtual
python -m venv .venv
# Windows:
.venv\Scripts\activate
# Linux/Mac:
source .venv/bin/activate

# Instale as dependências
pip install -r requirements.txt

# Execute o projeto
python run.py

Acesse: http://localhost:5000

✅ Funcionalidades
 Criação automática do banco de dados

 Modelo de usuários com SQLAlchemy

 Cadastro via formulário HTML

 Listagem e busca de dados

 Relacionamento com tabela de livros

 Autenticação de usuário (login)

 Interface com Bootstrap

📌 Melhorias Futuras
 CRUD completo de usuários e livros

 Templates HTML com Jinja2

 Sistema de autenticação e sessão

 Deploy em servidor gratuito (Render, Vercel, PythonAnywhere)

👤 Autores
Rhaniel Henrique Da Silva, Gabriel Da Silva Brandão, Luiz Gustavo
Projeto com fins educacionais.
Email: rhanielhen0@gmail.com