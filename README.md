

# Meu Projeto Django

O projeto tem como objetivo criar um blog onde podemos fazer postagens diversas(incluindo editar e excluir).

## Pré-requisitos

Antes de começar a trabalhar com este projeto, você deve ter os seguintes requisitos instalados em sua máquina:

- Python 3.7 ou superior
- Django 3.2 ou superior

## Instalação

Siga as etapas abaixo para configurar e executar o projeto em sua máquina:

1. Clone este repositório para o seu ambiente local:

git clone https://github.com/gabitenoriob/django-blog


2. Navegue até o diretório do projeto:

cd django-blog

3. Crie um ambiente virtual (recomendado) e ative-o:

python -m venv venv
source venv\Scripts\activate

4. Instale as dependências do projeto:

pip install -r requirements.txt

5. Execute as migrações do banco de dados:

python manage.py migrate

## Executando o Projeto

Para iniciar o servidor de desenvolvimento, execute o seguinte comando:

python manage.py runserver

Após a inicialização, você poderá acessar o projeto em seu navegador em `http://127.0.0.1:8000/`.

## Personalização


- Edite os modelos em `meuapp/models.py` para definir seus próprios modelos de dados.
- Crie visualizações personalizadas em `meuapp/views.py`.
- Configure URLs em `meuapp/urls.py` para suas visualizações.
- Personalize os modelos de administração em `meuapp/admin.py` para gerenciar seus dados de maneira fácil.
- Adicione templates HTML em `meuapp/templates/` para criar as páginas da web do seu aplicativo.
- Estilize suas páginas usando CSS e arquivos estáticos em `meuapp/static/`.



## Referencia :

https://tutorial.djangogirls.org/en/django_start_project/
