---
layout: page
title: Gaussian Splatting Thesis
tagline: Numerical Foundations and Performance Evaluation
description: Thesis by Nicolas Duque Molina
---

## Abstract
3D Gaussian Splatting (3DGS) offers a powerful alternative to traditional photogrammetry, yet its sensitivity to input data and hyperparameters remains underexplored. This work systematically evaluates the 3DGS pipeline to analyze the impact of sampling rates and training parameters on reconstruction fidelity and efficiency. Contrary to the assumption that higher data density linearly improves quality, our results reveal a non-monotonic relationship where excessive redundancy destabilizes the Structure-from-Motion process. Furthermore, we demonstrate that exhaustive optimization strategies are inefficient; extended training durations lead to "geometric bloat", a phenomenon where model size increases disproportionately to visual gains and compromises real-time performance on consumer hardware. We also validate the necessity of anisotropic covariance for preserving high-frequency details to resolve discrepancies between quantitative metrics and perceptual quality. Ultimately, this work identifies an optimal configuration that balances visual fidelity with storage and rendering constraints to provide a validated framework for the efficient deployment of 3DGS.
**Keywords:** 3D Gaussian Splatting, Photogrammetry, Structure-from-Motion (SfM), Sensitivity Analysis,Novel View Synthesis

## Resumen
El 3D Gaussian Splatting (3DGS) ofrece una alternativa potente a la fotogrametría tradicional; sin embargo, su sensibilidad a las características de los datos de entrada y a la configuración de hiperparámetros permanece poco explorada. Este trabajo evalúa sistemáticamente el flujo de trabajo de 3DGS para analizar el impacto de las tasas de muestreo y los parámetros de entrenamiento sobre la fidelidad de la reconstrucción y la eficiencia computacional. Contrario a la suposición de que una mayor densidad de datos mejora linealmente la calidad, nuestros resultados revelan una relación no monótona en la que la redundancia excesiva desestabiliza el proceso de Structure-from-Motion. Además, demostramos que las estrategias de optimización exhaustiva resultan ineficientes; los tiempos de entrenamiento extendidos conducen a una "inflación geométrica", un fenómeno donde el tamaño del modelo aumenta de manera desproporcionada respecto a las ganancias visuales y compromete el rendimiento en tiempo real en hardware de consumo. Asimismo, validamos la necesidad de la covarianza anisotrópica para preservar los detalles de alta frecuencia y resolver las discrepancias entre las métricas cuantitativas y la calidad perceptual. Finalmente, este trabajo identifica una configuración óptima que equilibra la fidelidad visual con las restricciones de almacenamiento y renderizado para proporcionar un marco validado para el despliegue eficiente de 3DGS.
**Palabras Clave:** 3D Gaussian Splatting, Fotogrametría, Estructura a partir del Movimiento (SfM), Análisis de Sensibilidad, Síntesis de Vistas

<div class="d-flex justify-content-center" style="gap: 1rem; margin: 2rem 0;">
  <a href="URL_DE_TU_PDF_EN_EL_REPO_O_DRIVE" class="btn btn-primary btn-lg">
    <i class="fas fa-file-pdf"></i> Read here/Leer aquí (PDF)
  </a>
</div>

## Video Demonstration
<div class="video-container" style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; margin-top: 1rem;">
  <iframe src="https://www.youtube.com/embed/QCtsvlz0mog" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" frameborder="0" allowfullscreen></iframe>
</div>
