#Projeto AjudaFEI
O Projeto AjudaFEI visa criar um sistema de auxilio a alunos do centro universitario da FEI a partir da criação de meios que facilite a organização e troca de conhecimento. O sistema será divido em três partes: fórum, sistema para marcar aulas e um sistema para a divulgação de pesquisas. O projeto será desenvolvido utilizando a ferramenta [Wordpress](https://br.wordpress.com  "Wordpress"), o tema [MesoColumn](https://wordpress.org/themes/mesocolumn/  "MesoColumn"), o plugin [BBPress](https://bbpress.org  "BBPress") e algumas adpatações implementadas pela nossa equipe de desenvolvimento.
##Instalando
Siga os seguintes passos para instalar o projeto:

* Clonar o repositório do AjudaFEI

		git clone https://github.com/egrassl/ajudafei.git

* Checar se o banco de dados está corretamente configurado no arquivo `wpconfig.php` da pasta raíz, deve-se conter as seguintes linhas

		define('DB_NAME', 'ajudafei');
		define('DB_USER', 'root');
		define('DB_PASSWORD', 'root');
		define('DB_HOST', 'localhost');

##Recomendações

* Utilizar [Sublime Text 3](https://www.sublimetext.com/3  "Sublime Text 3") para a edição de arquivos

* Saber o básico de [html, css3, javascript, php](http://www.w3schools.com  "w3schools") e [Wordpress](https://codex.wordpress.org  "Wordpress Codex")