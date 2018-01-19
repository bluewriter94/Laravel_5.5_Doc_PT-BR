Instalação

- Instalação
	- Requisitos do Servidor
	- Instalando o Laravel
	- Configuração

- Configurações do Servidor Web
	- URLs bonitas


# Instalação
	
	Requerimentos do Servidor 
	
	O framework Laravel possui alguns requisitos do sistema. Claro, todos estes requisitos são satisfeitos pela Laravel Homestead
	virtual machine, então é altamente recomendado que utilize Homestead como seu ambiente de desenvolvimento local Laravel.

	De qualquer modo, se você não está utilizando Homestead, você precisará ter certeza que seu servidor atende os seguintes
	requerimentos:

	* PHP >= 7.0.0
	* OpenSSL PHP Extension
	* PDO PHP Extension
	* Mbstring PHP Extension
	* Tokenizer PHP Extension
	* XML PHP Extension


	Instalando o Laravel

	Laravel utiliza o composer para gerenciar suas dependências. Então, antes de utilizar o Laravel, tenha certeza que você tem o
	composer instalado na sua máquina.


	Através do instalador Laravel

	Primeiro, baixe o instalador Laravel utilizando o Composer.

	composer global require "laravel/installer"

	Make sure to place composer's system-wide vendor bin directory in your $ PATH para que o executável laravel possa ser localizado 
	pelo seu sistema. Este diretório existe em diferentes localizações baseadas em seu sistema operacional; de qualquer forma, alguns
	locais comuns incluem:

	* macOS: $HOME/.composer/vendor/bin
	* GNU/Linux Distributions: $HOME/.composer/vendor/bin

	Uma vez instalado, o comando laravel new irá criar uma nova instalação no diretorio especificado. Por exemplo, laravel new blog irá
	criar um diretório chamado blog contendo uma nova instalação Laravel com todas as dependências dependências do Laravel instaladas:

	laravel new blog

	Via Composer Create-Project
	
	Alternativamente, você pode também instalar o Laravel utilizando o comando Composer create-project no seu terminal:

	composer create-project --prefer-dist laravel/laravel blog

	Servidor de Desenvolvimento Local
	
	Se você tem o PHP instalado localmente e gostaria de utilizar o servidor de desenvolvimento embutido do PHP para servir sua aplicação, você deve
	usar o comando Artisan serve. Este comando irá iniciar o servidor de desenvolvimento em http://localhost:8000:

	php artisan serve

	Claro, opções mais robusta de desenvolvimento local estão disponíveis via Homestead e Valet.

	Configuração

	Diretório Public

	Depois de instalar o Laravel, você deve configurar os documentos do servidor web / web root para ser o diretório public. O index.php serve como controlador
	frontal para todas as requisições HTTP que entram em sua aplicação.

	Arquivos de Configuração

	Todos os arquivos de configurações para o framework Laravel estão armazenados no diretório config. Cada opção é documentada, então sinta-se livre para olhar 
	atráves dos arquivos para se sentir familiar com as opções disponíveis para você.

	Permissões do Diretório

	Após intalar o Laravel, você pode necessitar configurar algumas permissões. Diretórios dentro dos arquivos storage e o bootstrap/cache devem ter permissão de
	escrita pelo servidor web ou o Laravel não irá funcionar. Se você está utilizando o Homestead virtual machine, estas permissões já devem está configuradas.

	Chaves da Aplicação

	A próximo passo que você deve fazer após instalar o Laravel é configurar sua chave de aplicação para uma string aleatória. Se você instalou o Laravel via
	Composer ou pelo instalador do Laravel, esta chave já foi configurada por você pelo comando php artisan key:generate.

	Tipicamente, está string deve ter o tamnho de 32 caracteres. A chave pode ser configurada no arquivo de ambiente .env. Se você não renomeou o arquivo 
	.env.examples para o arquivo .env, você deve fazer isto agora. Se a chave da aplicação não está configurada, sua sessão de usuário e outros dados encriptados
	não estarão seguros!

	Configuração Adicional

	Laravel não precisa de nenhuma outra configuração após a instalação. Você pode se sentir livre para começar a desenvolver. De qualquer modo, você pode querer
	rever o arquivo config/app.php e sua documentação. Ele contém várias opções, como fuso horário e local que você pode querer mudar de acordo com sua aplicação.


	Você pode querer também configurar alguns componentes adicionais do Laravel, tais como:

	* Cache
	* Database
	* Session

	# Configuração do Servidor Web

	URLs bonitas

	Apache

	Laravel inclue um arquivo public/.htaccess que é usado para prover URLs sem o index.php front controller in hte path. Antes de servir o Laravel com Apache, tenha
	certeza de habilitar o módulo mod_rewrite então o arquivo .htaccess irá ser horando pelo server.

	





	
