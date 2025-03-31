# ADVERSARIAL NATURAL LANGUAGE PROCESSING INFERENCE ANALYSIS

This project explores adversarial natural language inference using the ANLI (Adversarial Natural Language Inference) dataset. The analysis focuses on testing the robustness of language models against adversarial examples designed to confuse NLI systems.

## Overview

Natural Language Inference (NLI) is a fundamental task in NLP that involves determining the logical relationship between a premise and a hypothesis. The three possible relationships are:
- **Entailment**: The hypothesis logically follows from the premise
- **Contradiction**: The hypothesis contradicts the premise
- **Neutral**: The hypothesis neither follows from nor contradicts the premise

The ANLI dataset contains challenging examples specifically designed to be difficult for state-of-the-art models.

## Project Components

The project includes:
- Analysis of language model performance on adversarial NLI tasks
- Implementation of various techniques to evaluate model robustness
- Testing with multiple prompt engineering approaches
- Visualization of results and comparison of different strategies

## Technologies Used

- Python
- LangChain
- Hugging Face Transformers
- FAISS for vector embeddings
- Pandas for data manipulation
- Matplotlib/Seaborn for visualization

## Setup and Execution

### Requirements
Required packages can be installed with:
```
pip install datasets langchain langchain_openai langchain_deepseek tqdm matplotlib pandas seaborn pyarrow faiss-cpu langchain_community sentence-transformers
```

## Results

The project evaluates different prompt engineering and adversarial defense techniques, measuring how well language models can handle challenging NLI examples.

## License

This project is part of academic coursework and is provided for educational purposes.
