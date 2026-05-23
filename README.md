# Standard AutoEncoder
> _Architecture_
<center>
<img src='https://github.com/Martinmbiro/standard-autoencoder/raw/refs/heads/main/plots/autoencoder_sketch.png' alt='auto_encoder_sketch' width=800/>
</center>

Hello again 👋
+ An **autoencoder** is a neural‑network architecture that learns to compress _(encode)_ input data into a compact latent representation and then reconstruct _(decode)_ the original data from that representation. Trained with _unsupervised_ **(self‑supervised)** learning, the model’s _ground truth_ is the input itself
+ This project is a step-by-step implementation, training, and analysis of a standard AutoEncoder utilizing [PyTorch](https://pytorch.org/) and [PyTorch Lightning](https://lightning.ai/docs/pytorch/stable/)
+ While achieving descent image reconstruction, it is noted that a primary shortcoming of the standard AutoEncoder architecture is that it maps training data to single coordinates in the latent space rather than continuous distributions
+ Find the notes and annotated code in the Jupyter Notebook. Feel free to open and explore in Google Colab

## Tools ⚒️
**The tools used for this repository are:**
1. [Google Colab](https://colab.google/) - A hosted _Jupyter Notebook_ service by Google.
2. [`torch`](https://pytorch.org/) - (PyTorch) - An open-source **Deep Learning** library
3. [`lightning`](https://lightning.ai/docs/pytorch/stable/) - (PyTorch Lightning) - An open-source framework that serves as a high-level interface for PyTorch
4. [`matplotlib`](https://matplotlib.org/) - A comprehensive library for making static, animated, and interactive visualizations in Python
5. [`plotly`](https://plotly.com/python/) - An interactive, open-source, and browser-based graphing library
6. [`sklearn`](https://scikit-learn.org/stable/getting_started.html) - An open-source Python toolset that provides algorithms for machine learning, data preprocessing, and model evaluation
7. [`numpy`](https://numpy.org/) - The fundamental package for scientific computing with Python
8. [`pandas`](https://pandas.pydata.org/) - An open-source tool for data analysis and manipulation in Python
9. [`torchinfo`](https://github.com/TylerYep/torchinfo) - A library for inspecting neural network layer structures and network parameter details

> _Notable modules from [The Python Standard Library](https://docs.python.org/3/library/index.html) include [`pathlib`](https://docs.python.org/3/library/pathlib.html) and [`os`](https://docs.python.org/3/library/os.html)_

## Results 📈
+ _Structure of Neural Network_
> <img src='https://github.com/Martinmbiro/standard-autoencoder/raw/refs/heads/main/plots/Screenshot%202026-05-23%20122448.png' alt='neural_network_structure' width=500/>

+ _Training Loss (MSE Loss)_
> <img src='https://github.com/Martinmbiro/standard-autoencoder/raw/refs/heads/main/plots/mse_loss.png' alt='training_loss' width=650 />

+ _Input vs reconstructed input_
> <img src="https://github.com/Martinmbiro/standard-autoencoder/raw/refs/heads/main/plots/x_vs_x'.png" alt="x vs x'" width=650/>

+ _Sampled latent space_
> <img src="https://github.com/Martinmbiro/standard-autoencoder/raw/refs/heads/main/plots/latent_space_sampled.png" alt="sampled_latent_space" width=650/>

+ _Latent space in 2D & 3D_

|      |       |
| :--- | :---: |
| <img src="https://github.com/Martinmbiro/standard-autoencoder/raw/refs/heads/main/plots/latent_space_2d.png" alt="latent_space_2d" width=390/> | <img src="https://github.com/Martinmbiro/standard-autoencoder/raw/refs/heads/main/plots/latent_space_3d.png" alt="latent_space_3d" width=400/> |
<br>

## Roadmap 🎌
<center>
<img src='https://github.com/Martinmbiro/standard-autoencoder/raw/refs/heads/main/plots/roadmap.png' alt='auto_encoder_sketch' width=800/>
</center>
<p align='center'><i>This repository is part of a roadmap for understanding Generative Computer Vision</i></p>

## References 📚
+ [Autoencoder from scratch in 60 minutes](https://www.youtube.com/watch?v=MLAZu2mRbwk&t=3334s&pp=ygUTYXV0b2VuY29kZXIgdml6dWFyYQ%3D%3D) - by [Vizuara AI Labs](https://vizuara.ai/)
+ [What are Autoencoders?](https://www.youtube.com/watch?v=qiUEgSCyY5o&pp=ygUPYXV0b2VuY29kZXIgaWJt) - by [IBM](https://www.youtube.com/@IBMTechnology)
+ [Intro to Autoencoders](https://www.tensorflow.org/tutorials/generative/autoencoder)


