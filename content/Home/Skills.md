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
    <p>Python, MATLAB, Julia</p>
  </div>

  <div class="skills-category">
    <h3>Computational</h3>
    <p>
      <strong>Machine Learning & Data Science:</strong> NumPy, Pandas, Scikit-learn, TensorFlow, PyTorch<br>
      <strong>Neuroimaging:</strong> FSL, SPM<br>
      <strong>Software Engineering:</strong> Test Driven Development (TDD) "Google Test", Version Control "Git", CI/CD, CMake, LaTeX, Linux
    </p>
  </div>

  <div class="skills-category">
    <h3>Mathematical</h3>
    <p>Signal Processing, Large-scale Modelling and Data Analysis, Machine Learning, Probability Theory and Statistics, Dynamical Systems, Numerical Methods, Information Theory</p>
  </div>

  <div class="skills-category">
    <h3>Engineering</h3>
    <p>Arduino, TEMS, ACTIX Analyzer, Multisim, Logic Design, Oscilloscope</p>
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
