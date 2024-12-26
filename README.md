# ASPNETCore8-MVC-AzureEventHubs-AppInsightsConnString_Enquete
Exemplo de gera��o de eventos envolvendo o voto em uma enquete sobre o dia favorito da semana, utilizando o Azure Event Hubs em uma Web App criada com o .NET 8 + ASP.NET Core. Inclui o uso de um Dockerfile para gera��o de imagens Linux, al�m de monitoramento com o Azure Application Insights (utilizando Connection String).

## Estrutura de Diret�rio

<img src="./assets/directory_structure.png" width=115><br>

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