Projeto de Instalação do GLPI
Este projeto tem como objetivo automatizar a instalação do GLPI em um servidor Ubuntu utilizando um script bash. O script realiza todas as etapas necessárias para a instalação do GLPI, incluindo a instalação de dependências, configuração do servidor web Apache, banco de dados MariaDB, e ajuste de permissões.

Autor
Flávio Silva | OPROFESSOR

Data de Criação
29/07/2024

Funcionalidades
Busca a última versão do GLPI disponível no GitHub.
Adiciona repositórios necessários.
Atualiza e instala pacotes necessários (Apache2, PHP, MariaDB e extensões do PHP).
Baixa e descompacta a última versão do GLPI na pasta /var/www/html/.
Ajusta permissões dos arquivos e pastas do GLPI.
Cria e configura banco de dados e usuário no MariaDB.
Instala o GLPI via CLI.
Habilita e reinicia o Apache2.
Como Usar
Baixar e Executar o Script:

Faça o download do script e execute-o com permissões de superusuário:

bash
Copiar código
chmod +x install_glpi.sh
sudo ./install_glpi.sh
Configurações do Banco de Dados:

Durante a execução, será solicitado que você informe se deseja usar as configurações padrão do banco de dados ou personalizar as configurações. As configurações padrão são:

Nome do Banco de Dados: glpidb
Usuário do Banco de Dados: glpi
Senha do Usuário do Banco de Dados: glpi123
Caso escolha personalizar, você poderá definir o nome do banco de dados, o usuário e a senha.

Acesso ao GLPI
Após a conclusão da instalação, você pode acessar o GLPI utilizando as seguintes credenciais padrão:

Usuário: glpi
Senha: glpi
Licença
Este projeto é distribuído sob a licença MIT. Para mais detalhes, consulte o arquivo LICENSE.

Contato
Para dúvidas ou sugestões, entre em contato com Flávio Silva através do e-mail: pentestsystem@gmail.com.

Este projeto foi desenvolvido com o suporte do ChatGPT.
