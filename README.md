# Cadastro de Usuários com Django

Este é um projeto em Python utilizando o framework Django para criar um sistema de cadastro de usuários. O sistema permite que os usuários se cadastrem através de um formulário web e armazena as informações em um banco de dados.

## Funcionalidades

- Cadastro de novos usuários: Os usuários podem se cadastrar fornecendo um nome de usuário e idade.
- Armazenamento seguro: As informações dos usuários são armazenadas de forma segura no banco de dados.
- Visualização na página web: Os usuários cadastrados podem ser visualizados em uma página web, facilitando a administração do sistema.

## Pré-requisitos

Certifique-se de ter os seguintes requisitos instalados antes de executar o projeto:

- Python (versão 3.11.8)
- Django (versão 5.0.2)
- Banco de dados compatível com Django (por exemplo, SQLite, MySQL, PostgreSQL)

## Instalação

1. Clone este repositório para o seu ambiente local:

```
git clone https://github.com/paulo-hmm/user_registration.git
```

2. Navegue até o diretório do projeto:

```
cd projeto_cadastro
```

3. Instale as dependências do projeto:

```
pip install -r requirements.txt
```

4. Execute as migrações do Django para configurar o banco de dados:

```
python manage.py migrate
```

5. Inicie o servidor de desenvolvimento:

```
python manage.py runserver
```

6. Acesse o sistema em seu navegador web em [http://localhost:8000](http://localhost:8000).

## Utilização

1. Na página inicial, você encontrará um formulário de cadastro de usuário. Preencha os campos necessários e clique em "Enviar".
2. Após o cadastro, os usuários serão listados na página de visualização de usuários.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.
