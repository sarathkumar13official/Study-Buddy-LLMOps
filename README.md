# Study Buddy AIOps

A modern AI-powered study assistant built with LangChain, Groq API, Docker, Minikube, Jenkins, ArgoCD, and GCP.

## Architecture Flow
Project and API Setup → Configuration Code → Question Schemas Models Code → Prompt Templates Code → Groq Client Setup Code → Question Generator Code → Helper Class Codes

## What each step does
- **Project and API Setup** → Sets up the base application structure and API entry points.
- **Configuration Code** → Manages environment variables, app settings, and service configuration.
- **Question Schemas Models Code** → Defines structured data models for input and output validation.
- **Prompt Templates Code** → Stores reusable prompt patterns for the AI workflow.
- **Groq Client Setup Code** → Connects the app to Groq for model inference.
- **Question Generator Code** → Builds the logic that produces AI-generated questions.
- **Helper Class Codes** → Contains utility classes used across the application.

## CI/CD Pipeline Flow
Jenkins Setup → GitHub Integration with Jenkins → Build and Push Docker Image → ArgoCD Setup → WebHooks GitHub

### Explanation
- **Jenkins Setup** → Installs and configures Jenkins for pipeline execution.
- **GitHub Integration with Jenkins** → Connects GitHub repo to Jenkins using credentials and webhooks.
- **Build and Push Docker Image** → Builds the Docker image and pushes it to Docker Hub.
- **ArgoCD Setup** → Syncs Kubernetes deployment from GitHub using GitOps.
- **WebHooks GitHub** → Triggers pipeline automatically when code is pushed.
