# 🦆 Ducky AI - Open Source AI Tool for Godot 🎮

Welcome to Ducky AI! This is an open-source AI tool designed to assist developers working with the Godot game engine. Ducky AI, built using Rust, allows developers to interact with a game development assistant powered by AI, capable of executing instructions within the Godot engine.

## Features 🚀

- **Interactive Assistant**: Interact with a game development assistant using natural language commands.
- **Godot Integration**: Execute model inference from GDScript.
- **Local Models**: Utilize locally hosted AI models for enhanced privacy and offline functionality.
- **Future Hosted Option**: The project aims to offer a hosted option in the future for convenience and scalability.

## Getting Started 🛠️

To get started with Ducky AI, follow these steps:

1. Clone the repository: `git clone https://github.com/yourusername/ducky-ai.git`
2. Navigate to the project directory: `cd ducky-ai`
3. Build the project using Rust: `cargo build -p server --release`
4. Run the tool: `./target/release/ducky-ai`

## Usage 🕹️

1. Launch the Ducky AI tool.
2. Interact with the assistant using natural language commands.
3. The assistant will execute instructions within the Godot game engine.

## Contributing 🤝

We are not currently accepting pull-requests on this repository from people outside of our team, though we probably will once the project reaches a certain level of stability and usefulness.

Instead if you would like to contribute, please open an issue for discussion first or create a [discussion](https://github.com/NiceDuckGames/duckyai/discussions).

An additional way to contribute to the project is to contribute to the datasets used to create the custom models.

### Contributing to the Model Dataset
#### Command Sequence Data
To contribute your own command sequence data to the model dataset see the [Submitting Your Own Data](https://github.com/NiceDuckGames/DuckyCommandDataset?tab=readme-ov-file#submitting-training-data) section of the ducky-command-dataset repository.

#### GDScript Data
If you wish to contribute GDScript source code for use in training the DuckyAI codegen model see the [ducky-ai-codegen-optins](https://github.com/NiceDuckGames/ducky-ai-codegen-optins) repository for instruction on how to do that.

## Sponsorship and Support 💡

Ducky AI is a passion-driven project, and your support is greatly appreciated. You can support the development of Ducky AI through the following platforms:

- **GitHub Sponsorship**: Become a sponsor on GitHub to support ongoing development and maintenance of Ducky AI. [Sponsor Ducky AI](https://github.com/sponsors/NiceDuckGames)

- **Patreon**: Join our Patreon community to get exclusive access to behind-the-scenes updates, early releases, and more. [Support Ducky AI on Patreon](https://patreon.com/niceduckgames)

Your support helps us continue to improve Ducky AI and provide valuable resources to the community.

## License 📝

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements 🙏

- Special thanks to [Godot Engine](https://godotengine.org/) for being awesome and empowering game developers!
- Shout out to the HuggingFace crew for making [Candle](https://github.com/huggingface/candle) which is an awesome ML framework for Rust.

## Support 📧

For support or inquiries, please contact us at support@niceduck.games.
