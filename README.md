# Foodmine

*Website de compras de comidas*

Nele será possível:<br>  
  - Popular o banco através das api's: <br>
    Comidas: http://localhost:5000/api/foods/seed <br>
    Usuários: http://localhost:5000/api/users/seed <br>
  
  - Filtrar a lista de comidas através da *Pesquisa* ou clicando nas *Tags*; <br>
  - Selecionar uma comida e visualizar seu detalhes; <br>     
  - Adicionar a comida selecionada ao carrinho; <br>
  - Ajustar a quantidade de itens e/ou Finalizar Pedido no Carrinho; <br>
  - Logar ou Criar um usuário/Logar através do *Registre-se aqui*; <br>
  - Visualizar o *Formulário de Pedido* onde terá de encontrar sua localização e *Ir Para Pagamento*; <br>
  - Pagamento será realizado através do *PayPal*;

<br><br>

# Detalhes para subir o projeto em http://localhost:4200
1. Baixar o projeto através do cmd => git clone https://github.com/andersonjanuario/foodmine.git <br>

2. Configurar variáveis locais: <br>
  - Crie o arquivo *.env* dentro da pasta *backend/src/* <br>
  - Adicione as variáveis MONGO_URI e JWT_SECRET dentro do *.env*:
    ```
    //Conexão ao MONGODB local
    MONGO_URI=mongodb://localhost:27017
    
    JWT_SECRET="UmTextoQualquer"
    ```

3. Acessar a pasta foodmine <br>
  - *Frontend* <br>
    Abrir um terminal e rodar os seguintes comandos: <br>
    ```
    cd frontend
    ```
    ```
    npm install --force
    ```
    ```
    npm start
    ```
    
    <br>
    
 - *Backend* <br>
    Abrir um novo terminal e rodar os seguintes comandos: <br>
    ```
    cd backend
    ```
    ```
    npm install
    ```
    ```
    npm start
    ```
    
<br>
    
4. Tudo dando certo o Website estará disponível no edereço => http://localhost:4200
