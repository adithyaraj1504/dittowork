# Ditto Model Codes Repository

This repository contains experimental code implementations for operator learning, comparing **Proposed** architectures (such as Fast U-Net variants) against **Existing / Baseline** models across various partial differential equation (PDE) benchmark systems.

## 🧪 Benchmark Systems
- **System 1:** 1-D Wave Propagation
- **System 2:** Gray-Scott Reaction-Diffusion Equation
- **System 3:** Modified Shallow Water PDE

---

## 📂 Repository File Index & Descriptions

### **System 1: 1-D Wave Propagation**
- unet-1st-system-series.ipynb — Existing U-Net model evaluated on System 1 in a series configuration.
- unet_1st_system_parallel.ipynb — Existing U-Net model evaluated on System 1 in a parallel configuration.
- fast-unet-system-1-parallel.ipynb — **[Proposed]** Fast U-Net model evaluated on System 1 in a parallel configuration.
- fast_unet_model_4_models_system_1_(series)_.ipynb — **[Proposed]** Fast U-Net model configured with System 1 PDE in a series setup using 4 models with random weights.

### **System 2: Gray-Scott Equation**
- unet-2nd-system-parallel.ipynb — Existing U-Net model evaluated on System 2 in a parallel configuration.
- fast-unet-system-2-parallel.ipynb — **[Proposed]** Fast U-Net model evaluated on System 2 in a parallel configuration.
- unet-model-4-models-system-2-series.ipynb — Existing Ditto model configured with System 2 PDE in a series setup using 4 models with random weights.
- fast-unet-model-4-models-system-2-series.ipynb — **[Proposed]** Ditto model configured with System 2 PDE in a series setup using 4 models with random weights.

### **System 3: Modified Shallow Water PDE**
- unet-3rd-system-parallel-ipynb.ipynb — Existing U-Net / Ditto model evaluated on System 3 in a parallel configuration with 4 models in random weights.
- fast_Unet_system_3_parallel.ipynb — **[Proposed]** Fast U-Net model evaluated on System 3 in a parallel configuration.
- Unet_model_4_models-system-3-(series).ipynb — Existing Ditto model configured with System 3 PDE in a series setup using 4 models with random weights.
- fast-unet-model-4-models-system-3-series.ipynb — **[Proposed]** Ditto model configured with System 3 PDE in a series setup using 4 models with random weights.
