---
permalink: /lagrangiansplats/
title: "LagrangianSplats"
excerpt: "Divergence-Free Transport of Gaussian Primitives for Fluid Reconstruction"
author_profile: false
---

<div class="project-page">
  <header class="project-hero">
    <h1>LagrangianSplats: Divergence-Free Transport of Gaussian Primitives for Fluid Reconstruction</h1>
    <p class="project-venue">SIGGRAPH 2026 Conference Paper</p>
    <p class="project-authors">
      <strong>Ningxiao Tao</strong>, Baoquan Chen<sup>&dagger;</sup>, Mengyu Chu<sup>&dagger;</sup>
    </p>
    <p class="project-affiliation">Peking University</p>
    <p class="project-note"><sup>&dagger;</sup> Corresponding authors</p>
    <nav class="project-links" aria-label="Project links">
      <a href="/files/LagrangianSplats.pdf">
        <i class="fas fa-file-pdf" aria-hidden="true"></i>
        <span>Paper</span>
      </a>
      <a href="https://arxiv.org/abs/2605.09299">
        <i class="ai ai-arxiv" aria-hidden="true"></i>
        <span>arXiv</span>
      </a>
      <a href="https://drive.google.com/file/d/1tIE-u1iUoxtvsYSlITk23rTcN2kQwP-6/view?usp=drive_link">
        <i class="fas fa-file-alt" aria-hidden="true"></i>
        <span>Supp</span>
      </a>
      <a href="https://www.bilibili.com/video/BV1DLVM63ExF">
        <i class="fas fa-play" aria-hidden="true"></i>
        <span>Video</span>
      </a>
      <a href="https://github.com/taoningxiao/LagrangianSplats.git">
        <i class="fab fa-github" aria-hidden="true"></i>
        <span>Code</span>
      </a>
      <a href="https://huggingface.co/datasets/tnx123/LagrangianSplats-Dataset">
        <i class="fas fa-database" aria-hidden="true"></i>
        <span>Dataset</span>
      </a>
    </nav>
  </header>

  <figure class="project-teaser">
    <img src="/images/LagrangianSplats-teaser.png" alt="LagrangianSplats teaser">
    <figcaption>
      LagrangianSplats reconstructs physically valid 3D fluid motion from sparse 2D observations by transporting Gaussian primitives with a divergence-free velocity representation.
    </figcaption>
  </figure>

  <hr>

  <section class="project-section project-video">
    <h2>Video</h2>
    <div class="project-video-frame">
      <iframe
        src="https://player.bilibili.com/player.html?bvid=BV1DLVM63ExF&page=1&autoplay=0"
        title="LagrangianSplats video on Bilibili"
        scrolling="no"
        border="0"
        frameborder="no"
        framespacing="0"
        allowfullscreen="true">
      </iframe>
    </div>
  </section>

  <hr>

  <section class="project-section">
    <h2>Abstract</h2>
    <p>
      Reconstructing 3D fluid velocity fields from sparse 2D video observations is a highly ill-posed inverse problem,
      demanding both transport consistency with observed motion and physical validity under fluid laws. Existing methods
      typically impose these constraints through soft penalties, often leading to compromised accuracy and convergence
      issues. We introduce a reconstruction framework that structurally enforces both constraints.
    </p>
    <p>
      Specifically, we parameterize the reconstructed velocity using a continuous Divergence-Free Kernel representation,
      driving the advection of a Lagrangian 3D Gaussian Splatting representation. This formulation intrinsically guarantees
      both flow incompressibility and long-range transport coherence by construction. To enable efficient optimization of
      such a constrained system, we introduce a Sliding Window scheme that propagates gradients over meaningful temporal
      horizons while maintaining tractable training costs.
    </p>
  </section>

  <hr>

  <section class="project-section">
    <h2>Overview</h2>
    <p>
      Our method couples a Lagrangian 3D Gaussian Splatting representation with a continuous Divergence-Free Kernel
      velocity field, enforcing incompressibility by construction while maintaining transport coherence over long time
      horizons. A sliding-window optimization scheme makes the constrained reconstruction tractable, allowing gradients
      to propagate through meaningful temporal intervals without requiring full-sequence backpropagation.
    </p>
  </section>

  <hr>

  <section class="project-section">
    <h2>Dataset</h2>
    <p>
      We release the LagrangianSplats dataset for fluid reconstruction research. The dataset is available on
      <a href="https://huggingface.co/datasets/tnx123/LagrangianSplats-Dataset">Hugging Face</a>.
    </p>
  </section>

  <hr>

  <section class="project-section">
    <h2>Citation</h2>
    <pre class="project-bibtex"><code>@article{tao2026lagrangiansplats,
  title={LagrangianSplats: Divergence-Free Transport of Gaussian Primitives for Fluid Reconstruction},
  author={Tao, Ningxiao and Chen, Baoquan and Chu, Mengyu},
  journal={arXiv preprint arXiv:2605.09299},
  year={2026}
}</code></pre>
  </section>
</div>
