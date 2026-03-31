# Configuração do Ambiente - Django

## 1. Introdução ao Django

O Django é um framework web em Python utilizado para desenvolver aplicações web de forma rápida, segura e organizada.

## 2. Instalação do Python

Primeiramente, foi necessário instalar o Python no computador para poder utilizar o Django.

## 3. Criação do ambiente virtual

Foi criado um ambiente virtual para isolar as dependências do projeto, utilizando o comando:
python -m venv venv

## 4. Ativação do ambiente virtual

Após a criação, o ambiente virtual foi ativado com o comando:

No Windows:
venv\Scripts\activate

## 5. Instalação do Django

Com o ambiente ativado, foi feita a instalação do Django com o comando:
pip install django

## 6. Criação do projeto Django

O projeto foi criado utilizando o comando:
django-admin startproject meu_projeto

## 7. Acessar a pasta do projeto

Entrar na pasta criada com o comando:
cd meu_projeto

## 8. Inicialização do servidor

O servidor foi iniciado com o comando:
python manage.py runserver

## 9. Acesso no navegador

Após iniciar o servidor, o projeto pode ser acessado no navegador pelo endereço:
http://127.0.0.1:8000/
