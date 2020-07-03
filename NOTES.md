The Rails _router_ sits in front of the controller (the Application Controller),
and determines where to send requests that come from the browser. "sits in
front" means, "executes before". That is, the router executes before any
controller is executed. Since the controller that is first executed is the
Application Controller, the router executes before the Application Controller.

Source: https://www.railstutorial.org/book/beginning#sec-hello_world

---

Deploying Rails applications used to be a pain, but the Rails deployment
ecosystem has matured rapidly in the past few years, and now there are several
great options. These include shared hosts or virtual private servers running
[Phusion Passenger] (a module for the Apache and Nginx27 webservers),
full-service deployment companies such as [Engine Yard] and [Rails Machine], and
cloud deployment services such as [Engine Yard Cloud] and [Heroku].

[Phusion Passenger]: https://www.phusionpassenger.com/ [Engine Yard]:
https://www.engineyard.com/ [Rails Machine]: https://railsmachine.com/ [Engine
Yard Cloud]: https://www.engineyard.com/features [Heroku]:
https://www.heroku.com/

Source: https://www.railstutorial.org/book/beginning#sec-deploying
