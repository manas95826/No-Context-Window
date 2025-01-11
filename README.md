# No-Context Window: Context-Free Long-Form Text Generation

A sophisticated AI-powered document processing pipeline designed for **context-free long-form content generation** and **automated financial report creation**. Built with LangChain and LangGraph, the system processes documents and generates structured reports through a series of nodes in a multi-step pipeline.

## 🌟 Features

- **Context-Free Long-Form Generation**: Generate long-form content without requiring pre-established context.
- **Automated Financial Report Generation**: Generates detailed financial reports from raw input data.
- **Customizable Workflow**: Easily integrate new nodes and steps into the pipeline.
- **Support for Multiple LLM Providers**: Flexibility to use different language models for various tasks.
- **Structured Outputs**: Generates structured content in multiple formats such as Markdown, JSON, and plain text.

## 🏗️ Architecture

The system leverages a **directed graph workflow** for document processing, with nodes responsible for different stages of the pipeline. The architecture includes:

1. **Planning Node**: Analyzes the input documents, extracts key information, and generates a structured plan for the content.
2. **Writing Node**: Generates the content based on the plan created by the Planning Node.
3. **Saving Node**: Handles the output formatting and persistence (e.g., Markdown or JSON files).
4. **Financial Report Node** (optional): Specialized node for generating financial reports from structured data.

## 📁 Project Structure

The project is organized into the following directory structure:

