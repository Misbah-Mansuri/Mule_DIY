# Mule_DIY

This is mulesoft DIY project directory.
In this you will find how to create design specification in raml.
Implimentation of API, Upload API on cloud hub.
Create proxy of API.
Call external API in anypoint studio with synchronous HTTP Request component and asynchronous VM Consume component.
Consume API from exchange.


Please find links below.

Implementation URL:
http://localhost:8081/api/accounts

http://localhost:8081/api/accounts/4001

http://localhost:8081/api/accounts?account_name=Mat Siva

http://localhost:8081/api/accounts?account_type=business


Url after deploying to cloudhub
http://customer-accounts-ws-misbahm.us-e2.cloudhub.io/accounts

http://customer-accounts-ws-misbahm.us-e2.cloudhub.io:80/accounts?account_name=Rajesh Patil

http://customer-accounts-ws-misbahm.us-e2.cloudhub.io:80/accounts?account_type=business


Url for outbound calls 
http://localhost:8081/customers

http://localhost:8081/customers?account_type=personal

http://localhost:8081/customers?account_name=Mat Siva


Anypoint Exchabge public portal URL

https://anypoint.mulesoft.com/exchange/portals/njc-986/7a018d89-2195-48e0-81d2-5c53ee32994e/accounts-api/

client_id: 889ac90d52b94fc6a995d7a410fa0e15
client_secret: C8661561a4D943eBac36B04A5Afad48E
user_id:1


Error handling URLs
http://localhost:8081/api/accounts/440

http://localhost:8081/api/accounts/4400

http://localhost:8081/customers?account_type=business&condition=OR&account_name=Mat Siva

http://localhost:8081/customers?account_type=business&condition=AND&account_name=Mat Siva

http://localhost:8081/customers?account_type=business&condition=ABC

http://localhost:8081/customers?account_type=group&condition=OR


