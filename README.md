# ESTUDO SOBRE ORIENTAÇÃO A OBJETOS EM LINGUAGEM DE PROGRAMAÇÃO PHP

## DESCRIÇÃO:
Este é um projeto simples de conta bancária desenvolvido em PHP. Ele permite a criação de conta corrente e conta poupança através de um cadastro com nome e cpf ou cnpj em pessoa física ou pessoa jurídica respectivamente. A conta bancária recebe usuário como parâmentro e permite as operações de depósitos, transferência e verificação de saldo.
O sistema também conta com a classe histórico que instancia o tipo de transação: depósito, saque e transferência.
também conta com as classes logger e extrato.

## ESTRUTURA DO PROJETO:
<img src="img_project/project.png" alt="Imagem da Estrutura do Projeto.">

## FERRAMENTAS UTILIZADAS:
* Linguagem de programação PHP.
* Composer(gerenciador de dependências PHP)
* Stack Xampp(Servidor Apacha).
* Git/GitHub
* Visual studio code.
* Windows 10.

## MODO DE UTILIZAR:
* Instalar o gerenciador de dependências do Php: Composer. Link: https://getcomposer.org/download/
* Clonar o repositório para o diretório 'C:\xampp\htdocs\', que é o diretório padrão da instalação. No meu caso 'C:\xampp\htdocs\projetos\', porque prefiro criar um diretório dentro de 'htdocs\'. 
* Entrar no diretório do projeto: ```cd bank-php```.
* Na raiz do projeto executar o comando ```composer install``` para instalar os arquivos do diretório 'vendor' e as dependências. Caso precise, ```composer update``` para atualizar as dependências.
* Instalar/executar Stack XAMPP: acessar a raiz da Stack e executar o arquivo ```xampp-control.exe```, após isso, inicializar o servidor Apache. Também é possível usar os servidores Nginx, Wamp ou, no caso do sistema operacional 
linux, o Lamp.
* Em um navegador de sua preferência use ```localhost/bank-php/index.php```. No meu caso ```localhost/projetos/bank-php/index.php```.

## TESTES:
* Testes unitários com PHPUnit. Para execultar os testes: ```vendor\bin\phpunit tests```. 
* Teste de análise estática com PHPStan. Para execultar o teste: ```vendor\bin\phpstan analyse src tests```.            
* Corrige todo o estilo do código, quebras, espaços, estilo de declarações etc. Para execultar: ```vendor\bin\php-cs-fixer fix src --rules=@PSR2 --allow-risky yes```.

## CONTRIBUIÇÃO:
Se quiser contribuir para este projeto, fique à vontade para enviar um pull request ou relatar problemas na seção de issues.

## LICENÇA:
Este projeto é licenciado sob a Licença MIT.


