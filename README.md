# CST8915- LAB3 Akash Nadackanal Vinod

## Reflection Questions

1. What challenges did you encounter when configuring environment variables in the GitHub Actions workflow?

*I had trouble setting up environment variables in GitHub Actions because I had made the error of not activating the necessary permissions for OIDC tokens. Because I forgot to specify permissions: id-token:, the error "Unable to get ACTIONS_ID_TOKEN_REQUEST_URL" appeared. I came to understand from this that even minor configuration errors can affect operations, making it important to properly set up permissions while understanding the range of environment variables.*

2. How does deploying microservices on Azure Web App Service differ from running them locally?

*When deploying microservices on Azure Web App Service, configurations and credentials are transferred from the local.env to App Settings/Key Vault, while Azure manages security, load balancing, and scaling. Apps become stateless and prepared for the cloud when services utilize DNS endpoints rather than localhost, logs are sent to Azure Monitor, and deployments depend on CI/CD pipelines.*

3. Why is it important to use environment variables for configurations in a cloud environment?

*In a cloud setup, environment variables are essential because they protect sensitive information from the codebase, such as tokens, database passwords, and API credentials, increasing the security of apps. Additionally, they facilitate scaling across many instances where each container or service may access the same variables, support configuration changes between environments (dev, test, and prod) without requiring code modifications, and are in line with cloud best practices for developing stateless, portable projects.*

## Store-Front
https://github.com/nada0038/store-front-Lab2

## Product-Service
https://github.com/nada0038/LAB3-Product-Service-Python

## Order-Service
https://github.com/nada0038/order-service-Lab2

## Youtube Link
https://youtu.be/3KUXpWvoFuk 
