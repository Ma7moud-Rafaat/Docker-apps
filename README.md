# 🏢  .Net App

A **.NET 10** web application for fully containerized with Docker 🐳.

## ✨ Features
- 🖥️ Built with **ASP.NET 10**
- 🚀 Multi-stage Docker build for optimized runtime
- 📦 Runs in a Docker container, ready for deployment

## ⚙️ Prerequisites
- 🐳 Docker 24+ installed
- 💻 Optional: .NET 10 SDK for local development

## 🏃 Running with Docker
1. **Build the Docker image**:

```bash
docker build -t hrappdotnet .
docker run -d -p 8080:8080 --name hrapp hrappdotnet
