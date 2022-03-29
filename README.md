# ChatRMI
Chat construído com a tecnologia RMI
By Genilto Vanzin - https://genilto.com

Construido para fins acadêmicos, ChatRMI trata-se de 
um chat em rede construído com a tecnologia JAVA RMI.

# CONFIGURAÇÃO
Esta release é um projeto do Netbeans.
Faça o clone do repositório e a abra o projeto no Netbeans.

# COMO FUNCIONA
Execute o programa pelo Netbeans, ou usando o build já feito em dist/ através do comando:

```
java -jar "dist/ChatRMI.jar" 
```

Após abrir a aplicação, em um computador você deverá ir na opção Servidor -> Iniciar Servidor, escolha a porta desejada e clique em OK.

Em outro computador, vá em Cliente -> Conectar, informe o IP do computador onde o servidor foi iniciado.

Vários clientes poderão conectar em um servidor, e os usuários conectados aparecerão na lista de usuários.

Mensagens enviadas serão vistas por todos.
