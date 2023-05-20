<p align="center">
	<img src="https://github.com/nocodeleaks/quepasa/raw/main/src/assets/favicon.png" alt="Quepasa-logo" width="100" />	
	<p align="center">Quepasa é um software de código aberto, totalmente gratuito, para troca de mensagens com a plataforma Whatsapp</p>
</p>
<hr />
<p align="left">
	<img src="https://telegram.org/favicon.ico" alt="Telegram-logo" width="32" />
	<span>Grupo e Canal Telegram: </span>
	<a href="https://t.me/quepasa_api" target="_blank">Grupo</a>
	<span> || </span>
	<a href="https://t.me/quepasa_channel" target="_blank">Canal</a>
</p>
<hr />
<p align="left">
	<img src="https://whatsapp.com/favicon.ico" alt="WhatsAPP-logo" width="32" />
	<span>Grupo WhatsaAPP: </span>
	<a href="https://chat.whatsapp.com/Cv5WfmujRzE09yQ6hagYim" target="_blank">Grupo</a>
</p>
----------------------------------------------------------------------------
</p>

**Gostou do Tutorial? Faça sua Contribuição**

<img src="https://github.com/EngajamentoFlow/quepasa/blob/main/Contribui%C3%A7%C3%A3o.png" alt="Quepasa-logo" width="200" />
</p>

**PIX CNPJ**

```
45959142000119	
```
----------------------------------------------------------------------------

**Manual Gateway de pagamento Asaas com Quepasa**

----------------------------------------------------------------------------

**Conta Asaas**

</p>
Precisamos ter uma conta na Asaas se não tiver uma copie link abaixo 
</p>

```
https://www.asaas.com/r/fb/494c528f-9bd1-4f7a-b31d-4def8c0822d0
```

</p>
Acesse o painel de controle do ASAAS em https://www.asaas.com/login.

Faça login com suas credenciais de conta.
</p>
Após fazer login, clique no seu nome de usuário no canto superior direito e selecione "Configurações" no menu suspenso.
</p>
Na página de configurações, clique na guia "Tokens" no menu lateral esquerdo.
</p>
Na seção "Tokens de acesso", clique no botão "Novo token".

Crie 4 Links de Pagamento

Todos eles tem link unico no final que seja "ID Plano" no N8N

----------------------------------------------------------------------------

**Segundo passo imaginamos que vc ja tenha Chatwoot+N8N+Quepasa instalados**

Manual Instalação CHATWOOT QUEPASA

https://github.com/EngajamentoFlow/chatwoot

Manual Instalação N8N

https://github.com/EngajamentoFlow/n8n

Manual Instalação QUEPASA

https://github.com/EngajamentoFlow/quepasa

Montando Caixa de Entrada

https://github.com/EngajamentoFlow/quepasan8nchatwoot

----------------------------------------------------------------------------

**Worflows N8N**

</p>
Abaixe o Worflows que estão nesse GitHub e importe em seu N8N
</p>

**Worflow Asaas Chatwoot Pagamentos Quepasa**

</p>
Procure por "Coloque as informações Informações"
</p>
Coloque seguintes informações
</p>
URLQUEPSA
</p>
TOKEN QUEPASA
</p>
URL CHATWOOT
</p>
Token Asaas
</p>
ID Plano 1
</p>
ID Plano 2
</p>
ID Plano 3
</p>
ID Plano 4
</p>
Seu Numero de Telefone
</p>
Ajuste NO Trigger Renovação para numero do Worflow Worflow Asaas Chatwoot Pagamentos Quepasa Renovação"
</p>
Ative Worflow e pronto primeiro ja esta funcionando 
</p>

----------------------------------------------------------------------------
</p>

**Worflow Asaas Chatwoot Pagamentos Quepasa Renovação**

</p>
Nesse worflow não faremos nada
</p>

----------------------------------------------------------------------------
</p>
</p>

**Criando credenciais do Google Sheets no n8n**

</p>
Você precisa seguir os seguintes passos:
 </p>
Acesse o Google Cloud Console em https://console.cloud.google.com/.
</p>
Clique no botão "Selecionar projeto" no canto superior direito e crie um novo projeto ou selecione um projeto existente.
</p>
Após selecionar ou criar um projeto, clique no botão de navegação no canto superior esquerdo e vá para a seção "API e serviços" e, em 
</p>
seguida, "Biblioteca".
</p>
Na biblioteca de APIs, pesquise por "Google Sheets API" e clique no resultado correspondente.
</p>
Na página da API do Google Sheets, clique no botão "Ativar" para habilitar a API para o seu projeto.
</p>
Após ativar a API, volte para a seção "API e serviços" e clique em "Credenciais".
</p>
Na página de Credenciais, clique no botão "Criar credenciais" e selecione "ID do cliente OAuth".
</p>
Na seção "Configurar consentimento OAuth", preencha as informações necessárias, como nome do aplicativo, e-mail de contato e escopos de 
</p>
acesso. Certifique-se de adicionar o escopo "https://www.googleapis.com/auth/spreadsheets" para acesso ao Google Sheets.
</p>
Após configurar o consentimento, você será redirecionado para a página de criação das credenciais.
</p>
Selecione o tipo de aplicativo adequado para o seu caso de uso. Por exemplo, se você estiver usando o n8n localmente, pode escolher 
</p>
"Aplicativo para área de trabalho".
</p>
Preencha as informações adicionais necessárias, como nome da credencial e URIs de redirecionamento.
</p>
Clique no botão "Criar" para criar as credenciais.
</p>
Na página de credenciais, você encontrará as informações da credencial criada, incluindo o ID do cliente e o segredo do cliente.
</p>
No n8n, adicione um nó "Google Sheets" ao seu fluxo de trabalho.
</p>
Configure o nó "Google Sheets" e clique em "Autenticar".
</p>
Na janela de autenticação exibida, selecione "Google Sheets OAuth2 API" como serviço, insira o ID do cliente e o segredo do cliente 
</p>
obtidos nas etapas anteriores.
</p>
Siga as etapas de autorização e autenticação para conceder acesso ao n8n para interagir com o Google Sheets.
</p>
Após autenticar com sucesso, o nó "Google Sheets" estará pronto para uso em seu fluxo de trabalho.
</p>
Certifique-se de proteger suas credenciais do Google Sheets e não compartilhá-las com outras pessoas, pois elas fornecem acesso aos seus 
</p>
dados do Google Sheets.
</p>

----------------------------------------------------------------------------

</p>

**Pegando suas credeciais no n8n do Postgres**

</p>
Acesse o diretório do Chatwoot em seu sistema onde o aplicativo está instalado.
</p>
Procure o arquivo .env no diretório chatwoot ou chatwoot/chatwoot. O caminho completo pode ser semelhante a /home/chatwoot/chatwoot/.env.
</p>
Abra o arquivo .env em um editor de texto.
</p>
Dentro do arquivo, você encontrará variáveis de ambiente definidas, incluindo aquelas relacionadas ao banco de dados PostgreSQL.
</p>
Procure as variáveis de ambiente relacionadas ao PostgreSQL, que normalmente incluem POSTGRES_HOST, POSTGRES_PORT, POSTGRES_DATABASE, 
</p>
POSTGRES_USERNAME e POSTGRES_PASSWORD.
</p>
Anote os valores dessas variáveis, que representam as informações de conexão necessárias.
</p>
Agora você pode usar essas informações para configurar o nó PostgreSQL no n8n. Ao configurar o nó PostgreSQL, preencha as seguintes 
</p>
informações:
</p>
Host: O valor da variável POSTGRES_HOST.
</p>
Port: O valor da variável POSTGRES_PORT.
</p>
Database: O valor da variável POSTGRES_DATABASE.
</p>
User: O valor da variável POSTGRES_USERNAME.
</p>
Password: O valor da variável POSTGRES_PASSWORD.
</p>
Certifique-se de fornecer as informações corretas e de que o servidor do banco de dados PostgreSQL esteja acessível para o nó PostgreSQL 
</p>
do n8n. Lembre-se também de proteger as credenciais e não compartilhá-las publicamente.
</p>

----------------------------------------------------------------------------

**Worflow Asaas Chatwoot Pagamentos Quepasa Vencidos**

</p>
Crie uma planilha Google Sheets com seguintes colunas
</p>
Nome	
</p>
Email	
</p>
Telefone	
</p>
Próximo Vencimento
</p>
Coloque suas credeciais Google Sheets
</p>
Coloque credeciais Postgres a mesma usada no Chatwoot
</p>

----------------------------------------------------------------------------
----------------------------------------------------------------------------

</p>

**Pronto tudo Funcionando**

</p>

----------------------------------------------------------------------------
----------------------------------------------------------------------------

**Gostou do Tutorial? Faça sua Contribuição**

<img src="https://github.com/EngajamentoFlow/quepasa/blob/main/Contribui%C3%A7%C3%A3o.png" alt="Quepasa-logo" width="200" />
</p>


**PIX CNPJ**

```
45959142000119	
```

----------------------------------------------------------------------------
