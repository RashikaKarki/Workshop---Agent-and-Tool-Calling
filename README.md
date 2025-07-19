# Workshop: Building Your First AI Agent with Gemini

Welcome to the repository for the "Building Your First AI Agent" workshop! Here you will find all the resources, including the presentation slides and the hands-on code notebook used during the session.

## Core Concepts Covered

*   **The Limitations of LLMs:** Understand why models like Gemini can't answer questions about current events out-of-the-box.
*   **What is an AI Agent?** Learn the fundamental loop of an agent: **Reason -> Act -> Observe -> Respond**.
*   **Tool Calling:** Master the core mechanism that allows an LLM to request the execution of custom code (our "tools").
*   **API Integration:** See how to connect your agent to external, third-party APIs (like GitHub) to give it powerful new capabilities.

## How to Use This Repository

This repository is organized to be simple and easy to navigate. All the materials you need for the workshop are located in their respective folders:

*   **/slides:** This directory contains the presentation slides used during the workshop session.
*   **/notebook:** This directory contains the boilerplate as well as final Google Colab notebook.

## Getting Started with the Code

To run the hands-on example yourself, please follow these steps:

1.  **Clone the Repository**

2.  **Get a Gemini API Key:** You will need a free API key from Google to use the Gemini model.
    *   Visit [Google AI Studio](https://aistudio.google.com/) to create your key.

3.  **Open the Notebook:** Navigate to the `/notebook` directory and open the `.ipynb` file in Google Colab.

4.  **Set Up Your API Key in Colab:**
    *   In the Colab notebook, click the **key icon (Secrets)** in the left-hand sidebar.
    *   Create a **new secret** with the name `GEMINI_API_KEY`.
    *   Paste your API key into the "Value" field and ensure notebook access is enabled. This keeps your key secure.

5.  **Run the Cells:** Follow the instructions and execute the cells in the notebook from top to bottom. The code includes detailed comments explaining each step of the process as the agent comes to life.
