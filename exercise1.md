Linting:

For Java, if using a major IDE such as IntelliJ, there are a lot of built-in plugins to choose for keeping the code clean. Some examples are CheckStyle, PMD and SpotBugs.

Testing:

Java provides frameworks for testing, like JUnit for unit testing. Also for mock testing, a popular framework exists in the Java ecosystem called Mockito.

Building:

For Java there are tools for building and structuring code. One example is Maven, which can compile a Java application to various different forms. Maven also deals with dependency management, cutting out a lot of manual work dealing with all the necessary libraries yourself.

Jenkins / GitHub Actions Alternatives:

Some alternatives to use for CI/CD instead of Jenkins or GitHub Actions include GitLab CI and AWS CodePipeline. If we decided to use GitLab instead of GitHub, then GitLab CI would be convenient since it’s directly integrated with GitLab. Also, if we decided to use the AWS ecosystem for deploying and maintaining our application, then for CI/CD AWS CodePIpeLine would be a good alternative for Jenkins or GitHub Actions.

Self Hosted or Cloud-Based Environment?

Since the application is worked on by a relatively small team of six developers, I would think that a Cloud-Based Environment hosting would make more sense. But the decision would also depend on the scale of the application and our team's available resources. If the application would be very large in scale and complexity, then a self hosting option could be better.
