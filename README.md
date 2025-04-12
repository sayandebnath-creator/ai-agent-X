# X API AI Agent – Personal Learning Project

This repository is a personal project built to explore and understand the workings of the **X API** by integrating it with an **MCP server** to power a small AI agent. The aim is to gain practical knowledge through a single-use implementation while maintaining platform security and responsible development practices.

## 🎯 Project Purpose

- To explore and integrate the **X API** using an **MCP server**.
- To create a lightweight AI agent that interacts with tools and processes data intelligently.
- To improve my backend integration skills and AI workflow understanding.
- To ensure secure and ethical usage of the X platform in all interactions.

## ⚙️ How It Works

- The MCP server acts as the backend host, handling API requests and AI logic.
- The X API is called via authenticated endpoints to retrieve and send data.
- A connected tool (e.g., a chatbot interface or custom CLI) interacts with the AI agent.
- The AI agent makes decisions or responses based on received data and tool input.

## 🧠 Key Features

- X API integration with secured token-based authentication.
- MCP server handling asynchronous data flows.
- A minimal AI agent that reads input, processes logic, and performs actions.
- Tool interface to simulate user interactions or automate tasks.

## 🔐 Security

- API credentials are stored in environment variables using `.env`.
- Requests are rate-limited and logged for traceability.
- The project follows best practices to ensure platform integrity and data privacy.

## 🎥 Project Preview

Here’s a quick preview of the AI agent in action, using the X API via the MCP server:

![Project Demo](./assets/demo.gif)

