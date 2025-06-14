---
title: "PIMILab - Research"
layout: textlay
excerpt: "PIMILab -- Research"
sitemap: false
permalink: /research/
---

# Research

Our group focuses on integrating the fundamental structure of physics and mathematics into machine learning architectures. By embedding principles from geometric mechanics, exterior calculus, and variational methods into neural networks, we develop models that are both expressive and scientifically grounded. This approach allows us to construct AI systems capable of operating in extreme physical regimes, where traditional first-principles modeling becomes intractable.

We aim to bridge the gap between rigorous mathematical modeling and data-driven discovery, enabling tools for scientific inference, digital twins, and autonomous experimentation. Our work spans a wide range of multiscale and multiphysics domains—including energy systems, climate science, fusion power, and soft matter—where we develop learning algorithms inspired by finite element discretizations and graph-based representations. At the core of our mission is a belief that combining structure and learning will unlock the next generation of predictive, interpretable AI for science and engineering.

Here are some themes and techniques that we currently work on:

![]({{ site.url }}{{ site.baseurl }}/images/teaser/teaser1.png){: style="width: 250px; float: left; margin: 0px 10px"}
**Structure-Preserving Particle Dynamics Simulation**: We develop particle-based simulation tools that preserve the geometric and physical structure of the underlying dynamical systems. Traditional numerical methods often introduce artificial dissipation or break symmetries, leading to inaccurate long-term behavior. By contrast, our methods are grounded in variational integrators and geometric mechanics, ensuring the conservation of key quantities like momentum, energy, and symplectic structure. These tools are especially well-suited to systems with complex interactions—such as multiphase flows, granular media, or plasmas—where accurate long-time integration is essential for discovering emergent behavior. We are actively working on extending these methods to hybrid particle-field representations and incorporating them into differentiable simulators for scientific machine learning.

![]({{ site.url }}{{ site.baseurl }}/images/teaser/teaser.png){: style="width: 250px; float: right; margin: 0px 10px"}
**Structure-Preserving Models Based on Whitney Forms**: We leverage the mathematical framework of Whitney forms and discrete exterior calculus to construct structure-preserving neural network architectures that are compatible with physical laws. These methods translate ideas from finite element exterior calculus into a form that is naturally suited to graph-based learning and message passing. By encoding topological invariants, conservation laws, and differential constraints directly into the architecture, our models can learn from data in a way that respects the underlying physics. This line of research forms a bridge between classical numerical discretizations and modern machine learning, offering new avenues for high-fidelity, generalizable modeling in settings such as electromagnetism, elasticity, and fluid dynamics.

![]({{ site.url }}{{ site.baseurl }}/images/teaser/teaser.png){: style="width: 250px; float: left; margin: 0px 10px"}
**Learning Physical Models from Data**: In many complex systems, a full first-principles derivation is either impossible or computationally intractable. Our group develops methods for learning effective physical models directly from data while preserving the mathematical structure of the governing equations. These models, which include graph neural networks, variational autoencoders, and probabilistic surrogates, are informed by ideas from geometric mechanics and multiscale modeling. We apply these techniques to construct probabilistic digital twins and to perform autonomous scientific discovery in a range of domains, including combustion, fusion, energy storage, and soft matter. Our goal is not just predictive performance, but interpretability, reliability, and scientific insight.


