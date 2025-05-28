Sistema de Gestão de Estoque (SGE)
Bem-vindo ao Sistema de Gestão de Estoque (SGE), um projeto desenvolvido em Django e Bootstrap 5 para facilitar o gerenciamento de estoque. Este README fornece informações essenciais sobre como configurar e executar o projeto em seu ambiente local.

Requisitos
-se de que você tenha certeza dos seguintes requisitos instalados em seu sistema:

Python (versão recomendada: 3.7 ou superior)
Django (instalado automaticamente ao seguir as instruções abaixo)
Outras dependências relacionadas no arquivorequirements.txt
Instalação das Dependências
Com o ambiente virtual ativado, instale as dependências do projeto usando o comando:

pip install -r requirements.txt
Rodar o projeto
Após instalar as dependências, aplique as migrações no banco de dados com o comando:

python manage.py migrate
Agora o projeto já pode ser inicializado com o comando:

python manage.py runserver
Após isso, o sistema estará pronto para ser acessado em: http://localhost:8000
