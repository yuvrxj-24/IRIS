# Neural Network Regularization & Optimizer Comparison with the Iris Dataset

📌 Overview
In this project, I explored the impact of different regularization techniques and optimizers on a neural network trained on the Iris dataset. The primary goal was to understand how regularization methods affect overfitting and how different optimizers impact convergence speed.

📝 Project Highlights
✅ Built a **baseline model** without regularization.  
✅ Implemented models with **L1 Regularization**, **L2 Regularization**, and **Dropout**.  
✅ Compared optimizers: **Adam, Momentum, and RMSProp**.  
✅ Visualized training loss curves for all models.  
✅ Analyzed convergence behavior of optimizers.

---

📂 Dataset
The Iris dataset** contains 150 samples of iris flowers categorized into three classes:
- Setosa
- Versicolor
- Virginica

Each sample has four features**:
- Sepal length
- Sepal width
- Petal length
- Petal width

The target labels were one-hot encoded for multi-class classification.

----


🔹 Results & Observations
- Momentum & RMSProp converged faster than Adam
- Adam combines both methods, but the slow convergence of Momentum affected its performance.
- RMSProp performed the best in terms of speed.

---

📊 Results
📉 Loss vs. Epochs for Different Regularization Techniques
![Loss vs Epochs](./loss_vs_epochs.png)

📉 Optimizer Convergence Analysis
![Optimizer Convergence](./optimizer_comparison.png)

---

🎯 Key Takeaways
- Regularization prevents overfitting but impacts model convergence.
- Dropout improves generalization but requires tuning.
- Adam’s slower convergence is due to its dependency on Momentum and RMSProp.
- RMSProp achieved the best convergence speed.

---

🏆 Conclusion
This project helped me understand the practical trade-offs between regularization techniques and optimizers. Fine-tuning these aspects is crucial for building robust deep-learning models!

🔗 Let’s connect! If you have any insights or suggestions, feel free to open an issue or fork this repo. 🚀


