# Kubernetes_config

In this example, we're creating a Service object to expose the Java application container to external traffic, and a Deployment object to manage the deployment of the container.

To use this YAML file, you'll need to replace my-registry/my-java-app with the name of your Docker image. 

Now to deploy the YAML file using the following command:

kubectl apply -f config.yaml

This will deploy the Java application container to your Kubernetes cluster. You can access the application by using the external IP address of the Service object that was created. In this example, the application is exposed on port 8080.
