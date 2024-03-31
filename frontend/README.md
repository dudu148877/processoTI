# Acesse a pasta 'frontend'
cd todo-list/frontend

# Instale as dependências usando npm
npm install

# Crie um arquivo .env a partir do .env.example e configure a variável VITE_BASE_URL com o caminho e porta do servidor Laravel
cp .env.example .env
# Edit .env and set VITE_BASE_URL=<Laravel Server URL>

# Compile os assets do Vue
npm run dev