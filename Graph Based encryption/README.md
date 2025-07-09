# 🔐 Graph Theory-Based Encryption and Decryption Using SageMath

This project explores the use of graph theory for secure message encryption and decryption, leveraging SageMath for generating and manipulating graphs. Without relying on traditional cryptographic algorithms or programming logic, the approach uses mathematical properties of graphs to encode information securely.

## 📌 Objectives

- Apply graph labeling techniques (e.g., Harmonious Labeling) to encode messages
- Use Partial and Standard Complement graphs to increase encryption complexity
- Demonstrate encryption/decryption through graph transformations using SageMath

## 🧠 Graph Concepts Used

- **Harmonious Labeling**: Assigns unique labels to vertices such that edge labels (sum mod k) are distinct, allowing consistent message encoding.
- **Partial Complement**: Only certain subgraphs are complemented to obscure the graph’s structure.
- **Standard Complement**: Complements the entire graph to fully disrupt adjacency and increase complexity.

## 🛠 Tools & Technologies

- **SageMath** – Used for generating, labeling, and transforming graphs
- **LaTeX / TikZ** – Used for visualizing and documenting graph structures
- No programming or scripting was used beyond SageMath commands

## 📊 Project Overview

- Graphs are used as the basis for encrypting each character of a message.
- A unique labeled graph (e.g., with harmonious labeling) is generated for each segment of the message.
- Graph complements (partial/standard) serve as keys for encryption.
- Decryption involves reversing transformations and interpreting labels to recover the message.



