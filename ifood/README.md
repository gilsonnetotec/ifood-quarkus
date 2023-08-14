# ifood-quarkus
Sistema do ifood utilizando o framework Quarkus

1. **Instalação de Dependências:**
   Execute o seguinte comando para instalar as dependências do projeto:

   ```bash
   mvn io.quarkus:quarkus-maven-plugin:2.5.0.Final:create
   mvn quarkus:add-extension -Dextensions="jdbc-postgres,io.quarkus:quarkus-hibernate-orm-panache,resteasy-jsonb,io.quarkus:quarkus-smallrye-openapi,hibernate-validator"
   mvn compile quarkus:dev
