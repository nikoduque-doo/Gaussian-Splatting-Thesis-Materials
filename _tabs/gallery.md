---
layout: page
icon: fas fa-images
order: 2
title: Gallery
---

Aquí puedes ver las comparaciones visuales de alta resolución.

## Scene 1: Estatuas

<div class="container-fluid mb-5 p-4 rounded" style="background-color: rgba(255,255,255,0.03);">

  <div class="row justify-content-center mb-3">
    <div class="col-12 text-center text-muted small text-uppercase spacing-1">
      Full Scene Geometry
    </div>
  </div>

  <div class="row justify-content-center g-3 mb-3">
    
    <div class="col-md-6 d-flex flex-column align-items-center">
      <img src="/assets/img/thesis/EstatuasGT.png" class="img-fluid rounded shadow-sm" alt="GT Full">
      <div class="text-center small text-muted mt-2">GT (Full)</div>
    </div>

    <div class="col-md-6 d-flex flex-column align-items-center">
      <img src="/assets/img/thesis/EstatuasExp1.png" class="img-fluid rounded shadow-sm" alt="Exp 1 Full">
      <div class="text-center small text-muted mt-2">Exp. 1 Baseline (Full)</div>
    </div>

    <div class="col-md-6 d-flex flex-column align-items-center mt-3">
      <img src="/assets/img/thesis/EstatuasExp4.png" class="img-fluid rounded shadow-sm" alt="Exp 4 Full">
      <div class="text-center small text-muted mt-2">Exp. 4 Long Train (Full)</div>
    </div>

    <div class="col-md-6 d-flex flex-column align-items-center mt-3">
      <img src="/assets/img/thesis/EstatuasExp7.png" class="img-fluid rounded shadow-sm" alt="Exp 7 Full">
      <div class="text-center small text-muted mt-2">Exp. 7 No Scaling/Rotation (Full)</div>
    </div>
  </div>

  <hr class="my-4 mx-auto" style="width: 80%; border-top: 1px solid var(--text-muted-color); opacity: 0.3;">

  <div class="row justify-content-center mb-3">
    <div class="col-12 text-center text-muted small text-uppercase spacing-1">
      High-Frequency Texture Details (Zoom)
    </div>
  </div>

  <div class="row justify-content-center g-3">
    
    <div class="col-md-6 d-flex flex-column align-items-center">
      <img src="/assets/img/thesis/EstatuasZoomGT.png" class="img-fluid rounded shadow-sm" alt="GT Detail">
      <div class="text-center small text-muted mt-2">(a) GT Detail</div>
    </div>

    <div class="col-md-6 d-flex flex-column align-items-center">
      <img src="/assets/img/thesis/EstatuasZoomEXP1.png" class="img-fluid rounded shadow-sm" alt="Exp 1 Detail">
      <div class="text-center small text-muted mt-2">(b) Exp. 1 Baseline Detail</div>
    </div>

    <div class="col-md-6 d-flex flex-column align-items-center mt-3">
      <img src="/assets/img/thesis/EstatuasZoomEXP4.png" class="img-fluid rounded shadow-sm" alt="Exp 4 Detail">
      <div class="text-center small text-muted mt-2">(c) Exp. 4 Long Train Detail</div>
    </div>

    <div class="col-md-6 d-flex flex-column align-items-center mt-3">
      <img src="/assets/img/thesis/EstatuasZoomEXP7.png" class="img-fluid rounded shadow-sm" alt="Exp 7 Detail">
      <div class="text-center small text-muted mt-2">(d) Exp. 7 No Scaling/Rotation Detail</div>
    </div>
  </div>

  <figcaption class="figure-caption text-center mt-4 pt-3 border-top border-secondary">
    <strong>Figure 1: Visual progression of Estatuas Scene.</strong><br>
    <span class="text-muted">Note how the baseline models blur the pedestal details, while the full training restores high-frequency textures.</span>
  </figcaption>

</div>
