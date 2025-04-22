---

widget: markdown
headless: true  # This file represents a page section.

# Put Your Section Options Here (title, background, etc.) ...
title: Skills
active: true

subtitle:
weight: 30 # The position of section on page

text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
---
<section class="skills-cover">
  <div class="skills-category">
    <h3>Programming</h3>
    <p> <strong> Languages:</strong>
    Python (fluent), MATLAB, Julia <br>
     <strong> ML & Data Science:</strong> PyTorch, TensorFlow, Transformers (HuggingFace), Scikit-learn, NumPy,
Pandas, SciPy, torchvision, Matplotlib, Seaborn  <br>
    <strong>Software Engineering:</strong> Test-Driven Development (TDD; Google Test), Continuous Integration/Continuous Deployment (CI/CD), Git Version Control, API Integration (FastAPI), CMake,
    Linux Environments
     </p>

  </div>

  <div class="skills-category">
    <h3>Computational</h3>
    <p>
    Machine Learning & Deep Learning, Large-scale Modelling and high-dimensional Data Analysis, Multimodal signal processing, Dynamical Systems, Numerical Methods, Probability & Statistics, Information Theory
    </p>
  </div>


  <div class="skills-category">
    <h3>Neurotechnology</h3>
    <p>fMRI Analysis (FSL, SPM), EEG/EMG Acquisition & Processing, Embedded Systems (ESP32 Microcontroller), Electronics Simulation (Multisim), Hardware Measurement Tools (Open Ephys,
Oscilloscope)</p>
  </div>
</section>

<style>
  .skills-cover {
    max-width: 800px;
    padding: 20px;
    border-radius: 10px;
    width: 100%;
    box-sizing: border-box;
  }
  .skills-category {
    margin-bottom: 20px;
    display: inline-block;
    vertical-align: top;
    margin: 10px;
  }
  .skills-category h3 {
    font-size: 1em;
    border-bottom: 1px solid #cccccc;
    padding-bottom: 5px;
    margin-bottom: 10px;
    margin: 0 0 5px 0;
  }
  .skills-category p {
    font-size: 0.8em;
    margin: 0;
    line-height: 1.5;
  }
  .skills-category strong {
    font-weight: bold;
  }
</style>
