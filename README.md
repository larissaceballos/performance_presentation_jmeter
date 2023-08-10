# Introdução
Repositório contendo script de teste de performance no Jmeter para apresentação

# Itens necessários 
1. Instalar Jmeter (https://jmeter.apache.org/download_jmeter.cgi)
2. Instalar Java (https://www.java.com/pt-BR/download/ie_manual.jsp?locale=pt_BR)
3. Possuir plugin no Jmeter referente ao Ultimate Thread Group (https://jmeter-plugins.org/wiki/ConcurrencyThreadGroup/)
 
# Execução Jmeter
Abaixo segue comandos para execução dos testes através do CMD 

Windows
./jmeter.bat -n -t /local/do/script.jmx -l log.csv

Linux e MacOS
./jmeter -n -t /local/do/script.jmx -l log.csv