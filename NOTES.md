The Rails _router_ sits in front of the controller (the Application Controller),
and determines where to send requests that come from the browser. "sits in
front" means, "executes before". That is, the router executes before any
controller is executed. Since the controller that is first executed is the
Application Controller, the router executes before the Application Controller.

Source: https://www.railstutorial.org/book/beginning#sec-hello_world