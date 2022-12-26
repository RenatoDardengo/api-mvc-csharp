README.md

# comandos iniciais
``` bash
mkdir mvc-api
cd mvc-api
dotnet new mvc
```
# Comandos git
``` bash
code .gitignore
### gerar código para ignorar os arquivos ( Windows, Linux, Mac, DotnetCore, VisualStudioCode) em https://www.toptal.com/developers/gitignore/
 git init
 git add .
 git commit -m"Criando estrutura"
 git remote add origin git@github.com:RenatoDardengo/api-mvc-csharp.git
git branch -M main
git push -u origin main
 ```

 # Componenetes instalados
 ``` bash
 dotnet add package Microsoft.EntityFrameworkCore --version 7.0.1
 dotnet add package Microsoft.EntityFrameworkCore.Tools --version 7.0.1
 dotnet add package Microsoft.EntityFrameworkCore.SqlServer --version 7.0.1
 dotnet add package Microsoft.VisualStudio.Web.CodeGeneration.Design --version 7.0.1
 ```

 # Comandos para migração
  ``` bash
  dotnet tool install --global dotnet-ef
  dotnet ef migrations add ModeloAluno
  dotnet ef database update
  ```
  # Instalação do code Generator
   ``` bash
   dotnet tool install -g dotnet-aspnet-codegenerator
   ```

   # Gerando scaffold
    ``` bash
    dotnet aspnet-codegenerator controller -name AlunosController -m Aluno -dc DbContexto --relativeFolderPath Controllers --useDefaultLayout


    ```




