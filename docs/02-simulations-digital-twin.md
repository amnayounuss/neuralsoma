---
sidebar_position: 2
title: "Module 2: Simulations – Creating the Digital Twin"
---

# Module 2: Simulations – Creating the Digital Twin

In Physical AI, we never test directly on expensive hardware. We build a **Digital Twin** in a high-fidelity simulation environment to verify algorithms safely.

## 2.1 The Necessity of Simulation
Humanoid hardware is fragile and costly. Testing a new balancing algorithm on a physical robot can lead to expensive falls. Simulation allows for:
- **Infinite Iteration:** Test 1,000 walking cycles in minutes.
- **Extreme Conditions:** Simulate stairs, ice, or uneven terrain without risk.

## 2.2 Core Simulation Engines
- **Gazebo:** The industry standard for ROS 2. It provides robust physics and sensor simulation.
- **Unity/Unreal Engine:** Used for photorealistic environments to train Vision models.

## 2.3 Physics Engines (ODE, Bullet, MuJoCo)
The "Brain" of the simulation is the Physics Engine. It calculates gravity, friction, and torque. For humanoids, **MuJoCo** is often preferred for its superior handling of multi-joint contacts.

---
<button className="button button--primary" onClick={() => alert('Translating...')}>Translate to Urdu</button>