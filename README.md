# Built-It-Bigger
As Android projects grow in complexity, it becomes necessary to customize the behavior of the Gradle build tool, allowing automation of repetitive tasks. Particularly, factoring functionality into libraries and creating product flavors allow for much bigger projects with minimal added complexity.

this project contains 4 modules :-
A Java library that provides jokes.
A Google Cloud Endpoints (GCE) project that serves those jokes.
An Android Library containing an activity for displaying jokes.
An Android app that fetches jokes from the GCE module and passes them to the Android Library for display.


App Features:-
Add free and paid flavors to an app, and set up your build to share code between them
Factor reusable functionality into a Java library
Factor reusable Android functionality into an Android library
Configure a multi-project build to compile your libraries and app
Use the Gradle App Engine plugin to deploy a backend
Configure an integration test suite that runs against the local App Engine development server
