# Finetuning using Lamini

In this project I will develop a chatbot to generate SQL answers, combined with this we will perform a finetuning with the idea of reducing the token consumption and improving the quality of the result. We can make all of this more simple by using a platform such as Cohere or OpenAI, but in my case, I will use Lamini because it gives us the option of finetuning other LLMs such as Llama 3.

#

> **Disclaimer**
> In this project I will use the free tier of Lamini to make this project accessible to anyone interested in experimenting with Finetuning, in case of need for a production-ready app, I recommend using other platforms or upgrading to the paid tier to access more resources such as memory tuning to keep hallucinations almost 0 and with faster results.



## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/Jesusmanuelrg/finetuning_lamini.git
    ```
2. Navigate to the project directory:
    ```bash
    cd chatbot_routing
    ```
3. Install dependencies:
    ```bash
    pip install -qU lamini datasets pandas transformers
    ```
4. Set up environment variables (e.g., API keys for Lamini and other services).
    ```markdown
    Create a `.env` file in the root directory and add the necessary environment variables.
    ```

## Configuration
- **API Keys:** Configure your API keys in the `.env` file.

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License
This project is licensed under the Apache License. See the [LICENSE](LICENSE) file for details.
