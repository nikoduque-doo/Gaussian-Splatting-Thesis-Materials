---
layout: page
title: Codebase and Dataset
icon: fas fa-database
order: 3
---

This section hosts the raw experimental artifacts. Each scene includes the trained point cloud model (`.ply`) and configuration logs for the three main experimental variations.

<div class="row mb-4 g-2">
  <div class="col-md-6">
    <a href="https://github.com/nikoduque-doo/Gaussian-Splatting-Numerical-Foundations-and-Performance-Evaluation" target="_blank" class="btn btn-dark w-100 py-2 shadow-sm">
      <i class="fab fa-github fa-lg me-2"></i> View Source Code
    </a>
  </div>
  <div class="col-md-6">
    <a href="https://playcanvas.com/supersplat/editor" target="_blank" class="btn btn-primary w-100 py-2 shadow-sm" style="background-color: #2c3e50; border-color: #2c3e50;">
      <i class="fas fa-cube fa-lg me-2"></i> Launch SuperSplat Viewer
    </a>
  </div>
</div>

---


## How to visualize the artifacts

The easiest way to inspect the results is using the web-based **SuperSplat** viewer. No installation is required.

1.  **Download:** Click the download button for any experiment above (e.g., `Estatuas Exp 1`). This will download a `.zip` file from Hugging Face.
2.  **Launch:** Launch the [SuperSplat Viewer](https://playcanvas.com/supersplat/editor).
3.  **Drag & Drop:** Drag the `.ssproj` file directly into the browser window.

## Experiment Key

| ID | Description |
|:---|:---|
| **Exp 1** | **Baseline Model.** Standard Gaussian Splatting parameters (30k iterations). |
| **Exp 4** | **Long Training.** Extended training duration (60k+ iterations) for finer details. |
| **Exp 7** | **No Scaling/Rotation.** Geometry ablation study with restricted transformations. |

---

## Dataset

<div class="d-flex align-items-center mb-3">
  <span class="me-2">Hosted on:</span>
  <a href="https://huggingface.co/datasets/niduque/GaussianSplattingBogota" target="_blank">
    <img src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Datasets-yellow" alt="Hugging Face Datasets">
  </a>
</div>

<div class="alert alert-warning d-flex align-items-center" role="alert">
  <i class="fas fa-exclamation-triangle me-3 fa-lg"></i>
  <div>
    <strong>Large Files Warning:</strong> Each experiment is approx <strong>400-1200 MB</strong>. 
    Total dataset size exceeds 20 GB.
  </div>
</div>

<div class="table-responsive">
  <table class="table table-hover align-middle">
    <thead class="table-light">
      <tr>
        <th scope="col" style="width: 5%">ID</th>
        <th scope="col" style="width: 35%">Scene</th>
        <th scope="col" style="width: 60%">Download Models (.ply)</th>
      </tr>
    </thead>
    <tbody>

      <tr class="table-secondary">
        <td colspan="3" class="fw-bold text-uppercase small text-muted spacing-1">
          <i class="fas fa-user-tag me-2"></i> Custom Dataset (Author's Collection)
        </td>
      </tr>
      
      <tr>
        <th scope="row">01</th>
        <td>
          <strong>Estatuas</strong><br>
          <span class="text-muted small">Indoor</span>
        </td>
        <td>
          <div class="btn-group w-100" role="group">
            <a href="https://huggingface.co/datasets/niduque/GaussianSplattingBogota/resolve/main/Estatuas_50P_20FPS_Exp1.ssproj?download=true" class="btn btn-outline-primary btn-sm" title="Exp 1: Baseline">
              <i class="fas fa-download"></i> Exp 1
            </a>
            <a href="https://huggingface.co/datasets/niduque/GaussianSplattingBogota/resolve/main/Estatuas_50P_20FPS_Exp2.ssproj?download=true" class="btn btn-outline-primary btn-sm" title="Exp 2: High Positional LR">
              <i class="fas fa-download"></i> Exp 2
            </a>
            <a href="https://huggingface.co/datasets/niduque/GaussianSplattingBogota/resolve/main/Estatuas_50P_20FPS_Exp4.ssproj?download=true" class="btn btn-outline-primary btn-sm" title="Exp 4: Long Train">
              <i class="fas fa-download"></i> Exp 4
            </a>
          </div>
        </td>
      </tr>

      <tr>
        <th scope="row">02</th>
        <td>
          <strong>Sala Profes</strong><br>
          <span class="text-muted small">Indoor</span>
        </td>
        <td>
          <div class="btn-group w-100" role="group">
            <a href="https://huggingface.co/datasets/niduque/GaussianSplattingBogota/resolve/main/SalaProfe2_30P_10FPS_Exp1.ssproj?download=true" class="btn btn-outline-primary btn-sm" title="Exp 1: Baseline">
              <i class="fas fa-download"></i> Exp 1
            </a>
            <a href="https://huggingface.co/datasets/niduque/GaussianSplattingBogota/resolve/main/SalaProfe2_30P_10FPS_Exp2.ssproj?download=true" class="btn btn-outline-primary btn-sm" title="Exp 2: High Positional LR">
              <i class="fas fa-download"></i> Exp 2
            </a>
            <a href="https://huggingface.co/datasets/niduque/GaussianSplattingBogota/resolve/main/SalaProfe2_30P_10FPS_Exp4.ssproj?download=true" class="btn btn-outline-primary btn-sm" title="Exp 4: Long Train">
              <i class="fas fa-download"></i> Exp 4
            </a>
          </div>
        </td>
      </tr>

      <tr>
        <th scope="row">03</th>
        <td>
          <strong>UNAL</strong><br>
          <span class="text-muted small">Outdoor</span>
        </td>
        <td>
          <div class="btn-group w-100" role="group">
            <a href="https://huggingface.co/datasets/niduque/GaussianSplattingBogota/resolve/main/UNAL_50P_15FPS_Exp1.ssproj?download=true" class="btn btn-outline-primary btn-sm" title="Exp 1: Baseline">
              <i class="fas fa-download"></i> Exp 1
            </a>
            <a href="https://huggingface.co/datasets/niduque/GaussianSplattingBogota/resolve/main/UNAL_50P_15FPS_Exp2.ssproj?download=true" class="btn btn-outline-primary btn-sm" title="Exp 2: High Positional LR">
              <i class="fas fa-download"></i> Exp 2
            </a>
            <a href="https://huggingface.co/datasets/niduque/GaussianSplattingBogota/resolve/main/UNAL_50P_15FPS_Exp4.ssproj?download=true" class="btn btn-outline-primary btn-sm" title="Exp 4: Long Train">
              <i class="fas fa-download"></i> Exp 4
            </a>
          </div>
        </td>
      </tr>

      <tr>
        <th scope="row">04</th>
        <td>
          <strong>Virgen</strong><br>
          <span class="text-muted small">Outdoor</span>
        </td>
        <td>
          <div class="btn-group w-100" role="group">
            <a href="https://huggingface.co/datasets/niduque/GaussianSplattingBogota/resolve/main/Virgen_exp1.ssproj?download=true" class="btn btn-outline-primary btn-sm" title="Exp 1: Baseline">
              <i class="fas fa-download"></i> Exp 1
            </a>
            <a href="https://huggingface.co/datasets/niduque/GaussianSplattingBogota/resolve/main/Virgen_exp2.ssproj?download=true" class="btn btn-outline-primary btn-sm" title="Exp 2: High Positional LR">
              <i class="fas fa-download"></i> Exp 2
            </a>
            <a href="https://huggingface.co/datasets/niduque/GaussianSplattingBogota/resolve/main/Virgen_exp4.ssproj?download=true" class="btn btn-outline-primary btn-sm" title="Exp 4: Long Train">
              <i class="fas fa-download"></i> Exp 4
            </a>
          </div>
        </td>
      </tr>

      <tr class="table-secondary">
        <td colspan="3" class="fw-bold text-uppercase small text-muted spacing-1">
          <i class="fas fa-globe me-2"></i> Reference Datasets (State of the Art)
        </td>
      </tr>

      <tr>
        <th scope="row">05</th>
        <td>
          <strong>Dr Johnson</strong><br>
          <span class="text-muted small">
            Source: <a href="http://visual.cs.ucl.ac.uk/pubs/deepblending/datasets.html" target="_blank" class="text-decoration-none">Deep Blending</a>
          </span>
        </td>
        <td>
          <div class="btn-group w-100" role="group">
            <a href="https://huggingface.co/datasets/niduque/GaussianSplattingBogota/resolve/main/drjohnson_Exp1.ssproj?download=true" class="btn btn-outline-primary btn-sm" title="Exp 1: Baseline">
              <i class="fas fa-download"></i> Exp 1
            </a>
            <a href="https://huggingface.co/datasets/niduque/GaussianSplattingBogota/resolve/main/drjohnson_Exp2.ssproj?download=true" class="btn btn-outline-primary btn-sm" title="Exp 2: High Positional LR">
              <i class="fas fa-download"></i> Exp 2
            </a>
            <a href="https://huggingface.co/datasets/niduque/GaussianSplattingBogota/resolve/main/drjohnson_Exp4.ssproj?download=true" class="btn btn-outline-primary btn-sm" title="Exp 4: Long Train">
              <i class="fas fa-download"></i> Exp 4
            </a>
          </div>
        </td>
      </tr>

      <tr>
        <th scope="row">06</th>
        <td>
          <strong>Playroom</strong><br>
          <span class="text-muted small">
            Source: <a href="http://visual.cs.ucl.ac.uk/pubs/deepblending/datasets.html" target="_blank" class="text-decoration-none">Deep Blending</a>
          </span>
        </td>
        <td>
          <div class="btn-group w-100" role="group">
            <a href="https://huggingface.co/datasets/niduque/GaussianSplattingBogota/resolve/main/playroom_Exp1.ssproj?download=true" class="btn btn-outline-primary btn-sm" title="Exp 1: Baseline">
              <i class="fas fa-download"></i> Exp 1
            </a>
            <a href="https://huggingface.co/datasets/niduque/GaussianSplattingBogota/resolve/main/playroom_Exp2.ssproj?download=true" class="btn btn-outline-primary btn-sm" title="Exp 2: High Positional LR">
              <i class="fas fa-download"></i> Exp 2
            </a>
            <a href="https://huggingface.co/datasets/niduque/GaussianSplattingBogota/resolve/main/playroom_Exp4.ssproj?download=true" class="btn btn-outline-primary btn-sm" title="Exp 4: Long Train">
              <i class="fas fa-download"></i> Exp 4
            </a>
          </div>
        </td>
      </tr>

      <tr>
        <th scope="row">07</th>
        <td>
          <strong>Train</strong><br>
          <span class="text-muted small">
            Source: <a href="https://www.tanksandtemples.org/" target="_blank" class="text-decoration-none">Tanks & Temples</a>
          </span>
        </td>
        <td>
          <div class="btn-group w-100" role="group">
            <a href="https://huggingface.co/datasets/niduque/GaussianSplattingBogota/resolve/main/train_Exp1.ssproj?download=true" class="btn btn-outline-primary btn-sm" title="Exp 1: Baseline">
              <i class="fas fa-download"></i> Exp 1
            </a>
            <a href="https://huggingface.co/datasets/niduque/GaussianSplattingBogota/resolve/main/train_Exp2.ssproj?download=true" class="btn btn-outline-primary btn-sm" title="Exp 2: High Positional LR">
              <i class="fas fa-download"></i> Exp 2
            </a>
            <a href="https://huggingface.co/datasets/niduque/GaussianSplattingBogota/resolve/main/train_Exp4.ssproj?download=true" class="btn btn-outline-primary btn-sm" title="Exp 4: Long Train">
              <i class="fas fa-download"></i> Exp 4
            </a>
          </div>
        </td>
      </tr>

      <tr>
        <th scope="row">08</th>
        <td>
          <strong>Truck</strong><br>
          <span class="text-muted small">
            Source: <a href="https://www.tanksandtemples.org/" target="_blank" class="text-decoration-none">Tanks & Temples</a>
          </span>
        </td>
        <td>
          <div class="btn-group w-100" role="group">
            <a href="https://huggingface.co/datasets/niduque/GaussianSplattingBogota/resolve/main/truck_Exp1.ssproj?download=true" class="btn btn-outline-primary btn-sm" title="Exp 1: Baseline">
              <i class="fas fa-download"></i> Exp 1
            </a>
            <a href="https://huggingface.co/datasets/niduque/GaussianSplattingBogota/resolve/main/truck_Exp2.ssproj?download=true" class="btn btn-outline-primary btn-sm" title="Exp 2: High Positional LR">
              <i class="fas fa-download"></i> Exp 2
            </a>
            <a href="https://huggingface.co/datasets/niduque/GaussianSplattingBogota/resolve/main/truck_Exp4.ssproj?download=true" class="btn btn-outline-primary btn-sm" title="Exp 4: Long Train">
              <i class="fas fa-download"></i> Exp 4
            </a>
          </div>
        </td>
      </tr>

    </tbody>
  </table>
</div>