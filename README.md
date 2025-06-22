 📦 Sistema de Gestão de Estoque (SGE)

Bem-vindo ao **Sistema de Gestão de Estoque (SGE)**, um projeto desenvolvido em **Django** e **Bootstrap 5** com o objetivo de facilitar o gerenciamento de estoque de forma simples e eficiente.

<img src="/img/image.png">

## ✅ Requisitos

Certifique-se de ter os seguintes itens instalados em seu sistema:

- **Python** (recomendado: 3.7 ou superior)
- **Virtualenv** (opcional, mas recomendado)
- **Django** (instalado via `requirements.txt`)
- Demais dependências listadas no arquivo `requirements.txt`

---

## ⚙️ Instalação do Projeto

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio
2. Crie e ative o ambiente virtual (recomendado)
bash
Copiar
Editar
python -m venv venv
# Ativar no Windows
venv\Scripts\activate
# Ativar no Linux/Mac
source venv/bin/activate
3. Instale as dependências
bash
Copiar
Editar
pip install -r requirements.txt
🔧 Configuração e Execução
1. Aplique as migrações
bash
Copiar
Editar
python manage.py migrate
2. Crie um superusuário (para acessar o admin)
bash
Copiar
Editar
python manage.py createsuperuser
Siga as instruções no terminal para definir usuário, e-mail e senha.

3. Rode o servidor
bash
Copiar
Editar
python manage.py runserver
4. Acesse o sistema
Abra seu navegador e vá para:

arduino
Copiar
Editar
http://localhost:8000
🛠 Tecnologias Utilizadas
Django

Bootstrap 5

SQLite3 (padrão do Django para testes locais)


👨‍💻 Autor
Kleiton Macedo
LinkedIn