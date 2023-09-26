# Semantic Book Search

This project utilizes vector embeddings through [OpenAI's Embeddings API](https://platform.openai.com/docs/guides/embeddings/embeddings) and [Weaviate vector database](https://weaviate.io/) to enable efficient semantic searches within a dataset of books. The aim is to facilitate book discovery based on user preferences by simply entering a prompt.  
The project inspired by the [short course on large language models and semantic search](https://www.deeplearning.ai/short-courses/large-language-models-semantic-search/),

## Data Source

The dataset is derived from the following Goodreads lists:

- [Best Books Ever](https://www.goodreads.com/list/show/1.Best_Books_Ever)
- [Recommended Arabic Books](https://www.goodreads.com/list/show/3865)
- [Essential Books of Computer Science](https://www.goodreads.com/list/show/2205.Essential_Books_of_Computer_Science#10803540)

## Getting Started

To use this codebase, follow these steps:

1. Clone the repository to your local machine.

2. Create a `.env` file in the project root directory.

3. Inside the `.env` file, enter your API keys for the services you plan to use.

   ```
   OPENAI_API_KEY=your_openai_api_key_here
   WEAVIATE_API_KEY=your_weaviate_api_key_here
   ```

4. Run the code and start searching for books semantically!
