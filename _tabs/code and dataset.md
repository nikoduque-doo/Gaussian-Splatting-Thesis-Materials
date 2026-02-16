---
layout: page
title: Codebase and Dataset
icon: fas fa-database
order: 3
---

This section hosts the raw experimental artifacts. Each scene includes the trained point cloud model (`.ply`) and configuration logs for the three main experimental variations.


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

<div class="row mb-4 g-2">
  <div class="col-md-6">
    <a href="LINK_A_TU_REPO_DE_GITHUB_AQUI" target="_blank" class="btn btn-dark w-100 py-2 shadow-sm">
      <i class="fab fa-github fa-lg me-2"></i> View Source Code
    </a>
  </div>
  <div class="col-md-6">
    <a href="https://playcanvas.com/supersplat/editor" target="_blank" class="btn btn-primary w-100 py-2 shadow-sm" style="background-color: #2c3e50; border-color: #2c3e50;">
      <i class="fas fa-cube fa-lg me-2"></i> Launch SuperSplat Viewer
    </a>
  </div>
</div>

<div class="d-flex align-items-center mb-3">
  <span class="me-2">Hosted on:</span>
  <a href="TU_URL_DEL_REPO_DE_HUGGING_FACE" target="_blank">
    <img src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Datasets-yellow" alt="Hugging Face Datasets">
  </a>
</div>

<div class="alert alert-warning d-flex align-items-center" role="alert">
  <i class="fas fa-exclamation-triangle me-3 fa-lg"></i>
  <div>
    <strong>Large Files Warning:</strong> Each experiment is approx <strong>300-400 MB</strong>. 
    Total dataset size exceeds 15 GB. We recommend downloading via Wi-Fi.
  </div>
</div>

<div class="table-responsive">
  <table class="table table-hover align-middle">
    <thead class="table-light">
      <tr>
        <th scope="col" style="width: 5%">ID</th>
        <th scope="col" style="width: 25%">Scene</th>
        <th scope="col" style="width: 20%">Specs</th>
        <th scope="col" style="width: 50%">Download Models (.ply)</th>
      </tr>
    </thead>
    <tbody>
      
      <tr>
        <th scope="row">01</th>
        <td>
          <strong>Estatuas</strong><br>
          <span class="text-muted small">Outdoor / Complex</span>
        </td>
        <td>
          <span class="badge bg-light text-dark border">4K</span>
          <span class="badge bg-light text-dark border">30k Iter</span>
        </td>
        <td>
          <div class="btn-group w-100" role="group">
            <a href="LINK_ESTATUAS_EXP1" class="btn btn-outline-primary btn-sm" title="Exp 1: Baseline">
              <i class="fas fa-download"></i> Exp 1
            </a>
            <a href="LINK_ESTATUAS_EXP4" class="btn btn-outline-primary btn-sm" title="Exp 4: Long Train">
              <i class="fas fa-download"></i> Exp 4
            </a>
            <a href="LINK_ESTATUAS_EXP7" class="btn btn-outline-primary btn-sm" title="Exp 7: No Scaling">
              <i class="fas fa-download"></i> Exp 7
            </a>
          </div>
        </td>
      </tr>

      <tr>
        <th scope="row">02</th>
        <td>
          <strong>Sala Profes</strong><br>
          <span class="text-muted small">Indoor / Low Light</span>
        </td>
        <td>
          <span class="badge bg-light text-dark border">1080p</span>
          <span class="badge bg-light text-dark border">Indoor</span>
        </td>
        <td>
          <div class="btn-group w-100" role="group">
            <a href="LINK_SALA_EXP1" class="btn btn-outline-primary btn-sm" title="Exp 1: Baseline">
              <i class="fas fa-download"></i> Exp 1
            </a>
            <a href="LINK_SALA_EXP4" class="btn btn-outline-primary btn-sm" title="Exp 4: Long Train">
              <i class="fas fa-download"></i> Exp 4
            </a>
            <a href="LINK_SALA_EXP7" class="btn btn-outline-primary btn-sm" title="Exp 7: No Scaling">
              <i class="fas fa-download"></i> Exp 7
            </a>
          </div>
        </td>
      </tr>

      <tr>
        <th scope="row">03</th>
        <td>
          <strong>UNAL</strong><br>
          <span class="text-muted small">Large Scale / Drone</span>
        </td>
        <td>
          <span class="badge bg-light text-dark border">4K</span>
          <span class="badge bg-light text-dark border">Drone</span>
        </td>
        <td>
          <div class="btn-group w-100" role="group">
            <a href="LINK_UNAL_EXP1" class="btn btn-outline-primary btn-sm" title="Exp 1: Baseline">
              <i class="fas fa-download"></i> Exp 1
            </a>
            <a href="LINK_UNAL_EXP4" class="btn btn-outline-primary btn-sm" title="Exp 4: Long Train">
              <i class="fas fa-download"></i> Exp 4
            </a>
            <a href="LINK_UNAL_EXP7" class="btn btn-outline-primary btn-sm" title="Exp 7: No Scaling">
              <i class="fas fa-download"></i> Exp 7
            </a>
          </div>
        </td>
      </tr>

      <tr>
        <th scope="row">04</th>
        <td>
          <strong>Virgen</strong><br>
          <span class="text-muted small">Object Focus</span>
        </td>
        <td>
          <span class="badge bg-light text-dark border">4K</span>
          <span class="badge bg-light text-dark border">Masked</span>
        </td>
        <td>
          <div class="btn-group w-100" role="group">
            <a href="LINK_VIRGEN_EXP1" class="btn btn-outline-primary btn-sm" title="Exp 1: Baseline">
              <i class="fas fa-download"></i> Exp 1
            </a>
            <a href="LINK_VIRGEN_EXP4" class="btn btn-outline-primary btn-sm" title="Exp 4: Long Train">
              <i class="fas fa-download"></i> Exp 4
            </a>
            <a href="LINK_VIRGEN_EXP7" class="btn btn-outline-primary btn-sm" title="Exp 7: No Scaling">
              <i class="fas fa-download"></i> Exp 7
            </a>
          </div>
        </td>
      </tr>

    </tbody>
  </table>
</div>
