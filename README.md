# Projeto MVP de pós graduação em engenharia de software - PUC-RJ - BackEnd

O objetivo é apresentar uma API seguindo o estilo REST.

# As principais tecnologias que serão utilizadas aqui são:

Flask;
SQLAlchemy;
OpenAPI3;
SQLite;
Instalação;
Será necessário ter todas as libs python listadas no requirements.txt instaladas. Após clonar o repositório, é necessário ir ao diretório raiz, pelo terminal, para poder executar os comandos descritos abaixo.

É fortemente indicado o uso de ambientes virtuais do tipo virtualenv.

(env)$ pip install -r requirements.txt
Este comando instala as dependências/bibliotecas, descritas no arquivo requirements.txt.

# Executando o servidor
Para executar a API basta executar:

(env)$ flask run --host 0.0.0.0 --port 5000
Em modo de desenvolvimento é recomendado executar utilizando o parâmetro reload, que reiniciará o servidor automaticamente após uma mudança no código fonte.

(env)$ flask run --host 0.0.0.0 --port 5000 --reload

# Acesso no browser
Abra o http://localhost:5000/#/ no navegador para verificar o status da API em execução.
