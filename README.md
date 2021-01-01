## grpc-learning
Learning gRPC by building sample application.

## sample-application
Sample implementation using Unary , Server Streaming, Client Streaming, Bi-directional Streaming.

## sample-application
Sample Blogging application using gRPC.

## Building and running locally
In order to run this project locally, you will need the following installed
- Java Development Kit (JDK; has been tested with openjdk 11 and 13)

Once the configuration in `src/main/resources/application.properties` is updated to the desired setup needed, run
`./gradlew clean build`
to build. If the build is successful, a JAR file should be created in the `build/libs` directory. It can be run using
`java -jar build/libs/grpc-learning.jar`

