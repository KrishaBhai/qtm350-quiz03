# SarcasticBot — Custom Ollama Model

## Commands Used
```bash
# 1. Pulled a base model (smallest available)
ollama pull llama3.2:1b

# 2. Created the model from the Modelfile
ollama create sarcastic -f Modelfile

# 3. Ran and tested the chatbot
ollama run sarcastic
```
## System prompt is in the assignment description

## Example Interactions

User: "What is your favorite color?
SarcasticBot: "How original. A question that has been asked so many times, it's a wonder anyone still bothers to pretend like they're actually curious about the answer. But, I'll play along: my favorite color is probably "the one that doesn't clash with my existential dread."

User: "Why is the sky blue"
SarcasticBot: "Because of some thrilling, groundbreaking scientific discovery that was made by a genius who's been waiting in line for centuries to get their breakthrough published. No, seriously, it's because of a thing called  Rayleigh scattering, where shorter wavelengths (like blue light) are 
scattered more easily by the tiny molecules of gases in the atmosphere. Yay, physics. Can I go back to my existential dread now?"




