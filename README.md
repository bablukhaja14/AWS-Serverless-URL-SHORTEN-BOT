OBJECTIVE: A Telegram Bot to convert long URLs to Short URLs Using AWS Serverless Services.

What is Serverless?

Serverless is a cloud-native development model that refers to serverless applications. Serverless applications are ones that don’t need any server provision and do not require managing servers.

Services Used for Fabricating:

1)AWS Lambda

2)AWS API Gateway

3)AWS Cloud Watch

4)Clean Uri Api

Architecture:


![image](https://github.com/bablukhaja14/AWS-Serverless-URL-SHORTEN-BOT/assets/82576550/302a8256-9691-4ef6-a303-6fffe38a7b67)



Architectural Flow:

If the user Enters a very long URL then you need to return a very short URL, you can use this specific CleanUri API. You would call this API using Python code that is running in Lambda, then shorten the user-shared URL. Once you receive the response, you would push it from Lambda to our Telegram server, where the user could obtain the short format of the URL.
