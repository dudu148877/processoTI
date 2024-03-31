# Clone o repositório em sua máquina local
git clone 

# Acesse a pasta 'api'
cd todo-list/api

# Crie um arquivo .env a partir do .env.example e configure as variáveis de ambiente para o banco de dados
cp .env.example .env

# Execute o Composer para instalar as dependências
composer install

# Gere uma chave única para a aplicação Laravel
php artisan key:generate

# Execute as migrações para criar as tabelas do banco de dados
php artisan migrate