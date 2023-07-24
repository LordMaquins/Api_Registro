# Api_Registro
Api para cadastrar produtos
API Vue com PHP 7, E Json
Este é um projeto de API construído utilizando o framework Vue.js no frontend e PHP 7 com Json no backend para salvar os dados. Essa API permite a criação, leitura, atualização e exclusão de recursos por meio de endpoints RESTful.

Requisitos
Certifique-se de ter os seguintes requisitos instalados em seu ambiente antes de começar:

PHP 7 ou versão superior
MySQL
Composer
Node.js e npm (Node Package Manager)
Vue CLI (Interface de Linha de Comando do Vue)
Configuração
Siga os passos abaixo para configurar e executar o projeto:

Clone o repositório para sua máquina local:
bash
Descompacte o arquivo.


cd api-vue-php-slim-mysql
Instale as dependências do backend usando o Composer:
bash
Copie o código
cd backend
composer install
Configure o banco de dados MySQL:

Copie o código
php -S localhost:8000 -t public
Instale as dependências do frontend:
bash
Copy code
cd ../frontend
npm install
Inicie o servidor frontend:
bash
Copie o código
npm run serve
Agora a API Vue com PHP 7, Slim e MySQL está em execução. O frontend estará disponível em http://localhost:8080 

Obs: O slim framework está no projeto mas não foi utilizado, por motivos de erros de compatibilidade e de conexões
