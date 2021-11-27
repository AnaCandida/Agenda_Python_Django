# Agenda Python Django - replicada


Esse projeto foi desenvolvido durante o módulo de Python no curso oferecido pela NL Informática.

O Desafio consistia em :

 - Replicar/Clonar/Baixar o projeto original do seguinte repositório:   
   [https://github.com/leovd100/Agenda_Python_Django];
 - Fazer o projeto rodar em sua máquina;
 - Realizar melhorias nas telas e  adicionar uma imagem na tela de
   login;
 - Subir o projeto no seu GitHub    melhorando também a documentação.

# Getting Started

Para conseguir rodar o app da agenda você precisa:

 **1. Clonar esse diretório:**

      git clone https://github.com/AnaCandida/Agenda_Python_Django.git

 
 **2. Configurando o ambiente**

 - garanta que tenha o python3 instalado.Use: python3 -v
 - Use um ambiente virtual Python:
		  -Instale o virtualenv ;
		- Crie uma virtual **env** para o projeto e ative-a;
		- Verifique se vc tem a versão 3.2.9 do Djanjo, se não, instale dentro da env a versão 						correta.
		-  No terminal, atualize o banco de dados da venv:
	
		  python3 manage.py migrate

	-Execute o servidor para rodar o app:

		    python3 manage.py runserver

Ajuda com o virtualenv
https://docs.python.org/3/library/venv.html

Ajuda com o Django
https://docs.djangoproject.com/en/3.2/intro/install/


## *Se tudo der certo, após rodar o servidor você verá a tela de login:*

![tela de login](https://github.com/AnaCandida/Agenda_Python_Django/blob/4e6b471622b5a875c0635250354a9b07e111c1ec/telaLogin.png  "Tela de login" )



 Entre com o usuário e senha abaixo:
	

 - usuario: admin 	
 - senha:12345


# #Melhorias e aprendizados

Este foi meu primeiro contato com python e com o  Django. Precisei aprender sobre  o padrão de projeto  MTV (Model, Template, View) e me familiarizar com o uso da virutalenv. Implementei:

 - Refatoração dos templates com uso do "block content";
 - Criação de um padrão de design para o app.
 - Refatoração do css e aplicação do padrão de design, com reutilização de classes;
 - Responsividade das telas; 
 - Inserção de imagem em todas as telas;
 - Troca de senha do superadmin;
 
