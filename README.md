# ML-Foundations

Notebooks from my Data Science and AI coursework at IIT Mandi and my own study, covering exploratory analysis and classical ML through neural networks, computer vision, generative models, transformers and reinforcement learning.

Most notebooks were written for Google Colab and keep their outputs, so you can read results on GitHub without running anything.

## Contents

| Folder | What's inside |
|---|---|
| [`01-python-and-eda`](01-python-and-eda) | NumPy basics and exploratory analysis: Diwali sales, taco sales and two EDA case studies |
| [`02-classical-ml`](02-classical-ml) | Linear regression, iris classification, heart-disease prediction, spam classification, credit-card fraud detection, live weather prediction |
| [`03-neural-networks`](03-neural-networks) | MLPs in PyTorch and TensorFlow, fully connected networks, MNIST, small experiments such as learning primality |
| [`04-computer-vision`](04-computer-vision) | CNNs on MNIST and Fashion-MNIST, autoencoders and transfer learning, U-Net segmentation on Carvana, ViT and ViViT |
| [`05-generative-models`](05-generative-models) | Conditional GAN and Pix2Pix image-to-image translation |
| [`06-transformers-nlp`](06-transformers-nlp) | Training a transformer, BERT and GPT |
| [`07-reinforcement-learning`](07-reinforcement-learning) | Q-learning, DQN and A2C on CartPole, and an A2C agent for adaptive recommendations |
| [`assignments`](assignments) | Graded work: KNN and SGD on census data, a decision tree from scratch, SVM classification, fully connected networks |

## Running them

Open any notebook in Colab, or locally:

```bash
uv venv && source .venv/bin/activate
uv pip install jupyter numpy pandas matplotlib seaborn scikit-learn torch torchvision tensorflow
jupyter lab
```

The three small datasets the EDA and regression notebooks read (`insurance.csv`, `Diwali Sales Data.csv`, `placement.csv`) sit next to them. The rest download their data with `kagglehub` or the `torchvision`/`keras` loaders, or expect the file named in their first cells; the spam classifier needs `mails_data.csv`, which is too large to store here.
