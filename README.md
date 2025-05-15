# Swagger Practice

This repository is a personal playground for learning and experimenting with [Swagger](https://swagger.io/) — a suite of open-source tools for documenting, testing, and visualizing REST APIs using the OpenAPI Specification.

## ⚠️ Disclaimer

This repository was created as a self-directed learning project to explore Swagger tools and API documentation workflows on my own time. It is intended purely for experimentation and may contain incomplete, rough, or in-progress configurations. While the code may not always reflect production-ready standards, the goal is to deepen my understanding through hands-on practice.

## Purpose

To gain hands-on experience with:
- Using Swagger UI to generate interactive API documentation
- Integrating Swagger with an Express-based backend
- Hosting local or static API docs from OpenAPI files
- Exploring Swagger Editor and Swagger Codegen
- Learning how to document, test, and maintain APIs efficiently

## Tools & Technologies

- **Swagger UI**
- **Swagger Editor**
- **Swagger Codegen**
- **OpenAPI 3.0** (spec format used by Swagger tools)
- **Node.js + Express**
- (Optional) **Docker**

## Getting Started

> These steps will guide you through launching Swagger UI locally with a sample API.

### Prerequisites

- Node.js and npm installed
- Git installed
- (Optional) Docker installed for container-based setups

### Steps

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/Swagger-Practice.git
   cd Swagger-Practice

2. Navigate to the example project:
   ```bash
   cd examples/swagger-ui-express

3. Install dependencies:

   ```bash
   npm install

4. Start the server:

   ```bash
   npm start

5. Open your browser and visit:

   ```bash
   http://localhost:3000/api-docs

## Folder Structure

```bash
Swagger-Practice/
├── examples/
│   ├── swagger-ui-express/    # Express API with Swagger UI integration
│   ├── swagger-editor-docker/ # Dockerized Swagger Editor (optional)
│   └── codegen-demo/          # Experiments with Swagger Codegen
└── README.md                  # This file
```

## Resources

[**Swagger Tools Overview**](https://swagger.io/why-swagger/)

[**Swagger UI GitHub**](https://github.com/swagger-api/swagger-ui)

[**Swagger Editor**](https://editor.swagger.io/)

[**Swagger Codegen**](https://github.com/swagger-api/swagger-codegen)

[**OpenAPI Specification (OAS)**](https://spec.openapis.org/oas/latest.html)
