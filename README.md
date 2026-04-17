# Exercício 7 – Servidor HTTPS

## Comando utilizado:

python3 -m http.server 8443 --bind 0.0.0.0

## Explicação:

Foi iniciado um servidor local na porta 8443.

Ao acessar utilizando HTTPS, o navegador apresentou erro de segurança, pois o servidor não possui um certificado digital válido configurado.

Isso demonstra a importância do uso de certificados digitais em conexões seguras.

## Evidência:

![Print](print7.1.png)
