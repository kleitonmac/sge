📦 Sistema de Gestão de Estoque (SGE)

Bem-vindo ao **Sistema de Gestão de Estoque (SGE)**, um projeto desenvolvido em **Django** e **Bootstrap 5** com o objetivo de facilitar o gerenciamento de estoque de forma simples e eficiente.

---

## ✅ Requisitos

- Python 3.7 ou superior
- Git
- Virtualenv (opcional, mas recomendado)

---

## 🚀 Clonando o Repositório

```bash
git clone https://github.com/kleitonmac/sge.git
cd sge
🧪 Criando e Ativando Ambiente Virtual
bash
Copiar
Editar
python -m venv venv

# Ativar no Windows
venv\Scripts\activate

# Ativar no Linux/Mac
source venv/bin/activate
📦 Instalando Dependências
bash
Copiar
Editar
pip install -r requirements.txt
❗ Caso ainda não tenha o requirements.txt, você pode gerar com:

bash
Copiar
Editar
pip freeze > requirements.txt
🔧 Configuração e Execução

1. Aplicar Migrações
bash
Copiar
Editar
python manage.py migrate

2. Criar Superusuário (para acessar o painel administrativo)
bash
Copiar
Editar
python manage.py createsuperuser
Siga as instruções no terminal para definir usuário, e-mail e senha.

3. Rodar o Servidor
bash
Copiar
Editar
python manage.py runserver

4. Acessar o Sistema
Abra seu navegador e acesse:

arduino
Copiar
Editar
http://localhost:8000
🛠 Tecnologias Utilizadas
Django


SQLite3

👨‍💻 Autor
Kleiton Macedo
🔗https://www.linkedin.com/in/kleitonmacedo/
