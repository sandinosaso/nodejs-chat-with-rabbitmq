nodejs-chat-with-rabbitmq
=========================

An improved version of node.js chat example, with tab notifications and integration with rabbitmq

I improved basic node.js chat example, to let consume from rabbitmq queue, everytime you push a message to the queue
it is showed in the chat room, this could be used for integration the chat with another languages where you can put a message to the RabbitMQ queue and that way your message is sent to the chat room or as an admin function to send push messages to every user about notifications of changes or terms of use.

I also improve the message in the chat so when new message arrive and you are not looking at the chat tab you get notified as Gmail does. In the tab title it says Chat(0) or Chat(1) or Chat(2), that indicates the messages you have not yet read
