## 🚀 Features

- 👀 **Instant Visualization**: Convert any GitHub repository structure into a system design / architecture diagram
- 🎨 **Interactivity**: Click on components to navigate directly to source files and relevant directories
- ⚡ **Fast Generation**: Powered by OpenAI for quick and accurate diagrams
- 🔄 **Customization**: Modify and regenerate diagrams with custom instructions
- 🌐 **API Access**: Public API available for integration (WIP)

## 🤔 About

I created this because I wanted to contribute to open-source projects but quickly realized their codebases are too massive for me to dig through manually, so this helps me get started - but it's definitely got many more use cases!

Given any public (or private!) GitHub repository it generates diagrams in Mermaid.js with OpenAI.

I extract information from the file tree and README for details and interactivity (you can click components to be taken to relevant files and directories)

Most of what you might call the "processing" of this app is done with prompt engineering. This basically extracts and pipelines data and analysis for a larger action workflow, ending in the diagram code.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.


