# Desafio Backend Uber
Solução do desafio da Uber, sendo o de criar um Email Service utilizando Java e AWS SES

**Observação:** Maior parte do conteúdo foi retirado do [vídeo da Fernanda Kipper](https://youtu.be/eFgeO9M9lLw), 
que estou utilizando para meus estudos de arquitetura limpa e microserviços com Java.

# Descrição do desafio
Crie um serviço que aceita as informações necessárias e envia emails. Ela
deve prover uma abstração entre dois serviços diferentes de provedores de email.
Se um deles cair, o seu serviço deve rapidamente tolerar a queda e mudar para um diferente
provedor sem afetar seus clientes. 

Exemplos de Provedores de Email:

* [SendGrid](https://sendgrid.com/user/signup) - [Simple Send Documentation](https://sendgrid.com/docs/API_Reference/Web_API/mail.html)
* [Mailgun](http://www.mailgun.com) - [Simple Send Documentation](http://documentation.mailgun.com/quickstart.html#sending-messages)
* [SparkPost](https://www.sparkpost.com/) - [Developer Hub](https://developers.sparkpost.com/)
* [Amazon SES](http://aws.amazon.com/ses/) - [Simple Send Documentation](http://docs.aws.amazon.com/ses/latest/APIReference/API_SendEmail.html)

Todos os serviços listados são grátis para testar e muito simples de se cadastrar, então, 
por favor registre suas próprias contas de teste em cada um deles.
