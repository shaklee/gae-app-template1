# Spring Boot based app template

This is an app template for building a [Spring Boot][spring-boot] application on [Google
Cloud Platform][cloud-java]. It uses the [Google App Engine flexible
environment][App Engine-flexible].

[App Engine-flexible]: https://cloud.google.com/appengine/docs/flexible/
[cloud-java]: https://cloud.google.com/java/
[spring-boot]: http://projects.spring.io/spring-boot/


## Setup

Follow [original project][original-project].

[original-project]: https://github.com/GoogleCloudPlatform/getting-started-java/tree/master/helloworld-springboot

## Run the application locally

1. Set the correct Cloud SDK project via `gcloud config set project
   YOUR_PROJECT` to the ID of your application.
1. Run `mvn spring-boot:run`
1. Visit http://localhost:8080


## Deploy to App Engine flexible environment

1. `mvn appengine:deploy`
1. Visit `http://YOUR_PROJECT.appspot.com`.

