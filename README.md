# How to Deploy

For a complete guide, check out our [docs](https://docs.porter.run/language-specific-guides/fastapi).

## Create an account on Porter

Unlike other PaaS options, Porter deploys your applications to your own AWS account. Before deploying a FastAPI application you must set up your infrastructure on AWS first.

First, create an account on [Porter](https://dashboard.getporter.dev). Follow [this guide](https://docs.porter.run/standard/getting-started/deploy-overview) to create the necessary infrastructure on AWS.

## Deploying from the dashboard
Once your infrastructure has been provisioned on AWS, you can start deploying your FastAPI application. Take a look here for a more [detailed guide](https://docs.porter.run/standard/getting-started/deploy-overview).

1. Create a New Application on Porter.
2. Select the Git repository you have forked from the example repo.
3. Add a Web service to the application. There is no need to add a start command, because the `Dockerfile` in the example repository already has a command specified.
4. Click Deploy.

That's it! You should be able to see your FastAPI server on a Porter URL that ends with `onporter.run`. Verify that the application has been deployed by going to the `/docs` page on your application, which will show the auto-generated docs as below:
