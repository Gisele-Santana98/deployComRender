# deploy

## Variáveis de ambiente:

JDBC_DATABASE_URL: jdbc:postgresql://DB_HOST.oregon-postgres.render.com:5432/DB_NAME?sslmode=require

DB_USERNAME:
DB_PASSWORD:

jdbc:postgresql://USUARIO:SENHA@HOST:PORTA/NOME_BANCO


ORIGINAL
postgresql://db_tcc_4rqy_user:agF6XEI16SSm7nhvyrrKwWUeg1YgwLgs@dpg-d0otkhre5dus73d8q850-a.oregon-postgres.render.com/db_tcc_4rqy

Para deixar a senha url correta faz as devidas modificações:

jdbc:No inicio
db_tcc_4rqy_user:agF6XEI16SSm7nhvyrrKwWUeg1YgwLgs@ : Apaga
:5432 : Isere o numero da Porta
?sslmode=require: Insere no fim

jdbc:postgresql://dpg-d0otkhre5dus73d8q850-a.oregon-postgres.render.com:5432/db_tcc_4rqy?sslmode=require


Ctrl + Enter = dar commit.add

