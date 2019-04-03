# Using a database

In this lesson we will be covering how to use a database persistence layer with your functions.

- [Lesson Steps](#lesson-steps)
- [Complete code](#complete-code)
- [Additional Resources](#additional-resources)

## Lesson Steps

1. Create a `netlify.toml` file in your project.

    The `netlify.toml` file is where we configure how the site builds and where your serverless functions live.

2. In `netlify.toml`, add a `[build]` section and add `publish = "site"` and `functions = "functions"` values

3. We need to create this site in Netlify

    Open your terminal and run the following command:

    ```bash
    netlify init
    ```

    Choose manual deployments

4. Choose the database type you would like to use

    There are a number of examples in this lesson. See the functions folder for all of them.

    Choose the database you want to work with

4. Now deploy the function

    Open your terminal and run the following command:

    ```bash
    netlify deploy -p
    ```





## Complete code

If you need help or get stuck refer to the completed code of this lesson

[View Complete Code](https://github.com/DavidWells/netlify-functions-workshop/tree/master/lessons-code-complete/core-concepts/6-using-a-database)


## Additional Resources

- [Reuse SQL Database Connections in AWS Lambda](https://www.jeremydaly.com/reuse-database-connections-aws-lambda/)