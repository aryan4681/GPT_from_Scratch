# GPT from Scratch

This repository implements a basic GPT model from scratch using PyTorch. The notebook walks through the key components needed to build a transformer-based language model.

## Structure

### Key Steps:
1. **Data Preparation**:
   - Reads and preprocesses the dataset (`shakespeare.txt` in this example).
   - Identifies unique characters and prepares mappings for tokenization.

2. **Model Implementation**:
   - Implements the core components of a transformer:
     - **Q, K, V (Query, Key, Value)** matrices for attention.
     - Positional encoding.
     - Multi-head self-attention layers.

3. **Training**:
   - Trains the model on the prepared dataset to predict the next character in a sequence.

 
**QVK**:
  The attention mechanism is implemented from scratch, defining the query, key, and value matrices manually.
 

