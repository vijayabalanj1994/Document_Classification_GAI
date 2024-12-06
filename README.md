# TopicTagger AI

## Project Overview

The **TopicTagger AI** project focuses on building a machine learning pipeline for classifying news articles into predefined categories. The aim is to design a model that enhances search engine capabilities by efficiently retrieving and delivering relevant content to users. This project demonstrates expertise in data preprocessing, model development, and performance evaluation.

---

## Features

- **Dataset Preparation:**
  - Utilizes the AG NEWS dataset for multi-class classification.
  - Efficient tokenization and vocabulary building using PyTorch's TorchText utilities.
  - Balanced train/validation/test dataset splits for robust model evaluation.

- **Model Architecture:**
  - A lightweight feed-forward neural network (NN) with `nn.EmbeddingBag` for efficient embedding representation.
  - Two-layer architecture optimized for text classification.
  - Weight initialization for stable training performance.

- **Training Pipeline:**
  - Gradient clipping and learning rate scheduling to enhance training stability.
  - Tracks validation accuracy and saves the best-performing model during training.

- **Visualization:**
  - Embedding visualization using t-SNE, showcasing how the model groups similar content.
  - Interactive 3D plots generated with Plotly for deeper insights.

- **Prediction:**
  - A simple and user-friendly pipeline for predicting categories of new articles.
  - Markdown visualization for presenting results clearly.

---

## Results

- **Accuracy:**
  - Pretrained Model Accuracy: ~81.7% on the test set.

- **Embedding Visualization:**
  - Visualizations highlight clear separations between different news categories.

---

---

## Code

- the project code can be found in Document_Classification.ipynb file

---

## Technologies Used

- Python (PyTorch, TorchText, NumPy, Pandas, Matplotlib, Plotly)
- AG NEWS Dataset
- t-SNE for dimensionality reduction

---

## Example Prediction

### Input:
```
"Canada navigated a stiff test against the Republic of Ireland on a rain-soaked evening in Perth, coming from behind to claim a vital 2-1 victory at the Women’s World Cup."
```

### Output:
```
Category: Sports
```

---

## Future Improvements

- Extend the model to support multilingual datasets.
- Incorporate real-time news scraping for dynamic content classification.
- Experiment with advanced architectures such as transformers.

---

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request for any improvements or bug fixes.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

