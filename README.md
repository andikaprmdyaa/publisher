## Preparing The Subscriber

### a. How many data your publlsher program will send to the message broker in one run? 

    The publisher program will send five data items to the message broker in one run. This can be inferred from the five calls to the publish_event function within the main function, each sending a UserCreatedEventMessage to the message broker.

### b. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?

    The URL "amqp://guest:guest@localhost:5672" is commonly used to connect to a RabbitMQ message broker running on the local machine with default guest credentials. In both the publisher and subscriber programs, this URL is used to connect to the same RabbitMQ broker instance. This means that both the publisher and subscriber programs are configured to communicate with the same message broker instance on the same machine using the same credentials. This ensures that messages published by the publisher can be received and processed by the subscriber.

## Running RabbitMQ as message broker
<img src="assets/images/rabbit1.png" alt="Rabbit Image" width="50%" height="50%">
