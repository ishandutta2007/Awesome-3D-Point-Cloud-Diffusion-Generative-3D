# Awesome-3D-Point-Cloud-Diffusion-Generative-3D

## Top 3D Point Cloud Diffusion & Generative 3D Ecosystem



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



## Sector Overview & Market Dynamics

The global market for Generative AI in 3D assets and reality capture is currently valued between **.5 billion and .2 billion**, accelerating at a CAGR exceeding 35% toward an estimated **.4+ billion** by the early 2030s. The sector remains **highly fragmented** rather than winner-take-all, driven by distinct vertical requirements across autonomous robotics (metric LiDAR accuracy), AEC/BIM digital twins (massive cloud point-cloud processing), spatial computing/XR (4D Gaussian Splatting), and real-time gaming (lightweight textured meshes and diffusion transformers).

## SaaS/Hosted Platforms

| Platform | Valuation / Revenue | Starting Pricing | Free Tier Limits | Key Capabilities |
| :--- | :--- | :--- | :--- | :--- |
| **[Niantic Scaniverse](https://scaniverse.com)** | .0B Valuation / ~ Revenue (Parent Niantic) | /month (Plus plan) | Free forever on mobile; unlimited on-device 3D Gaussian Splatting & point-cloud capture/export, 20,000 monthly cloud credits | On-device 3D Gaussian Splatting, LiDAR capture, WebGL sharing, and geospatial mesh processing |
| **[Luma AI](https://lumalabs.ai)** | .0B Valuation / ~ ARR | /month (Plus tier, 10,000 credits/mo) | Free forever; ~80 daily generation credits for low-volume video & 3DGS testing | Cloud 3D Gaussian Splatting, Dream Machine generative video, and text/image-to-3D asset synthesis |
| **[Polycam](https://poly.cam)** |  Valuation / ~.5M ARR | /month (/year Pro tier) | Free forever; unlimited LiDAR/room scanning with basic GLTF export (point cloud & CAD export restricted) | Smartphone LiDAR scanning, photogrammetry, 3DGS, and instant browser floor plan generation |
| **[Cintoo Cloud](https://cintoo.com)** |  Valuation / ~.7M ARR | ,800/year (bundles of 500 scans) | 30-day free trial; maximum 20 scan uploads and unlimited 3D/BIM model imports | Reality capture SaaS streaming massive LiDAR point clouds as high-fidelity TurboMesh™ with CAD/BIM alignment |
| **[Spline (3DGS & AI)](https://spline.design)** |  Valuation / ~.5M ARR | /editor/month (/mo billed monthly) | Free forever; unlimited personal 3D files and viewers (exports include Spline watermark) | Browser-based 3D design studio supporting imported 3D Gaussian Splats, AI 3D gen, and WebGL embeds |
| **[Artec Cloud](https://artec3d.com)** | €15M EIB Venture Debt / ~.8M Revenue | /year (~/mo, 200 GB tier) | Free forever; 5 GB free cloud storage for scan uploads, 3D viewing, and team commenting | Cloud photogrammetry and industrial LiDAR scan processing, point-cloud alignment, and mesh reconstruction |
| **[Pointly](https://pointly.ai)** | Private (Supper & Supper GmbH) | €99/month (Professional S tier, 500 MPoints) | Free forever; 15 million points (15 MPoints) upload limit with pre-trained AI classifiers | Cloud 3D point cloud classification, aerial LiDAR segmentation, and automated feature extraction |
| **[Jawset Postshot](https://jawset.com)** | Private / Bootstrapped | €17/month (~.50/mo Indie tier, billed annually) | Free forever; unlimited images & model size (non-commercial only, watermarked, locked exports) | Desktop NeRF & 3D Gaussian Splatting workstation with live previews and Unreal Engine / After Effects plugins |
| **[Gracia AI](https://gracia.ai)** | .9M Seed Funding / Pre-ARR | ~/minute of processed 4DGS content | Free forever for VR Viewer on Steam, Meta Quest, and Apple Vision Pro (pilot trials for creators) | 6DoF volumetric 4D Gaussian Splatting streaming pipeline for photorealistic VR and spatial computing |

## Open-Source GitHub Projects

A curated index of open-source repositories for 3D point cloud diffusion, generative 3D modeling, Gaussian Splatting, and LiDAR reality capture—strictly ranked by GitHub star count.

- **[3D Gaussian Splatting (`graphdeco-inria/gaussian-splatting`)](https://github.com/graphdeco-inria/gaussian-splatting)** [![GitHub stars](https://img.shields.io/github/stars/graphdeco-inria/gaussian-splatting?style=social&color=white)](https://github.com/graphdeco-inria/gaussian-splatting/stargazers)  
  Foundational SIGGRAPH 2023 3D Gaussian Splatting project for real-time radiance field rendering, rasterization, and rapid novel view synthesis.

- **[Tencent Hunyuan3D 2.0 (`Tencent-Hunyuan/Hunyuan3D-2`)](https://github.com/Tencent-Hunyuan/Hunyuan3D-2)** [![GitHub stars](https://img.shields.io/github/stars/Tencent-Hunyuan/Hunyuan3D-2?style=social&color=white)](https://github.com/Tencent-Hunyuan/Hunyuan3D-2/stargazers)  
  Advanced high-resolution 3D asset generation system synthesizing production-grade textured meshes and geometric shapes from single images or text prompts.

- **[TRELLIS (`microsoft/TRELLIS`)](https://github.com/microsoft/TRELLIS)** [![GitHub stars](https://img.shields.io/github/stars/microsoft/TRELLIS?style=social&color=white)](https://github.com/microsoft/TRELLIS/stargazers)  
  Microsoft open-source structured latent diffusion model for fast, high-quality 3D asset generation across Radiance Fields, 3D Gaussians, and meshes.

- **[Open3D (`isl-org/Open3D`)](https://github.com/isl-org/Open3D)** [![GitHub stars](https://img.shields.io/github/stars/isl-org/Open3D?style=social&color=white)](https://github.com/isl-org/Open3D/stargazers)  
  Modern open-source (MIT) C++ and Python library for 3D point cloud processing, ICP alignment, Poisson surface reconstruction, and hardware-accelerated visualization.

- **[Nerfstudio (`nerfstudio-project/nerfstudio`)](https://github.com/nerfstudio-project/nerfstudio)** [![GitHub stars](https://img.shields.io/github/stars/nerfstudio-project/nerfstudio?style=social&color=white)](https://github.com/nerfstudio-project/nerfstudio/stargazers)  
  Modular open-source (Apache-2.0) PyTorch framework unifying 3D Gaussian Splatting (splatfacto), NeRFs, camera pose estimation, and real-time web viewers.

- **[Rerun (`rerun-io/rerun`)](https://github.com/rerun-io/rerun)** [![GitHub stars](https://img.shields.io/github/stars/rerun-io/rerun?style=social&color=white)](https://github.com/rerun-io/rerun/stargazers)  
  High-performance visual data SDK for streaming, logging, and interactively visualizing multimodal 3D point clouds, spatial sensor streams, and computer vision data.

- **[Point Cloud Library (`PointCloudLibrary/pcl`)](https://github.com/PointCloudLibrary/pcl)** [![GitHub stars](https://img.shields.io/github/stars/PointCloudLibrary/pcl?style=social&color=white)](https://github.com/PointCloudLibrary/pcl/stargazers)  
  Comprehensive, standalone, large-scale open-source C++ framework for 2D/3D point cloud and image processing, KD-tree indexing, and feature estimation.

- **[SuperSplat (`playcanvas/supersplat`)](https://github.com/playcanvas/supersplat)** [![GitHub stars](https://img.shields.io/github/stars/playcanvas/supersplat?style=social&color=white)](https://github.com/playcanvas/supersplat/stargazers)  
  Free and open-source (MIT) WebGL/WebGPU 3D Gaussian Splatting editor for inspecting, cropping, filtering floaters, and optimizing .ply and .sog splat scenes.

- **[Stable-Dreamfusion (`ashawkey/stable-dreamfusion`)](https://github.com/ashawkey/stable-dreamfusion)** [![GitHub stars](https://img.shields.io/github/stars/ashawkey/stable-dreamfusion?style=social&color=white)](https://github.com/ashawkey/stable-dreamfusion/stargazers)  
  PyTorch implementation of text-to-3D and image-to-3D generation using 2D diffusion models (Stable Diffusion) via Score Distillation Sampling (SDS).

- **[DUSt3R (`naver/dust3r`)](https://github.com/naver/dust3r)** [![GitHub stars](https://img.shields.io/github/stars/naver/dust3r?style=social&color=white)](https://github.com/naver/dust3r/stargazers)  
  Geometric 3D vision transformer that predicts dense 3D pointmaps directly from uncalibrated image pairs without requiring prior camera parameters or COLMAP.

- **[Threestudio (`threestudio-project/threestudio`)](https://github.com/threestudio-project/threestudio)** [![GitHub stars](https://img.shields.io/github/stars/threestudio-project/threestudio?style=social&color=white)](https://github.com/threestudio-project/threestudio/stargazers)  
  Unified modular PyTorch framework for 3D content creation from text, images, and point clouds using diverse diffusion priors and implicit representations.

- **[OpenAI Point-E (`openai/point-e`)](https://github.com/openai/point-e)** [![GitHub stars](https://img.shields.io/github/stars/openai/point-e?style=social&color=white)](https://github.com/openai/point-e/stargazers)  
  Official open-source (MIT) two-stage diffusion pipeline from OpenAI synthesizing synthetic views and generating colored 3D point clouds and SDF meshes.

- **[gsplat (`nerfstudio-project/gsplat`)](https://github.com/nerfstudio-project/gsplat)** [![GitHub stars](https://img.shields.io/github/stars/nerfstudio-project/gsplat?style=social&color=white)](https://github.com/nerfstudio-project/gsplat/stargazers)  
  CUDA-accelerated Python library for 3D Gaussian Splatting rasterization, memory-efficient backpropagation, and lightning-fast differentiable rendering.

- **[Apple Depth Pro (`apple/ml-depth-pro`)](https://github.com/apple/ml-depth-pro)** [![GitHub stars](https://img.shields.io/github/stars/apple/ml-depth-pro?style=social&color=white)](https://github.com/apple/ml-depth-pro/stargazers)  
  Foundation model for zero-shot metric monocular depth estimation producing sharp, high-frequency dense 3D point clouds and focal length predictions in sub-second time.

- **[Potree (`potree/potree`)](https://github.com/potree/potree)** [![GitHub stars](https://img.shields.io/github/stars/potree/potree?style=social&color=white)](https://github.com/potree/potree/stargazers)  
  Free open-source (BSD-2-Clause) WebGL point cloud renderer engineered to stream and visualize multi-billion-point LiDAR and photogrammetry datasets directly in browsers.

- **[PointNet (`charlesq34/pointnet`)](https://github.com/charlesq34/pointnet)** [![GitHub stars](https://img.shields.io/github/stars/charlesq34/pointnet?style=social&color=white)](https://github.com/charlesq34/pointnet/stargazers)  
  Pioneering deep learning architecture directly consuming raw unstructured 3D point clouds for 3D object classification, part segmentation, and scene parsing.

- **[Brush (`ArthurBrussee/brush`)](https://github.com/ArthurBrussee/brush)** [![GitHub stars](https://img.shields.io/github/stars/ArthurBrussee/brush?style=social&color=white)](https://github.com/ArthurBrussee/brush/stargazers)  
  Modern, high-performance universal 3D Gaussian Splatting viewer and reconstruction system written in Rust and WebGPU.

- **[CloudCompare (`CloudCompare/CloudCompare`)](https://github.com/CloudCompare/CloudCompare)** [![GitHub stars](https://img.shields.io/github/stars/CloudCompare/CloudCompare?style=social&color=white)](https://github.com/CloudCompare/CloudCompare/stargazers)  
  Industry-standard open-source (GPL-2.0+) 3D point cloud and triangular mesh processing suite for massive LiDAR registration, segmentation, and distance analysis.

- **[MASt3R (`naver/mast3r`)](https://github.com/naver/mast3r)** [![GitHub stars](https://img.shields.io/github/stars/naver/mast3r?style=social&color=white)](https://github.com/naver/mast3r/stargazers)  
  Matching and Stereo 3D Reconstruction pipeline extending DUSt3R with fast local feature matching and dense metric point cloud generation.

- **[PDAL (`PDAL/PDAL`)](https://github.com/PDAL/PDAL)** [![GitHub stars](https://img.shields.io/github/stars/PDAL/PDAL?style=social&color=white)](https://github.com/PDAL/PDAL/stargazers)  
  Point Data Abstraction Library providing composable pipelines for translating, filtering, and processing geospatial LiDAR point clouds in LAS, LAZ, and E57 formats.

- **[PointNeXt (`guochengqian/PointNeXt`)](https://github.com/guochengqian/PointNeXt)** [![GitHub stars](https://img.shields.io/github/stars/guochengqian/PointNeXt?style=social&color=white)](https://github.com/guochengqian/PointNeXt/stargazers)  
  Next-generation modernized PointNet++ baseline utilizing modern training techniques and inverted residual architectures for fast point cloud representation learning.

- **[LION (`nv-tlabs/LION`)](https://github.com/nv-tlabs/LION)** [![GitHub stars](https://img.shields.io/github/stars/nv-tlabs/LION?style=social&color=white)](https://github.com/nv-tlabs/LION/stargazers)  
  NVIDIA NeurIPS Hierarchical Latent Point Diffusion model combining Point-Voxel VAEs with dual latent diffusion models for high-resolution 3D shape generation.

- **[Diffusion Point Cloud (`luost26/diffusion-point-cloud`)](https://github.com/luost26/diffusion-point-cloud)** [![GitHub stars](https://img.shields.io/github/stars/luost26/diffusion-point-cloud?style=social&color=white)](https://github.com/luost26/diffusion-point-cloud/stargazers)  
  Foundational CVPR 2021 probabilistic diffusion model for 3D point cloud generation, auto-encoding, point completion, and unsupervised shape upsampling.

- **[GaussianAnything (`NIRVANALAN/GaussianAnything`)](https://github.com/NIRVANALAN/GaussianAnything)** [![GitHub stars](https://img.shields.io/github/stars/NIRVANALAN/GaussianAnything?style=social&color=white)](https://github.com/NIRVANALAN/GaussianAnything/stargazers)  
  ICLR 2025 cascaded 3D native diffusion pipeline utilizing a point-cloud structured latent space to generate editable 3D Gaussian assets from text or images.

- **[PVD (`alexzhou907/PVD`)](https://github.com/alexzhou907/PVD)** [![GitHub stars](https://img.shields.io/github/stars/alexzhou907/PVD?style=social&color=white)](https://github.com/alexzhou907/PVD/stargazers)  
  ICCV 2021 Point-Voxel Diffusion framework unifying point-level and voxel-level representations for 3D shape synthesis and dense point-cloud completion.

- **[google-research/pointdit (`google-research/pointdit`)](https://github.com/google-research/pointdit)** [![GitHub stars](https://img.shields.io/github/stars/google-research/pointdit?style=social&color=white)](https://github.com/google-research/pointdit/stargazers)  
  ICML 2026 open-source minimalist pixel-space Diffusion Transformer (ViT) conditioned on frozen DINOv3 tokens that directly denoises raw 3D point map patches.

- **[Occupancy Flow (`autonomousvision/occupancy_flow`)](https://github.com/autonomousvision/occupancy_flow)** [![GitHub stars](https://img.shields.io/github/stars/autonomousvision/occupancy_flow?style=social&color=white)](https://github.com/autonomousvision/occupancy_flow/stargazers)  
  4D reconstruction architecture learning continuous vector fields in space and time to capture dense motion and continuous generative shape representations.

- **[SLIDE (`SLIDE-3D/SLIDE`)](https://github.com/SLIDE-3D/SLIDE)** [![GitHub stars](https://img.shields.io/github/stars/SLIDE-3D/SLIDE?style=social&color=white)](https://github.com/SLIDE-3D/SLIDE/stargazers)  
  Sparse Latent Point Diffusion model encoding 3D geometries into sparse latent points with rich features for controllable point-cloud and mesh generation.

- **[SPVD (`JohnRomanelis/SPVD`)](https://github.com/JohnRomanelis/SPVD)** [![GitHub stars](https://img.shields.io/github/stars/JohnRomanelis/SPVD?style=social&color=white)](https://github.com/JohnRomanelis/SPVD/stargazers)  
  TNNLS 2025 Sparse Point-Voxel Diffusion framework leveraging TorchSparse for scalable conditional point cloud generation, completion, and super-resolution.

- **[DiffFacto (`diffFacto/diffFacto`)](https://github.com/diffFacto/diffFacto)** [![GitHub stars](https://img.shields.io/github/stars/diffFacto/diffFacto?style=social&color=white)](https://github.com/diffFacto/diffFacto/stargazers)  
  ICCV 2023 controllable part-based 3D point cloud generation model using cross-diffusion to factor independent part geometries and spatial configurations.

- **[Awesome-Point-Cloud-Generation (`Dekai21/Awesome-Point-Cloud-Generation`)](https://github.com/Dekai21/Awesome-Point-Cloud-Generation)** [![GitHub stars](https://img.shields.io/github/stars/Dekai21/Awesome-Point-Cloud-Generation?style=social&color=white)](https://github.com/Dekai21/Awesome-Point-Cloud-Generation/stargazers)  
  Curated chronological index of point-cloud diffusion, flow-matching, and autoregressive architectures (DiT-3D, TIGER, PSF, SeaLion).

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
