## Project Overview

This project implements an AI-based pipeline that automatically generates
3D object files from text or image inputs and renders them in a 3D scene.

By leveraging OpenAI's Shap-E pre-trained model, the system converts textual
prompts or input images into 3D latent representations, which are then
exported as 3D object files. These generated models are integrated into an
OpenGL-based rendering engine for visualization.

To support seamless integration, the rendering engine was modified to handle
newly generated object files, including on-the-fly vertex normal computation
when normal data is missing. The project was designed to run on a GPU server
due to the high computational cost of 3D diffusion models.

This work aims to lower the barrier to 3D content creation by combining
AI-driven 3D generation with traditional graphics rendering pipelines.

## Acknowledgements

This project is based on and inspired by OpenAI's Shap-E project,
which is released under the MIT License.

Copyright (c) 2023 OpenAI
