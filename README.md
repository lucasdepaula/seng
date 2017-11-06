# Site para Semana de Engenharia da UFRJ

Esse repositório contém os arquivos necessários para colocar o site da SEng no ar.


## Passo a passo

Abaixo o passo a passo para configuração.


### Banco de Dados
1. Ter um servidor, um usuario e senha de banco de dados. Criar também um banco, cujo usuário tenha todos os privilégios (leitura/escrita).
2. Definir a URL do site. URL Recomendada: http://caeng.poli.ufrj.br/seng/ 
3. Abrir o arquivo "loader.sql" localizado na pasta "data".
4. Localizar (CTRL+F) todas as ocorrências de texto "http://seng.lucasnaweb.com.br/seng/" e alterar para a URL definida no passo 2.
5. Carregar o arquivo loader.sql no banco de dados.

### Arquivos
6. Carregar os arquivos localizados dentro da pasta *www* para o caminho em questão especificado na URL do site no passo 2. (Obs: caso a sugestão seja seguida, basta criar uma pasta chamada *seng* dentro da raíz da página do CAENG, e então colocar os arquivos dentro.)
7. Abrir o arquivo *wp-config.php* e preencher os campos *DB_NAME*, *DB_HOST*, *DB_USER* e *DB_PASSWORD* com os dados do item 1.
