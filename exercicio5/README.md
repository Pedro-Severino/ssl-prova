# Exercício 5 – Certificado Digital

## Comando utilizado:

openssl x509 -req -days 365 -in ~/ssl-prova/exercicio4/aluno.csr -signkey ~/ssl-prova/exercicio3/aluno.key -out aluno.crt

## Explicação:

Foi criado um certificado digital a partir do CSR e da chave privada.  
Esse certificado garante segurança e autenticação.
