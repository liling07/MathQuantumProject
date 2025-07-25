---
title: "Posts by Category"
layout: categories
permalink: /categories/
author_profile: true
---
## ⚛️ Quantum Cryptography Timeline + Concepts

| Year       | Event            | Description                                                                 |
|------------|------------------|-----------------------------------------------------------------------------|
| 1984       | BB84 Protocol    | Developed by Bennett and Brassard, this was the first practical quantum key distribution (QKD) protocol. It relies on the quantum properties of photons to exchange encryption keys securely. Any attempt to intercept the key changes the quantum state and is thus detectable. |
| 1991       | Ekert Protocol   | Artur Ekert’s protocol introduced entanglement-based key exchange using Bell inequalities. It further demonstrated the potential of quantum mechanics to ensure secure communication, exploiting quantum nonlocality for increased verification and security. |
| 2000s–Now  | Quantum Networks | Rapid developments in real-world QKD include fiber-based networks in cities and satellite-based communication experiments, such as China’s Micius satellite. These implementations bring quantum-secure communication closer to practical use. |

**Mechanics Behind BB84:** The BB84 protocol encodes bits into the quantum states of photons using two bases: rectilinear (|0⟩, |1⟩) and diagonal (|+⟩, |−⟩). Only matching bases between sender and receiver produce usable bits. Attempts to intercept the photons disturb the states and reveal the intrusion.

**Quantum Principles:** Superposition (a qubit can be in multiple states), entanglement (linked particles affect each other at a distance), and the no-cloning theorem (you can’t copy a quantum state) form the core of quantum cryptography’s security.

**Image:**  
![BB84 Protocol](/assets/images/BB84.png)

