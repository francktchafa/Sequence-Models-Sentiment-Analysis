This repository contains two notebooks that explore sentiment analysis and emotion representation through natural language processing.

**Project_Sentiment_Analysis_v1.ipynb: Emojifier with Word Embeddings**
This notebook utilizes pre-trained word embeddings to develop an Emojifier that associates sentences with the most relevant emoji. It demonstrates how word vector representations can effectively capture semantic meaning. Some examples:
* "Job well done!" → 👍
* "Let's get dinner and talk" → 🍴
* "I love you!" → ❤️

**Project_Sentiment_Analysis_v2.ipynb: Enhanced Emojifier with LSTM**
This notebook extends the initial model by incorporating an LSTM (Long Short-Term Memory) network, which captures sequential dependencies and context in text. The LSTM-based architecture improves the Emojifier's performance by better understanding the flow of information in sentences.

**Project_Sentiment_Analysis_v3.ipynb: Advanced Emojifier with Transformers**
This notebook advances the Emojifier by introducing transformer-based architectures like BERT or DistilBERT for sentiment and emotion analysis. Transformers enable the model to leverage self-attention mechanisms for better handling of long-range dependencies in text. This model achieves enhanced accuracy and robustness in mapping sentences to emojis.
It also demonstrates transfer learning using pre-trained models from Hugging Face.
