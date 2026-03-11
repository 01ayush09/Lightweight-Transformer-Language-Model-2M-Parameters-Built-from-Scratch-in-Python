# 📦 Lightweight 2M Parameter Transformer Language Model

> A compact, efficient Transformer-based language model designed for minimal parameter count (~2 million parameters) while retaining core natural language generation capabilities.

---

## 🧠 Project Overview

This repository implements a **lightweight transformer language model** with a total of **~2 million parameters**, focused on:

✔️ Realistic language modeling  
✔️ Fast training on limited hardware  
✔️ Reduced memory footprint  
✔️ Educational value (understand transformer internals)

Unlike large LLMs with billions of parameters, this model emphasizes compact design and efficiency for research, experimentation, and deployment in constrained environments.

---

## 📌 Key Highlights

### 🔹 Model Efficiency

- **~2M Parameters** — significantly smaller than typical transformer models used in large-scale NLP systems (100M+).  
- Compact architecture enables experimentation on CPUs and low-end GPUs.
- Designed for basic language modeling tasks such as next-token prediction and simple text generation.

### 🔹 Transformer Architecture

- Multi-head self-attention  
- Positional encodings  
- Feed-forward layers  
- Layer normalization  
- Residual connections  

These core transformer components allow the model to learn contextual representations efficiently.

---

## 🚀 Training the Model

To train on a text dataset:

```bash
python train.py \
    --data_path path/to/text_corpus.txt \
    --epochs 10 \
    --batch_size 64 \
    --lr 1e-4 \
    --save_model lightweight_model.pt
```

This will preprocess the corpus, train the transformer model, and save a trained checkpoint.

---

## ▶️ Generating Text

After training, generate text using:

```bash
python eval.py \
    --model_path lightweight_model.pt \
    --prompt "Once upon a time" \
    --max_len 256
```

This runs autoregressive generation, producing coherent continuation from the prompt.

---

## 📈 Performance & Use Cases

📌 The model is designed for:

- Educational experimentation with transformer internals  
- Language modeling on small datasets  
- Fast inference on CPU / limited GPU  
- Resource-efficient generation tasks

Because it has only ~2 million parameters, it trades off raw performance for efficiency, making it ideal for lightweight research and understanding transformer behavior.

---

## 🧪 Example Output

```
> Prompt: “The future of AI is”
The future of AI is connected to the data we gather and the models we train. As compute improves, so too will the capabilities of small models...
```

(Sample generated text showcasing contextual learning.)

---

## 📚 Background: Transformers

This project builds on the standard **Transformer architecture**, a neural network mechanism known for self-attention and parallel contextual learning. Transformers power most modern language models today, including large variants such as GPT and T5, but here scaled down for minimal footprint and educational use.

For detailed theory on transformer components like self-attention and positional encoding, see “Attention Is All You Need”.

---

## 🤝 Contributing

Contributions are welcome! You can:

⭐ Star this repository  
🐛 Report issues  
🔀 Submit pull requests

Feel free to propose improvements like:

- Training on new datasets  
- Quantization or pruning for further efficiency  
- Integration with generation interfaces

---

## 📜 License

This project is released under the **MIT License**.

---

## 📬 Contact

For questions or collaboration, feel free to open an issue or pull request.  
Happy experimenting with lightweight transformers! 🚀

Inspired by modern Transformer and LLaMA-style architectures, with a focus on learning through implementation.

---

If you find this project useful for learning or reference, feel free to star the repository!
