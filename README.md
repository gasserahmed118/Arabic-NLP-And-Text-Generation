      🧠 Arabic NLP & Text Generation – Smart Transformer Pipeline

         📌 Overview
             This project demonstrates a complete, modern Arabic NLP pipeline using Transformer-based models from Hugging Face and SimpleTransformers.
             It covers multiple real-world NLP tasks in Arabic, including:
                 * Arabic text generation (prose
                 * Arabic poetry generation
                 * Sentiment analysis
                 * Toxicity / hate speech detection

         🎯 Project Goals
             * Generate high-quality Arabic text using GPT-2 models
             * Compare low-level (Transformers) vs high-level (SimpleTransformers) APIs
             * Perform Arabic sentiment analysis with probability scores
             * Detect toxic and hateful Arabic language
             * Provide a clean, reproducible setup with safe installation
 
         🛠️ Technologies & Libraries
            * Python 3.9+
            * PyTorch
            * Hugging Face Transformers
            * SimpleTransformers
            * Pretrained Arabic models from Hugging Face Hub

         📂 Project Structure
             arabic-nlp-transformers/
             │
             ├── notebooks/
             │   └── arabic_nlp_pipeline.ipynb
             │
             ├── README.md
             └── requirements.txt

        🧠 CPU vs GPU Handling
             The project automatically detects hardware:
                python
                   device = "cuda" if torch.cuda.is_available() else "cpu"
                   ✔️ Works safely on CPU-only machines
                   ✔️ CUDA is used only when available

        ⚠️ Common Issues & Solutions
            1. CUDA Not Available
                 ✔️ Automatically falls back to CPU
            2. Protobuf / Dependency Errors
                ✔️ Uses compatible Transformer versions
                ✔️ Avoids forced system-level installs

       📈 Possible Extensions
           * Arabic Named Entity Recognition (NER)
           * Text summarization
           * Fine-tuning on custom Arabic datasets
           * Web UI using Streamlit
           * Model evaluation & benchmarking

        📚 References
            * Hugging Face Transformers
            * SimpleTransformers Documentation
            * GPT-2 Architecture
            * XLM-RoBERTa Models

        👤 Author
             Gasser Ahmed
