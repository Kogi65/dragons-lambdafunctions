# Dragons 🐉
This repository contains Lambda invoking function codes for Dragons WebApp.
- ListDragons ->  Invokes API Gateway to obtain the list of Dragons in S3 bucket using GET method.
- ValidateDragons -> A task state in Step Functions which checks if a dragon already exists in the list or a new dragon is spotted.
- AddDragons -> A task state in Step Fuctions which adds new dagons spotted in our list and sends an SMS using Simple Notification Service (SNS).
## Other Files
Gradle builds for AWS Java SDK dependencies & Sample .JSON paylods for ValidateDragons and AddDragons.

[Invoke URL](https://k-javaproj.s3.amazonaws.com/dragonsapp/index.html)
