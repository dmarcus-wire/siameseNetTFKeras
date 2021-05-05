# Siamese Networks


[!image](./images/siamese-network.png)

- results in similarity between 0 and 1 to identify commonality between inputs
- Using image pairs (2 inputs) to train your network
- Triplete pairs (2 of same class, 1 other), the network works off commonality

```
.
├── README.md
├── main.ipynb
├── main.py 
├── output # populated with train/loss accuracy
│   ├── plot.png
│   └── siamese_model # serialized weights and arch files
│       ├── saved_model.pb
│       └── variables
│           ├── variables.data-00000-of-00001
│           └── variables.index
├── requirements.txt
├── submodules
│   ├── config.py 
│   ├── siamese_network.py # implementation of sister networks
│   └── utils.py # generates image pairs
└── train_siamese_network.py

```