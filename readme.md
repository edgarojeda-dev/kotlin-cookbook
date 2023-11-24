# Kotlin cookbook

This repository contains easy code projects to help you learn Kotlin.

Current projects:

* Hello world

## How to run a project

### Run a single file project

  1. Compile the application using the kotlin compiler. This will result in a self-contained **.jar** file.

        ```console
        kotlinc hello-world.kt -include-runtime -d hello-world.jar
        ```

  2. Execute the **.jar** file.  

        ```console
        java -jar hello-world.jar
        ```
