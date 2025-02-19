# Monte Carlo Tree Search

Using Tree Search space to answer harder problems that cannot be answerd by simple COT.
Ref paper - https://arxiv.org/pdf/2501.08603

The implementation here is a simplified version of the one done in the paper.

For LLM we are using Ollama with `llama3.2:3b` model.
We can use some other LLM of choice by changing the `get_llm_response` function.

Setup instructions -
1. Install ollama
2. ollama run llama3.2:3b
3. Use the notebook and play with the code.