# Chatbot-Resume

This chatbot-resume app is a portfolio application. It aims to show AI, Frontend and Backend knowledge.
## How it's done?
The application has two layers. The client (Frontend) and the server (Backend). Both have some specifications that will be explaind next.
### Frontend
The frontend client is made with Astro. This framework allows a very comfortable development and a faster client application. It uses Tailwind for most of the styling present in the application.

### Backend
The backend server is made with FastAPI. This framework is very comfortable for development too, and also is easy to connect with the backend technologies for AI. AI technologies include Langchain, Llama2 LLMs, Mistral LLMs and more.

## Deployment
The application is deployed using Docker. There is two main directories where the frontend and backend are developed. Each one has it's one Dockerfile. Also, there is a docker-compose file to quickly deploy both applications to production. For this, nginx-reverse-proxy is used, with Acme Companion for SSL certificates (Let's Encrypt SSL certification).
