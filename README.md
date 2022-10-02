# Razor Pages Pizza App


### Commands
- dotnet run
	- Esse comando localiza o arquivo de projeto no diretório
	- Coleta e instala as dependências do projeto
	- Compila o código
	- Cria um servidor Web Kestrel do ASP.NET Core para chamadas HTTP e HTTPS
		- HTTP 5000 e 5300
		- HTTPS 7000 e 7300
		- As portas podem ser alteradas no arquivo launchSettings.json do projeto
- dotnet new page --name Pizza --namespace RazorPagesPizza.Pages --output Pages
	- Cria uma nova página Razor Pages
