---
title: "NaviTrace: Evaluating Embodied Navigation of Vision-Language Models"
description: "NaviTrace is a novel VQA benchmark for VLMs that evaluates models on their embodiment-specific understanding of navigation across challenging real-world scenarios."
url: https://leggedrobotics.github.io/navitrace_webpage/
authors: ["Tim Windecker", "Manthan Patel", "Moritz Reuss", "Richard Schwarzkopf", "Cesar Cadena", "Rudolf Lioutikov", "Marco Hutter", "Jonas Frey"]
publisher: IEEE International Conference on Robotics and Automation 2026 (ICRA)
date: "2025-10-30"
image: {
url: "/navitrace.png",
alt:  "NaviTrace overview"
}
---

## Abstract

Vision–language models demonstrate unprecedented performance and generalization across a wide range of tasks and scenarios. Integrating these foundation models into robotic navigation systems opens pathways toward building general-purpose robots. Yet, evaluating these models’ navigation capabilities remains constrained by costly real-world trials, overly simplified simulations, and limited benchmarks. We introduce NaviTrace, a high-quality Visual Question Answering benchmark where a model receives an instruction and embodiment type (human, legged robot, wheeled robot, bicycle) and must output a 2D navigation path in image space, which we call a trace. Across 1000 scenarios and more than 3000 expert traces, we systematically evaluate eight state-of-the-art VLMs using a newly introduced semantic-aware trace score. This metric combines Dynamic Time Warping distance, goal endpoint error, and embodiment-conditioned penalties derived from per-pixel semantics and correlates with human preferences. Our evaluation reveals consistent gap to human performance caused by poor spatial grounding and goal localization. NaviTrace establishes a scalable and reproducible benchmark for real-world robotic navigation. 
