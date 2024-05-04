## About
This project aims to implement a backend server for a WhatsApp-like application. The focus is on implementing chatting-related features, such as user profiles, chatrooms, and messaging functionalities.

**RestAPI** that can send and receive Whatsapp messages through **_[WhatsappAPI](https://chat-api.com/)_**, a _Whatsapp API gateway_.

> _This project's purpose's to demonstrate some of my Java spring boot skills._

## Features

- My Profile Feature: Users should be able to view and manage their profile information.
- Chatroom Feature: Users should be able to create and join chatrooms for group conversations.
- Message Feature:
   - Users should be able to send text messages.
   - Users should be able to send attachments, with a size limit of 10MB. Attachments should be saved in the local server directory (root/picture for images, root/video for videos).
- Response Emoji Feature:
   - Users should be able to respond to messages with emojis, including "thumbup", "love", "crying", and "surprised".

## Some of the technologies I used on this project:
- The project should utilize the Spring Framework for backend development.
- Object-Relational Mapping (ORM) should be used for database interaction.
- The project should include a well-defined Relational Database (RDB) schema.

### [Backend](https://github.com/julian-cabrera/java-whatsapp-demo)

- Java 8
  - Spring Boot
    - Spring Web
    - Spring Data
    - OpenAPI (Swagger)
  - Maven
  - Wildfly
  - Hibernate
  - Lombok
- SQL Server

- [Ngrok](https://ngrok.com/docs)
  (exposes a local web server to the internet so I can receive data from ChatAPI. Also, it lets you inspect HTTP traffic)
  <br />
## Situation Condition
  The project does not require an elaborate login process. Implement a simple user/login process.
## Deployment 
  - Deploy the server with a Swagger tester that allows testing of APIs. Utilize a free deployment service for hosting.
  - API Documentation: Provide API documentation in any suitable format, such as Swagger, Markdown, etc.


<br />
