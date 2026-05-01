# ♻️ ZenWaste

**Plataforma B2B para gestão inteligente de resíduos industriais**

---

## 🚀 Sobre o projeto

O **ZenWaste** é uma aplicação web desenvolvida para otimizar a gestão de resíduos industriais dentro de empresas, oferecendo controle de estoque, organização de dados e base para criação de um marketplace de resíduos.

A proposta vai além de um CRUD: a ideia é evoluir para uma plataforma SaaS capaz de conectar empresas, reduzir desperdício e gerar valor a partir de dados.

---

## 🎯 Objetivo

- Melhorar o controle e rastreabilidade de resíduos  
- Digitalizar processos internos de gestão ambiental  
- Criar oportunidades de reutilização de materiais  
- Servir como base para um ecossistema B2B  

---

## ⚙️ Funcionalidades

- Cadastro de empresas  
- Gestão de estoque de resíduos  
- CRUD completo de produtos  
- API REST em JSON  
- Estrutura preparada para expansão (marketplace + inteligência de dados)  

---

## 🛠️ Tecnologias utilizadas

- Python  
- Django  
- Django REST Framework  
- SQLite (ambiente de desenvolvimento)  

---

## ▶️ Como executar

```bash
# Clonar o repositório
git clone https://github.com/gustavoreis7/ZenWaste.git

# Entrar na pasta
cd ZenWaste

# Criar ambiente virtual
python -m venv venv

# Ativar ambiente
# Windows:
venv\Scripts\activate
# Linux/Mac:
source venv/bin/activate

# Instalar dependências
pip install -r requirements.txt

# Rodar migrações
python manage.py migrate

# Iniciar servidor
python manage.py runserver
