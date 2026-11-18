# Awesome-3D-Point-Cloud-Diffusion-Generative-3D

# Top 3D Point Cloud Diffusion & Generative 3D Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Point Cloud Diffusion Transformers, Monocular Geometry Estimation, 3D Gaussian Splatting & LiDAR/Photogrammetry Reconstruction*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **3D Point Cloud Diffusion & Generative 3D**. These tools generate dense 3D point clouds and textured meshes from text or single images, denoise raw 3D point maps in pixel space, reconstruct real-world LiDAR/photogrammetry scans, and render real-time 3D Gaussian Splats.

**Examples** include Luma AI, Polycam, Scaniverse, Jawset Postshot, KIRI Engine, Gracia AI, Spline, Artec Cloud, Nerfstudio, SuperSplat, and google-research/pointdit (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for point-cloud diffusion models, pixel-space geometry diffusion, local 3DGS training/editing, and large-scale point-cloud processing/rendering — ideal for 3D computer vision researchers, spatial AI engineers, graphics programmers, and 3D capture artists.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Luma AI](https://lumalabs.ai)**  
  Cloud AI 3D capture and generative platform turning smartphone videos and text prompts into photorealistic 3D Gaussian Splats, point clouds, and meshes.

- **[Polycam](https://poly.cam)**  
  Cross-platform mobile and web 3D scanning suite supporting LiDAR point-cloud capture, photogrammetry, cloud 3D Gaussian Splatting, and browser sharing.

- **[Niantic Scaniverse](https://scaniverse.com)**  
  Mobile spatial scanning app offering on-device 3D Gaussian Splatting and dense point-cloud capture, editing, and geospatial world mapping.

- **[Jawset Postshot](https://jawset.com)**  
  High-speed 3D Gaussian Splatting and radiance field workstation featuring live training previews, ACES color pipelines, and Unreal Engine / After Effects plugins.

- **[KIRI Engine](https://kiriengine.app)**  
  Cloud 3D scanning and Gaussian Splatting platform providing mobile photo-to-3D capture, splat-to-mesh conversion, quad-retopology, and Blender integration.

- **[Gracia AI](https://gracia.ai)**  
  Spatial computing platform for publishing, streaming, and experiencing photorealistic 6DoF volumetric 3D Gaussian Splatting scenes across VR headsets and web.

- **[Spline (3DGS & AI)](https://spline.design)**  
  Collaborative browser-based 3D design studio supporting imported 3D Gaussian Splats, generative 3D assets, interactive lighting, and instant WebGL embeds.

- **[Artec Cloud](https://artec3d.com)**  
  Cloud-based 3D scan processing, point-cloud alignment, mesh reconstruction, and collaborative inspection platform built for professional 3D scanners.

- **[Pointly / Cintoo Cloud](https://cintoo.com)**  
  Cloud reality-capture and point-cloud management SaaS platforms enabling browser-native streaming, AI semantic classification, and CAD/BIM comparison of massive LiDAR scans.


## Open-Source GitHub Projects

- **[google-research/pointdit](https://github.com/google-research/pointdit)**  
  ICML 2026 open-source minimalist pixel-space Diffusion Transformer (`ViT`) conditioned on frozen `DINOv3` tokens that directly denoises raw 3D point map patches without lossy VAE bottlenecks.

- **[OpenAI Point-E (`openai/point-e`)](https://github.com/openai/point-e)**  
  Official open-source (`MIT`) two-stage diffusion pipeline from OpenAI that synthesizes synthetic views and generates colored 3D point clouds and SDF meshes from text or images.

- **[Nerfstudio](https://github.com)**  
  Modular open-source (`Apache-2.0`) PyTorch framework unifying 3D Gaussian Splatting (`splatfacto`), NeRFs, COLMAP/GLOMAP pose estimation, and an interactive real-time web viewer.

- **[SuperSplat (PlayCanvas)](https://github.com)**  
  Free and open-source (`MIT`) browser-based 3D Gaussian Splatting editor and optimizer for inspecting, cropping, cleaning floaters, and compressing `.ply` / `.sog` splats.

- **[LION (`nv-tlabs/LION`)](https://github.com)**  
  NVIDIA NeurIPS open-source Hierarchical Latent Point Diffusion model combining a Point-Voxel VAE with dual latent diffusion models for high-resolution 3D shape generation and voxel/text conditioning.

- **[Diffusion Point Cloud (`luost26/diffusion-point-cloud`)](https://github.com/luost26/diffusion-point-cloud)**  
  Foundational CVPR 2021 open-source probabilistic diffusion model for 3D point cloud generation, auto-encoding, shape completion, and upsampling.

- **[PVD (`alexzhou907/PVD`)](https://github.com)**  
  ICCV 2021 open-source Point-Voxel Diffusion framework unifying point-level and voxel-level representations for 3D shape generation and partial point-cloud completion.

- **[SPVD (`JohnRomanelis/SPVD`)](https://github.com/johnromanelis/spvd)**  
  TNNLS 2025 open-source Sparse Point-Voxel Diffusion framework leveraging TorchSparse for scalable unconditional/conditional point cloud generation, completion, and super-resolution.

- **[DiffFacto (`diffFacto/diffFacto`)](https://github.com/diffFacto/diffFacto)**  
  ICCV 2023 open-source (`MIT`) controllable part-based 3D point cloud generation model using cross-diffusion to factor independent part styles and spatial configurations.

- **[SLIDE (`SLIDE-3D/SLIDE`)](https://github.com/SLIDE-3D/SLIDE)**  
  Open-source Sparse Latent Point Diffusion model that encodes 3D shapes into sparse latent points with features for controllable point-cloud and Shape-As-Points mesh generation.

- **[GaussianAnything (`NIRVANALAN/GaussianAnything`)](https://github.com)**  
  ICLR 2025 open-source cascaded 3D native diffusion pipeline using a point-cloud structured latent space to generate editable 3D assets from text, point clouds, or images.

- **[DUSt3R & MASt3R (`naver/dust3r`)](https://github.com)**  
  Open-source dense 3D pointmap reconstruction models capable of recovering calibrated 3D point clouds and camera poses from uncalibrated image pairs without prior intrinsics.

- **[Open3D (`isl-org/Open3D`)](https://github.com)**  
  Modern open-source (`MIT`) C++ and Python library for 3D point-cloud processing, ICP registration, Poisson/Ball-Pivoting surface reconstruction, and GPU visualization.

- **[CloudCompare](https://github.com)**  
  Industry-standard open-source (`GPL-2.0+`) desktop 3D point cloud and triangular mesh processing software for massive LiDAR registration, segmentation, and distance computation.

- **[Potree](https://github.com)**  
  Free open-source (`BSD-2-Clause`) WebGL point cloud renderer engineered to stream and visualize multi-billion-point LiDAR and photogrammetry datasets directly in browsers.

### Additional Strong Open-Source Options

- **[Dekai21/Awesome-Point-Cloud-Generation](https://github.com/Dekai21/Awesome-Point-Cloud-Generation)** for a curated chronological index of point-cloud diffusion, flow-matching, and autoregressive papers (`DiT-3D`, `TIGER`, `PSF`, `SeaLion`).
- **[Point Cloud Library (PCL)](https://github.com)** and **[PDAL (Point Data Abstraction Library)](https://github.com)** for industrial-grade C++ point cloud filtering, KD-tree spatial indexing, and LAS/LAZ geospatial pipelines.
- **[gsplat](https://github.com)** and **[Brush (`ArthurBrussee/brush`)](https://github.com)** for high-speed CUDA and cross-platform Rust/WebGPU 3D Gaussian Splatting training and rasterization.
- **[Microsoft TRELLIS](https://github.com)** and **[Tencent Hunyuan3D-2](https://github.com)** for downstream structured latent and diffusion-based textured mesh synthesis.
- **[rerun.io (`rerun-io/rerun`)](https://github.com)** for high-performance open-source multimodal visualization of streaming 3D point clouds, depth maps, and spatial AI telemetry.

**Frameworks for building custom systems**: Combine **google-research/pointdit** or **OpenAI Point-E** with **DUSt3R**, **Nerfstudio (`gsplat`)**, **Open3D**, and **Potree / SuperSplat** for end-to-end open-source point cloud diffusion and generative 3D pipelines.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Point cloud diffusion transformers (such as `PointDiT`, `Point-E`, and `LION`) require compatible PyTorch/CUDA environments, and gated backbone weights (such as `DINOv3` for PointDiT) must be requested separately from upstream providers.
- Verify individual software, dataset, and model weight licenses (`MIT`, `Apache-2.0`, `BSD-2-Clause`, `GPL-2.0+`, or research-only terms) before commercial deployment.

---

**Made for 3D computer vision researchers, spatial AI engineers, graphics programmers, and reality-capture specialists.**  
Let's make 3D point cloud diffusion and generative 3D modeling more open, accurate, and accessible.
