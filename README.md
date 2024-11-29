# Text Generation using GPT-2
"This project demonstrates how to use the pre-trained GPT-2 model from the Hugging Face Transformers library to generate coherent and contextually relevant text based on a given prompt."
Features:
  - Loads a pre-trained GPT-2 model and tokenizer.
  - Generates text based on user-defined parameters:
      - Prompt: The initial text to guide the generation.
      - Maximum length: The maximum number of tokens to generate.
      - Temperature: Controls randomness in predictions (higher values = more randomness).
      - Top-k: Limits sampling to the top-k most likely next words.
  - Supports GPU acceleration for faster text generation.
Parameters:
  - model_name: "gpt2" (other options include "gpt2-medium", "gpt2-large", and "gpt2-xl")
  - max_length: 50 (default, can be adjusted for longer or shorter outputs)
  - temperature: 1.0 (default, controls randomness in generation)
  - top_k: 50 (default, limits sampling to the top-k tokens)
Usage:
  - Modify the `prompt` variable to supply the initial text for generation.
  - Adjust parameters such as `max_length`, `temperature`, and `top_k` to control the output characteristics.
Example:
  - Prompt: "Once upon a time in a faraway kingdom"
  - Generated Text: A continuation of the story in GPT-2's style.
