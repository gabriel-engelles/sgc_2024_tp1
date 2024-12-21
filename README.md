# Projeto SGC 2024 TP1

Este projeto tem como objetivo configurar uma instalação do WordPress no diretório `sgc_2024_tp1`, criar uma base de dados associada, e organizar a estrutura para submissão conforme as diretrizes fornecidas.

## Configuração do Ambiente

1. **Instalação do WordPress**
   - O WordPress foi instalado no diretório `sgc_2024_tp1`.
   - Configuração realizada no arquivo `wp-config.php` com as seguintes credenciais:
     - **Nome da Base de Dados**: `sgc_2024_tp1`
     - **Usuário da Base de Dados**: `sgc_2024_tp1`
     - **Senha**: `sgc_2024_tp1`
     - **Host**: `localhost`

2. **Base de Dados**
   - Uma base de dados chamada `sgc_2024_tp1` foi criada.
   - Usuário `sgc_2024_tp1` com privilégios completos em `sgc_2024_tp1.*`.

3. **Servidor Local**
   - A aplicação está configurada para ser acessada via [http://localhost/sgc_2024_tp1](http://localhost/sgc_2024_tp1).

## Estrutura para Submissão

O arquivo submetido segue a seguinte estrutura:

```
sgc_2024_tp1/
    |
    \database_sgc_2024_tp1.sql.zip
    |   |
    |   \database_sgc_2024_tp1.sql
    |
    \wordpress_sgc_2024_tp1.zip
        |
        \wordpress_sgc_2024_tp1/
```

### Conteúdo

- **`database_sgc_2024_tp1.sql.zip`**: Contém o dump da base de dados.
- **`wordpress_sgc_2024_tp1.zip`**: Contém os arquivos do WordPress instalados e configurados.

## Como Executar o Projeto

1. Extraia os arquivos do WordPress:
   ```bash
   unzip wordpress_sgc_2024_tp1.zip
   ```

2. Configure a base de dados:
   - Importe o arquivo `database_sgc_2024_tp1.sql` para o MySQL:
     ```bash
     mysql -u <usuario> -p < database_sgc_2024_tp1.sql
     ```

3. Certifique-se de que o servidor local está configurado e acessível pelo caminho `/sgc_2024_tp1`.

4. Acesse [http://localhost/sgc_2024_tp1](http://localhost/sgc_2024_tp1) para visualizar o projeto.

## Informações Adicionais

- O projeto foi testado em ambiente WSL Ubuntu.
- Certifique-se de que os serviços MySQL e Apache/Nginx estão configurados corretamente.

---

**Autor:**  
www.linkedin.com/in/gabriel-engelles
