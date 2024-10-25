# DiagramBot.ai 🤖

**DiagramBot.ai** is an AI-powered tool designed to generate **Mermaid diagrams** through simple chat-based interaction. It leverages **Google Generative AI** to help users create a wide variety of diagrams such as flowcharts, ER diagrams, pie charts, and more—without needing to manually write code or understand the underlying Mermaid syntax.

## Features 🚀
- **AI-Powered Diagram Generation**: Simply describe the diagram you need, and the tool will generate the corresponding **Mermaid code** and visual representation.
- **Supported Diagram Types**:
  - **Flowcharts** (`graph TD`, `graph LR`)
  - **Pie Charts** (`pie`)
  - **Gantt Charts** (`gantt`)
  - **Sequence Diagrams** (`sequenceDiagram`)
  - **Class Diagrams** (`classDiagram`)
  - **State Diagrams** (`stateDiagram`)
  - **Entity-Relationship Diagrams (ERD)** (`erDiagram`)
- **Versatile Output**: Diagrams can be downloaded in **PNG**, **PDF**, or **Mermaid code** formats.
- **Editable Diagrams**: Users can edit the generated Mermaid code directly within the tool and regenerate the diagram.

## Demo 🎥
TBA

## Installation and Setup ⚙️

### Prerequisites
- Python 3.7+
- **Google Generative AI API Key**: DiagramBot.ai uses Google Generative AI to generate diagrams. Make sure you have an API key from Google. Set it in your environment variables as `GEMINI_API_KEY`.

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/mrnithesh/DiagramBot-ai.git
    cd DiagramBot.ai
    ```

2. Create and activate a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Set your **Google Generative AI API Key** in the environment:
    ```bash
    export GEMINI_API_KEY=your_google_api_key
    ```

### Running the App
Start the Streamlit app using the following command:
```bash
streamlit run app.py
```

## Usage 🛠️
1. **Chat with the AI**: Enter your description of the diagram (e.g., "Create a flowchart for a login system") in the chat interface.
2. **View and Download Diagrams**: The generated diagram will be displayed alongside options to download the diagram as **PNG**, **PDF**, or **Mermaid code**.
3. **Edit Mermaid Code**: You can manually edit the generated Mermaid code in the code tab and regenerate the diagram with the updated code.

## Example Queries 💬
Here are some example queries you can use with **DiagramBot.ai**:

- "Generate a flowchart showing the process of logging in, checking credentials, and accessing the dashboard."
- "Create an ER diagram with a customer placing an order for a product."
- "Show a Gantt chart for a project with development, testing, and deployment phases."

## Supported Diagram Types 📊
**DiagramBot.ai** supports the following types of diagrams:
1. **Flowcharts**: Visualize step-by-step processes using `graph TD` or `graph LR`.
2. **Pie Charts**: Create percentage-based pie charts.
3. **Gantt Charts**: Plan project timelines with start dates and durations.
4. **Sequence Diagrams**: Show how entities communicate with each other over time.
5. **Class Diagrams**: Define classes and relationships in an object-oriented structure.
6. **State Diagrams**: Represent the state transitions of a system.
7. **Entity-Relationship Diagrams (ERD)**: Model relationships between data entities.

## Contributing 🤝

Contributions are welcome! Here's how you can help:

1. **Fork the repository**.
2. **Create a new branch** for your feature or bugfix:
    ```bash
    git checkout -b feature/your-feature
    ```
3. **Make your changes** and commit them:
    ```bash
    git commit -m "Add a new feature"
    ```
4. **Push your branch** to your forked repository:
    ```bash
    git push origin feature/your-feature
    ```
5. **Open a pull request** with a description of your changes.

## Issues and Feedback 💡
If you encounter any bugs or have feature requests, feel free to open an issue in the [Issues section](https://github.com/mrnithesh/DiagramBot-ai/issues). I’m always open to feedback and ideas to improve the tool.

## License 📄
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Connect with Me 👋
- **GitHub**: [github.com/mrnithesh](https://github.com/mrnithesh)
- **LinkedIn**: [linkedin.com/in/mrnithesh](https://linkedin.com/in/mrnithesh)

Feel free to reach out if you have any questions, ideas, or suggestions for **DiagramBot.ai**!
