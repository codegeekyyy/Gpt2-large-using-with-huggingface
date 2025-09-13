# Gpt2-large-using-with-huggingface
This project demonstrates text generation with GPT-2 Large using the Hugging Face Transformers library. It explores various decoding strategies such as Greedy Search, Beam Search, Top-k Sampling, and Nucleus (Top-p) Sampling, showcasing how each impacts fluency, coherence, and creativity in AI-generated text.


GPT-2 Text Generation with Hugging Face

This project demonstrates how to use the Hugging Face Transformers library for text generation with the GPT-2 Large model.
It explores different decoding strategies to generate human-like text:

Greedy Search – selects the highest probability token at each step.

Beam Search – explores multiple possible sequences for more coherent results.

Top-k Sampling – samples from the top k most likely next tokens.

Nucleus (Top-p) Sampling – samples dynamically from the smallest set of tokens whose cumulative probability is above p.

The notebook is useful for understanding how different decoding methods affect the quality, diversity, and creativity of generated text.
