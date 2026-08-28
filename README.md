# Descrição de Projeto

Júlia Rodrigues 3DS - CRUD Mundo <br>
Projeto das disciplinas de PAM e PW, para um sistema de gerenciamento de países e suas cidades usando o CRUD.

### Sistema Web
- Tecnologias usadas: HTML, CSS, PHP, MySQL
- É composto de uma tela inicial com botões para as páginas de criação de cidades e paises, e seus gerenciamentos.
- Nas páginas de gerenciamentos de cidades e países, é possível visualizar todos por uma tabela, fazendo a edição de suas informações, e remoção; assim como ir pra página de adição.
- Uso da API REST Countries, para informações adicionais (moeda e bandeira) da maior parte dos países (apenas os já existentes no banco de dados, e que não tenham o nome composto por mais de duas palavras).

#### Como rodar a aplicação web
1. Garanta que você tem o Xampp instalado na sua máquina, e inicie o Apache dele (que é o servidor do PHP)
2. Baixe o repositório e mova ele para a pasta `C:\xampp\htdocs\`.
3. Abra no navegador a url `localhost/<nome-da-pasta>/PW/index.php`, e pronto!

### Sistema Mobile
- Tecnologias usadas: JavaScript, PostgreeSQL
- Design parecido do sistema web, mas compacto, para celular.
- Usa o PostgreeSQL como substituto do MySQL, mas com a mesma base de dados.
- Telas de criação, gerenciamento, edição e remoção de cidades e países.



