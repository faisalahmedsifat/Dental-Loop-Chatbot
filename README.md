# Dental Chat LLM Repository

In this repository, we explore the usage of Retrieval-Augmented Generation (RAG) on a dental dataset. Although the dataset is not publicly available, significant improvements in factual correctness were observed by fine-tuning on a small subset.

The implementation of the entire pipeline is located in the `src/experiment_pipeline.ipynb` file, while various experiments are housed in the `src/experiments` directory. The `src/core` directory contains the core functional pipelines, including fine-tuning the embeddings and fine-tuning the LLaMA2 model on a closed-source dataset using QLoRA.

**Important:** This repository heavily depends on the Hugging Face API key. You must generate an access token from Hugging Face and ensure that the account holder has access to the LLaMA2 model, as it is gated.

---

## Usage Instructions

### Prerequisites
To use the dental chat LLM pipeline, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/sifat-ahmed/dental-chat-llm.git
    ```

2. **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Obtain a Hugging Face API key:**
    - Create an account on [Hugging Face](https://huggingface.co).
    - Generate an API token.

4. **Set the Hugging Face API key as an environment variable:**
    ```bash
    export HF_TOKEN=YOUR_API_KEY
    ```

5. **Explore the implementation:**
    - Access the `src/experiment_pipeline.ipynb` file to view the entire pipeline implementation.

6. **Explore experiments:**
    - Navigate to the `src/experiments` directory to view different experiments.

7. **Modify core pipelines:**
    - In the `src/core` directory, modify pipelines to fine-tune the embedding and the LLaMA2 model on your own dataset.

    > **Note:** The LLaMA2 model requires access granted by the Hugging Face account holder.

8. **Run the pipeline:**
    - Execute the necessary scripts and notebooks to run the pipelines.

For additional guidance, refer to the [documentation](https://github.com/sifat-ahmed/dental-chat-llm/blob/main/docs/README.md).

---

## Contributing

We welcome contributions to the Dental Chat LLM project. If you would like to contribute, follow these steps:

1. **Fork the repository** and create a new branch for your changes.
2. Make your changes and ensure that the code is properly formatted.
3. Write tests to validate your changes.
4. Submit a pull request with a clear description of your changes and the problem it solves.
5. Project maintainers will review your pull request and provide feedback as necessary.
6. Once approved, your pull request will be merged into the main branch.

Thank you for contributing!

---

## License

This project is licensed under the Apache License Version 2.0 License. For more details, see the [LICENSE](https://github.com/faisalahmedsifat/llama2-dental/blob/main/LICENSE) file.

---

## Contact

For any questions or further assistance, feel free to reach out:

**Faisal Ahmed Sifat**  
Email: [faisal.ahmed20@northsouth.edu](mailto:faisal.ahmed20@northsouth.edu)

---

## Acknowledgements

We would like to acknowledge the following individuals and organizations for their contributions to the Dental Chat LLM project:

- **Md Sahadul Hasan Arian**
- **Acme Corporation**

---

## References

1. ADA Australia Policies: [Link](https://ada.org.au/about/policies)
2. SDCEP Published Guidance: [Link](https://www.sdcep.org.uk/published-guidance/)
