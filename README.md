# OminiCode-Vortex-Manifests
This repository contains Kubernetes deployment manifests for various services that are part of the OmniCode Vortex project. The manifests define the configuration and deployment details for key services within the Vortex infrastructure, enabling a scalable and easily managed microservices architecture.

Repository Structure

auth-service-deployment.yaml: Contains the deployment configuration for the Authentication Service, responsible for user authentication and authorization within the Vortex system.
discovery-server-deployment.yaml: Defines the deployment setup for the Discovery Server, which helps in service discovery and registration.
gateway-service-deployment.yaml: Configuration for the API Gateway Service, responsible for routing requests to various backend services and acting as a central entry point.
marketplace-service-deployment.yaml: Manages the deployment of the Marketplace Service, handling product listings and transactions for the marketplace feature.
notification-service-deployment.yaml: Specifies the deployment details for the Notification Service, which manages real-time notifications for users.
post-service-deployment.yaml: Deployment manifest for the Post Service, which handles creating, updating, and managing user posts.

Branch Information
main: The primary branch containing stable manifests.
DevOps: The branch used for active development and updates related to infrastructure and deployment configurations.

Usage
To deploy these services in your Kubernetes cluster, follow these steps:

1. Clone the Repository
   git clone https://github.com/scpmWijesiriwardhana/OminiCode-Vortex-Manifests.git
cd OminiCode-Vortex-Manifests
2. Apply the Manifests

Ensure your kubectl is configured to communicate with your Kubernetes cluster.
Apply each service manifest using
kubectl apply -f <service-deployment-file.yaml>

Prerequisites
A running Kubernetes cluster.
kubectl configured to interact with your cluster.
Proper configuration and secrets set in the cluster for secure communication between services.
