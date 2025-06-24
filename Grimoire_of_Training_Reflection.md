## ✍️ Introduction

This project explored the fundamentals of optimization in neural networks—from learning about gradient descent and learning rate schedules to loss functions and visualization tools. It served to bridge theoretical concepts with practical training behaviors.

---

### 🔢 Stage 1: Gradient Intuition

- **What I did**: Plotted \( f(x) = x^2 \) and observed gradients visually.
- **What I learned**:
  - Gradient = function slope.
  - Small gradients → slow updates.
  - Steep slopes → faster descent with risk of overshooting.
- **New understanding**:
  - Optimization is extremely sensitive to the loss surface shape.

---

### ⚙️ Stage 2: Learning Rate Schedules

- **What I did**: Trained models using fixed learning rate and `OneCycleLR`.
- **What I learned**:
  - Fixed LR works, but can plateau or overshoot.
  - OneCycleLR accelerates convergence and supports better generalization.
- **Reflections**:
  - Learning rate schedulers aren't fancy tricks—they have a drastic impact on training quality.

---

### 🧠 Stage 3: Visualization

- **What I did**: Used tools like `torchviz`, `loss-landscapes`, etc.
- **What I learned**:
  - Visualizing gradients helped detect vanishing/exploding gradients.
  - Loss surfaces are often bumpy and non-convex—unlike textbook examples.
- **Insight**:
  - Diagnostic tools are vital for real-world debugging and model training.

---

### 📉 Stage 4: Loss Function Dynamics

- **What I did**: Compared **MSE** and **CrossEntropy** on the same task.
- **What I learned**:
  - MSE is suited for regression, not classification.
  - CrossEntropy gradients remain stable even with saturated predictions.
- **Takeaway**:
  - Choosing the right loss function is critical—not just a technical detail.

---

### 🪞 Stage 5: Summary Reflection

With this project, I now view optimization not just as "minimizing loss," but as a **delicate interplay of hyperparameters, schedules, gradients, and architecture**.

- Visual tools like OneCycleLR plots, `torchviz`, and loss landscapes helped turn abstract math into concrete understanding.
- My perspective on gradients shifted—from memorizing derivatives to appreciating their real impact on training behavior.
- I will apply these insights in future projects—especially for:
  - Fine-tuning models
  - Diagnosing training bottlenecks
  - Designing more effective training routines with confidence and intuition

---




