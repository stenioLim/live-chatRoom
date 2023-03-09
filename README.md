# Sala de chat ao vivo / PT-BR 
(Usando Flask e SocketlO)

 
Desenvolvi um pequeno projeto de uma sala de chat ao vivo usando Python, seu framework Flask e Flask socketio, e usamos também HTML, Css e um pouco de Java Script. 

Esse mini projeto funciona como um chat de WhatsApp, 100 ao vivo onde conseguimos registrar a entrada, saída , hora que a mensagem foi enviada e ainda conseguimos guarda ao histórico das mensagens. 

Também conta com uma pagina inicial onde fazemos a verificação se os campos foram preenchido, também geramos uma nova sala usando um um loop para gerar novos códigos de sala e também usando para verificar se aquela sala selecionada já existe ou não. Assim a pessoa pode fazer o acesso caso deseje. 

Usamos o metodo *route* para fazer o processo de configuração e inicialização das paginas referente dentro de *tampletes* que fora desenvolvida em HTML usando um arquivo base. O CSS bastante simples pois o foco central foi a parte de funcionamento de todo o sistema e usamos um pouco de JS para poder criar o push da mensagem e também alinhar a hora e data do envio da mesma. 

Usando o socketio para verificar se havia algum usuário ou não na sala e se alguém entrou ou saiu da sala, também criamos uma função para identificar quem havia entrado na sala e qual sala de referencia direto em nosso servido, assim podendo ter um controle geral da aplicação back-end. 


## Live Chat Rom / EN 
(Using Flask and SocketIO ) 

Live chat room / PT-BR
(Using Flask &amp; SocketlO)

 
I developed a small project of a live chat room using Python, its Flask framework and Flask socketio, and we also used HTML, CSS and a little bit of Java Script.

This mini project works like a WhatsApp chat, 100 live where we can record the entry, exit, time the message was sent and we still manage to keep the message history.

It also has an initial page where we check if the fields have been filled in, we also generate a new room using a loop to generate new room codes and also using it to check if that selected room already exists or not. So people can access it if they want.

We use the *route* method to carry out the process of configuring and initializing the referring pages within *tampletes* that were developed in HTML using a base file. The CSS is quite simple because the central focus was the functioning part of the entire system and we used a little JS to be able to create the message push and also align the time and date of sending it.

Using socketio to check if there were any users in the room or not and if someone entered or left the room, we also created a function to identify who had entered the room and which room was referred directly to our server, thus being able to have a general control of the backend application.
