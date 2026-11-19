# Matthew Flake

**ComfyUI workflow designer & technical AI artist.**
I build tested, repeatable generative pipelines, from the node graph to the API and batch automation.
Author of two books on ComfyUI, with an engineering background in renewable energy.

> *Matthew Flake* is the pen name I publish my ComfyUI books under. I keep personal details off public profiles, so everything here is about the work.

📍 Poland (CET)

---

### Portfolio 2026

[![Portfolio 2026: every image and page made in ComfyUI](https://github.com/matthew-flake/portfolio/raw/main/pages/01_cover.png)](https://github.com/matthew-flake/portfolio)

Three small projects: a stylised character with consistent scenes, a sketch-to-render house with rooftop PV, and one product shown in three campaign looks. Every image and every page of the layout was made in ComfyUI on an 8 GB GPU, and the workflow for each one is in the repo.
→ [**matthew-flake/portfolio**](https://github.com/matthew-flake/portfolio) · [PDF](https://github.com/matthew-flake/portfolio/raw/main/matthew-flake-portfolio-2026.pdf)

### What I do

- **Workflows:** text-to-image, img2img, inpainting / outpainting, ControlNet, LoRA, consistent characters with reference latents, hi-res fix, 4× print upscaling, seamless textures, background removal
- **Workflows as code:** workflows generated from Python schemas, shipped in UI and API format, with checksums and versions
- **Automation:** batch runs through the ComfyUI `/prompt` API, CSV-driven series, release scripts
- **QA & licensing:** every workflow tested end to end, with a written report; model licences checked before commercial use

### Repositories

| Repository | What it shows |
|---|---|
| [portfolio](https://github.com/matthew-flake/portfolio) | 12 images and 6 layout pages, all made in ComfyUI, with one API workflow per image (Z-Image-Turbo, FLUX.2 [klein] 4B) |
| [from-noise-to-income](https://github.com/matthew-flake/from-noise-to-income) | 21 tested ComfyUI projects (Z-Image-Turbo, FLUX.2 [klein]), plus a batch script and a release script |
| [node-by-node](https://github.com/matthew-flake/node-by-node) | 11 teaching workflows, from the first image to a full pipeline |

### Reproducibility

Each repository includes a test report (`TESTED.md`) and a list of the exact model files (`MODELS.md`). The book packs also include checksums (`SHA256SUMS.txt`). Every workflow is provided in API format, so any result can be rebuilt from its repository.

### Setup

Everything here, from the book examples and companion packs to the portfolio pieces, was made and tested on one local machine:

| Component | Spec |
|---|---|
| CPU | Intel Core i5-14400F |
| RAM | 32 GB |
| GPU | NVIDIA GeForce RTX 5060, 8 GB VRAM |
| OS | Windows 11, 64-bit |
| Software | ComfyUI 0.39, Python 3.12 |

All workflows are tuned to run on 8 GB VRAM, with no cloud GPU needed.

### Books

- **Node by Node.** ComfyUI from Your First Image to Your Own Workflow (2026). Polish edition: *Węzeł po węźle*
- **From Noise to Income.** The ComfyUI Handbook (2026)

### Tools

ComfyUI · ComfyUI API · Z-Image-Turbo · FLUX.2 [klein] · SDXL · ControlNet · LoRA · Python · Git
