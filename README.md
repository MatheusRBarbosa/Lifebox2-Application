# Lifebox2-Application

Os códigos fontes podem ser encontrados em :
- Desktop : https://github.com/MatheusRBarbosa/lifebox2srcApp
- Web : https://github.com/MatheusRBarbosa/lifebox2srcWeb

## Instalação
<br>**Apenas da Windows 64**<br>
- Baixe as duas pastas
- Na pasta "Desktop" você encontrará um arquivo chamado "rxtxSerial.dll", coloque esse arquivo dentro da pasta **jre/bin** do seu java
- Pronto, instalado !

## Usando
- Primeiro, execute o arquivo "usbwebserver.exe" e espere os dois icones verder aparecerem<br>
![Exemplo](https://image.prntscr.com/image/otuaCcmMS92VP6FvxemtXQ.png)<br>
- Clique na aba "general" e aparecerá 4 botões, 3 deles são importantes
  - Root dir: Abre a a pasta root que contém o código fonte
  - Localhost: Abre em seu navegador sua aplicação
  - PHPMYAdmin : Abre em seu navegador o banco de dados
  <br>
- Para fazer conexão com o arduino é preciso usar o aplicativo desktop feito em java
- Execute o arquivo Lifebox2app.jar<br>
![Exemplo 2](https://image.prntscr.com/image/fU78qF1UTQGkMM-MaeJLpw.png)<br>
- No dropdown irá aparecer todas as portas COM que estão sendo usadas em sua maquina, selecione a que for do arduino e clique em "conectar"
- Em "indentificação" é o espaço para se dar o nome do teste
- Quando se clica em "Iniciar Registro" os valores de temperatura junto com a identificação serão registrados no banco de dados
*Por isso se deve abrir primeiro o servidor local e depois o app desktop*
