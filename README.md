# busque-cep API REST
 
 API composta por duas rotas:
[IP]:[PORTA]/zip_code/${codigoCep}
[IP]:[PORTA]/city/${codigoIbge}

 Tem a findalidade de retornar os dados cadastrais de uma cidade ou CEP, a partir de um código de ibge ou código de CEP utilizado como url path.
 

 Nesse projeto foi utilizado uma conexão fixa com um banco de dados mariadb através de typeORM.
