# AWS Lambdas: what are they?

The idea is: you want some code to run in response to something. A good example is a website, which runs certain code in response to requests being sent to certain ports of certain servers. 

What sucks though, is having to maintain a server. and all the complexity that this entails 24/7. 

AWS lambdas lets you send code to AWS in lambda form and specify a triggering action, like a request to a certain url which starts the code. Then whenever the triggering action occurs, AWS will run your code. Simple as that. 

Well, not really, there's more things you can optionally specify and a lot going on behind the scenes that is worth understanding. 

## Behind the scenes