# Imagem base node com a versão v14.19.0
FROM node:14.19.0
# Definindo o diretorio
WORKDIR /app
# Copiando os pacotes
COPY ./package*.json ./
# executando os pacotes
RUN npm install
# Copiando todos os arquivos
COPY . .
# expondo a porta da aplicação
EXPOSE 8080
# executando a aplicação
CMD ["node", "server.js"]