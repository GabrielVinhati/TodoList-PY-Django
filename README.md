Para configurar e rodar o projeto corretamente no VSCode ou em outro ambiente de desenvolvimento, siga os seguintes passos:

Baixar o projeto: Primeiro, baixe o projeto para a sua máquina, seja clonando o repositório do GitHub ou baixando o código fonte diretamente.

Instalar o Python: Certifique-se de que o Python esteja instalado na sua máquina. Você pode baixar o Python através do site oficial: Python Downloads.

Instalar o Django: Após garantir que o Python está instalado, você precisa instalar o Django. Isso pode ser feito abrindo o terminal no VSCode (ou qualquer terminal) e executando o seguinte comando:
pip install django

Instalar todas as dependências: Depois de instalar o Django, você pode instalar todas as dependências do projeto de uma só vez utilizando o arquivo requirements.txt (que contém todas as bibliotecas necessárias para rodar o projeto). Com o terminal aberto no diretório do projeto, execute:
pip install -r requirements.txt

Isso instalará todas as bibliotecas, incluindo o Django, para garantir que o projeto funcione corretamente com o comando:
python manage.py runserver
na porta      http://127.0.0.1:8000/           estará o projeto.


To set up and run the project correctly in VSCode or another development environment, follow these steps:

Download the project: First, download the project to your machine by either cloning the GitHub repository or downloading the source code directly.

Install Python: Make sure that Python is installed on your machine. You can download Python from the official website: Python Downloads.

Install Django: After confirming that Python is installed, you need to install Django. This can be done by opening the terminal in VSCode (or any terminal) and running the following command:
pip install django

Install all dependencies: Once Django is installed, you can install all the project dependencies at once by using the requirements.txt file (which contains all the necessary libraries for the project to run). With the terminal open in the project directory, run:
pip install -r requirements.txt

This will install all the libraries, including Django, to ensure the project runs correctly. Then, use the following command to start the project:
python manage.py runserver

The project will be available at the address:   http://127.0.0.1:8000/    .
