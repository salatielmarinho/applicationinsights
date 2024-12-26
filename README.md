# ASPNETCore8-MVC-AzureEventHubs-AppInsightsConnString_Enquete
Exemplo de gera��o de eventos envolvendo o voto em uma enquete sobre o dia favorito da semana, utilizando o Azure Event Hubs em uma Web App criada com o .NET 8 + ASP.NET Core. Inclui o uso de um Dockerfile para geração de imagens Linux, al�m de monitoramento com o Azure Application Insights (utilizando Connection String).

## Estrutura de Diret�rio

``
Directory structure:
??? salatielmarinho-applicationinsights/
    ??? LICENSE
    ??? README.md
    ??? doc/
    ??? src/
        ??? SiteQuestaoEventHub/
            ??? appsettings.Development.json
            ??? SiteQuestaoEventHub.csproj
            ??? appsettings.json
            ??? Properties/
            ?   ??? launchSettings.json
            ??? Models/
            ?   ??? ErrorViewModel.cs
            ??? Controllers/
            ?   ??? HomeController.cs
            ?   ??? VotacaoController.cs
            ??? wwwroot/
            ?   ??? lib/
            ?   ?   ??? bootstrap/
            ?   ?   ?   ??? LICENSE
            ?   ?   ?   ??? dist/
            ?   ?   ?       ??? css/
            ?   ?   ?       ?   ??? bootstrap.css
            ?   ?   ?       ?   ??? bootstrap-reboot.css
            ?   ?   ?       ?   ??? bootstrap-reboot.rtl.css
            ?   ?   ?       ?   ??? bootstrap-utilities.rtl.css
            ?   ?   ?       ?   ??? bootstrap-grid.rtl.css
            ?   ?   ?       ?   ??? bootstrap-utilities.css
            ?   ?   ?       ?   ??? bootstrap.rtl.css
            ?   ?   ?       ?   ??? bootstrap-grid.css
            ?   ?   ?       ??? js/
            ?   ?   ?           ??? bootstrap.js
            ?   ?   ?           ??? bootstrap.esm.js
            ?   ?   ?           ??? bootstrap.bundle.js
            ?   ?   ??? jquery-validation-unobtrusive/
            ?   ?   ?   ??? jquery.validate.unobtrusive.js
            ?   ?   ?   ??? LICENSE.txt
            ?   ?   ??? jquery/
            ?   ?   ?   ??? LICENSE.txt
            ?   ?   ?   ??? dist/
            ?   ?   ?       ??? jquery.js
            ?   ?   ??? jquery-validation/
            ?   ?       ??? LICENSE.md
            ?   ?       ??? dist/
            ?   ?           ??? jquery.validate.js
            ?   ?           ??? additional-methods.js
            ?   ??? css/
            ?   ?   ??? site.css
            ?   ??? js/
            ?       ??? site.js
            ??? EventHubs/
            ?   ??? AzureEventHubsExtensions.cs
            ?   ??? VotacaoProducer.cs
            ?   ??? Voto.cs
            ??? Dockerfile
            ??? SiteQuestaoEventHub.sln
            ??? Views/
            ?   ??? Shared/
            ?   ?   ??? _ValidationScriptsPartial.cshtml
            ?   ?   ??? _Layout.cshtml.css
            ?   ?   ??? _Layout.cshtml
            ?   ?   ??? Error.cshtml
            ?   ??? Home/
            ?   ?   ??? Privacy.cshtml
            ?   ?   ??? Index.cshtml
            ?   ??? _ViewImports.cshtml
            ?   ??? _ViewStart.cshtml
            ??? Program.cs
``

## Instala��o 

1. **Clone o Reposit�rio:** Primeiro, fa�a o clone do reposit�rio para o seu ambiente local. Utilize o comando abaixo no terminal ou prompt de comando:

` git clone https://github.com/salatielmarinho/applicationinsights.git `

2. **Acesse o Diret�rio do Projeto:** Navegue at� o diret�rio onde o reposit�rio foi clonado:

` cd salatielmarinho-applicationinsights `

3. **Instale as Depend�ncias:** Certifique-se de ter o .NET SDK instalado na sua m�quina. Em seguida, instale as depend�ncias do projeto:

` dotnet restore `

4. **Configura��o de Ambiente (Opcional):** Verifique os arquivos de configura��o `appsettings.Development.json` e `appsettings.json` para ajustar as configura��es conforme necess�rio.

5. **Compilar e Executar o Projeto:** Compile o projeto e, em seguida, execute-o:

` dotnet build
dotnet run
`

6. **Acesse a Aplica��o:** Ap�s a execu��o, a aplica��o estar� dispon�vel. Normalmente, ser� acess�vel via `http://localhost:5000` ou `http://localhost:5001` (HTTPS).

## Author

:boy: [Salatiel Marinho](https://github.com/salatielmarinho)