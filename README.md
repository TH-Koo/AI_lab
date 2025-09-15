# AI_lab

- Taehwan Koo 2023078074
- 2025-2 Artificial Intelligence

---

## Development Environment

### Hardware
- **GPU**: NVIDIA GeForce RTX 4050 6GB
- **CUDA Support**: Available (1 device)

### Software Stack
- **Python**: 3.11.13
- **PyTorch**: 2.8.0 + cu129 (CUDA-enabled)
- **Jupyter Notebook**: Configured and operational

---

## Environment Status ✅
- ✔️ PyTorch successfully imported and functional  
- ✔️ CUDA acceleration available  
- ✔️ Tensor operations working correctly  
- ✔️ GPU-accelerated deep learning ready  

---

## Quick Environment Check

Run the following snippet in your notebook or terminal to verify PyTorch installation and CUDA availability:

```python
import torch

print("PyTorch version:", torch.__version__)
print("CUDA available:", torch.cuda.is_available())
print("Device name:", torch.cuda.get_device_name(0))
