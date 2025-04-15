# Q-Prop Demo 🧠📉

This project provides a PyTorch implementation of the **Q-Prop** algorithm for continuous control, demonstrated on the `Pendulum-v1` environment from OpenAI Gym.

Q-Prop is a hybrid reinforcement learning method that combines:
- **Deterministic critic-based learning** (like DDPG)  
- **Stochastic policy gradients** (like REINFORCE)  
with variance reduction through **Taylor expansion** and **covariance-based control variates**.

---

## 🔍 Highlights

- ✅ Implements a simplified version of Q-Prop
- ✏️ Advantage estimation via baseline Q-value
- 📉 KL-divergence regularization for stable updates
- 📊 Live tracking of episode returns and Q-values

---

## 🧪 Requirements

- Python 3.8+
- PyTorch
- NumPy
- Matplotlib
- Gym
